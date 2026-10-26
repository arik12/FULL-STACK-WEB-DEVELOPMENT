<div align="center">

# CSS (Cascading Style Sheets)
## Web Development Notes

</div>

# Introduction 

Imagine you are building a house.  
First, you construct the basic structure of the house walls, doors, windows, roof and rooms. Without this structure, the house cannot exist properly.In the same way, HTML creates the basic structure of a website.

But a plain structured house does not look attractive. It feels empty and boring.

Now think about what happens next. You start decorating the house. You paint the walls with beautiful colors, add lights in every room, place stylish furniture, hang curtains, and design everything in a modern way. After decoration, the house becomes beautiful, comfortable, and visually attractive.

This decoration part is exactly what CSS does for a web page.

CSS stands for **Cascading Style Sheets**. It is used to style and design HTML elements. If HTML is the skeleton of a website, then CSS is the skin, colors, and fashion of that website.

With CSS, we can:
- Add colors to text and background
- Control layout and spacing
- Make websites responsive for mobile and desktop
- Add animations and effects
- Improve overall user experience

Without CSS, websites would look very plain, just like black-and-white text pages with no design.

So, HTML builds the structure, and CSS makes it beautiful.

---

# History of CSS

CSS was first introduced in **1996** by **Håkon Wium Lie**, while working with the World Wide Web Consortium (W3C).

At that time, HTML was used only for structure, but developers needed a separate system to style webpages properly. Before CSS, developers used to add styling directly inside HTML, which made code messy and difficult to manage.

CSS was created to solve this problem by separating structure (HTML) from design (CSS).

The main idea of CSS was:
> “Keep content and design separate so websites become easier to build and maintain.”

Over time, CSS improved with new versions:
- CSS1 introduced basic styling features like colors and fonts
- CSS2 added layouts and positioning
- CSS3 introduced modern features like animations, transitions, gradients, and responsive design

Today, CSS3 is widely used in all modern websites and works together with HTML and JavaScript to build complete web applications.

---


---

## What is CSS?

CSS (Cascading Style Sheets) is an important part of modern web development because it controls how a website looks and feels. It is used with HTML to style elements like colors, fonts, spacing, and layout. Without CSS, web pages would appear plain and unorganized. It also helps create responsive designs, making websites look good on different devices.
In simple terms:  
- HTML = Structure  
- CSS = Design & Style  

CSS makes web pages visually attractive, user-friendly, and responsive.

---

## What can CSS do?

- 🎨 Change colors (text, background)
- 📏 Adjust size, margin, padding
- 📐 Control layout (Flexbox, Grid)
- ✨ Add animations and effects
- 📱 Responsive design
- 🔤 Font styling (font-family, font-weight, Google Fonts use)

---


##  A Short Story About CSS

Imagine a plain HTML page as a blank canvas.It has headings, paragraphs, and images but everything looks plain.  

Then CSS comes to help . It says, *"I can make your page colorful and styled!"*  

CSS can be added in **three ways**:  
- **External CSS** – using a separate `.css` file to style many pages  
- **Internal CSS** – using a `<style>` tag inside a single HTML page  
- **Inline CSS** – applying styles directly to an HTML element  

With these three ways, even a simple HTML page can become stylish and easy to read.



---

## Three Ways to Add CSS

### 1️⃣ External CSS 

```html

HTML

<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>Hello World</h1>

</body>
</html>

```

```css

styles.css

h1 {
  color: blue;
}


```

Note: External CSS is a method where CSS code is written in a separate .css file (like styles.css) and linked to an HTML file using the <link> tag.

### 2️⃣ Internal CSS 

```html

<!DOCTYPE html>
<html>
<head>
  <style>
    h1 {
      color: green;
    }
  </style>
</head>
<body>

<h1>Hello World</h1>

</body>
</html>

```
Note: Internal CSS is used to apply styles directly inside a single HTML page by using the <style> tag within the <head> section.

### 3️⃣ Inline CSS

```html

<!DOCTYPE html>
<html>
<head>
  <title>Inline CSS Example</title>
</head>
<body>

<h1 style="color: red;">Hello World</h1>

</body>
</html>



```

Note:Inline CSS applies styling directly within an HTML element by using the style attribute and affecting only that specific element.


---

## Understanding CSS Rules

CSS Rule Structure:

```

selector {
  property: value;
}

```

Selector: It targets the HTML element (like p, .class, #id) you want to style.

Declaration Block {}: The area where styles are written.

Property: What you want to change (e.g., color, background-color).

Value:The style you apply (e.g., blue, red).


Example 1


```

<p>I love pizza!</p>
<p>ummer vacation is the best!</p>
/* Make all paragraphs blue and fun */
p {
  color: blue; /* text color becomes blue */
  font-size: 18px; /* bigger text for fun */
}

```



Example 2


```

<!-- Heading and subheading -->
<h1 id="title">🚀 Big Heading</h1>
<h2 class="subheading">✨ Cool Subheading</h2>
<p>Normal paragraph</p>

/* Style both heading and subheading together */
#title,
.subheading {
  color: navy; /* text color turns navy */
  font-family: 'Arial', sans-serif; /* stylish font */
}


```


---


##  CSS Comments

CSS comments are used to explain code, make notes, or temporarily disable styles. These comments are ignored by the browser and do not affect the design.

### 🔹 Syntax

CSS comments start with `/*` and end with `*/`.

```css
/* This is a CSS comment */
```

### 🔹 Example

```css
/* Styling the main container */
.container {
  width: 100%;
  margin: 0 auto;
}

/* This will not apply
p {
  color: red;
}
*/
```

### 🔹 Why Use Comments?

* Improve code readability
* Explain complex styles
* Help during debugging
* Temporarily disable CSS rules

### 🔹 Tips

* Keep comments short and meaningful
* Avoid over-commenting obvious code
* Use comments to group related styles

---

 **Note:** Comments are very useful when working in teams or large projects.


---


## 🎨 CSS Background Properties

In this section, you will learn about different CSS background properties used to control the appearance of an element’s background.

### 🔹 List of Background Properties

* `background-color`
* `background-image`
* `background-repeat`
* `background-attachment`
* `background-position`
* `background` (shorthand)

---

### 🔹 `background-color`

Sets the background color of an element.

```css
body {
  background-color: lightblue;
}
```

---

### 🔹 `background-image`

Sets an image as the background.

```css
body {
  background-image: url("bg.jpg");
}
```

---

### 🔹 `background-repeat`

Controls how the background image repeats.

```css
body {
  background-repeat: no-repeat; /* repeat | repeat-x | repeat-y */
}
```

---

### 🔹 `background-attachment`

Defines whether the background image scrolls with the page or stays fixed.

```css
body {
  background-attachment: fixed; /* scroll | fixed */
}
```

---

### 🔹 `background-position`

Specifies the position of the background image.

```css
body {
  background-position: center; /* top, bottom, left, right */
}
```

---

### 🔹 `background` (Shorthand)

A short way to define multiple background properties in one line.

```css
body {
  background: lightblue url("bg.jpg") no-repeat fixed center;
}
```

---

💡 **Note:** Using shorthand helps keep your CSS clean and more readable.


---

## 🧱 CSS Border Style

The `border-style` property specifies what kind of border to display around an element.

---

### 🔹 Available Values

* `dotted` → Defines a dotted border
* `dashed` → Defines a dashed border
* `solid` → Defines a solid border
* `double` → Defines a double border
* `groove` → Defines a 3D grooved border (depends on `border-color`)
* `ridge` → Defines a 3D ridged border (depends on `border-color`)
* `inset` → Defines a 3D inset border (depends on `border-color`)
* `outset` → Defines a 3D outset border (depends on `border-color`)
* `none` → Defines no border
* `hidden` → Defines a hidden border

---

### 🔹 Example

```css id="b3n1qk"
p {
  border-style: solid;
}
```

---

### 🔹 Multiple Values Example

You can define different styles for each side (top, right, bottom, left):

```css id="z7f2ld"
p {
  border-style: dotted dashed solid double;
}
```

---

### 🔹 Visual Examples

```css id="uqw0fa"
.dotted  { border-style: dotted; }
.dashed  { border-style: dashed; }
.solid   { border-style: solid; }
.double  { border-style: double; }
.groove  { border-style: groove; }
.ridge   { border-style: ridge; }
.inset   { border-style: inset; }
.outset  { border-style: outset; }
.none    { border-style: none; }
.hidden  { border-style: hidden; }
```

---

💡 **Note:** To make the border visible, you usually need to set `border-width` and `border-color` along with `border-style`.

Example:

```css id="0d5f1y"
p {
  border-style: solid;
  border-width: 2px;
  border-color: black;
}
```

---


## 📦 CSS Margin - Individual Sides

CSS provides separate properties to control the margin on each side of an element.

---

### 🔹 Margin Properties

* `margin-top` → Sets the top margin
* `margin-right` → Sets the right margin
* `margin-bottom` → Sets the bottom margin
* `margin-left` → Sets the left margin

---

### 🔹 Example

```css id="v1k9pz"
p {
  margin-top: 20px;
  margin-right: 15px;
  margin-bottom: 20px;
  margin-left: 15px;
}
```

---

### 🔹 Possible Values

All margin properties can use the following values:

* `auto` → Browser automatically calculates the margin
* `length` → Fixed value (e.g., `px`, `pt`, `cm`)
* `%` → Relative to the width of the containing element
* `inherit` → Inherits margin from parent element

---

### 🔹 Example with Different Values

```css id="8r2lqm"
div {
  margin-top: 10px;
  margin-right: auto;
  margin-bottom: 5%;
  margin-left: inherit;
}
```

---

### 💡 Tip

Negative values are also allowed:

```css id="p4x7ab"
div {
  margin-top: -10px;
}
```

This can be useful for overlapping elements or adjusting layout spacing.

---

💡 **Note:** Margins control the space **outside** an element, unlike padding which controls space inside the element.


---


## 📦 CSS Padding - Individual Sides

CSS provides separate properties to control the padding on each side of an element.

---

### 🔹 Padding Properties

* `padding-top` → Sets the top padding
* `padding-right` → Sets the right padding
* `padding-bottom` → Sets the bottom padding
* `padding-left` → Sets the left padding

---

### 🔹 Example

```css id="k2m8zx"
div {
  padding-top: 20px;
  padding-right: 15px;
  padding-bottom: 20px;
  padding-left: 15px;
}
```

---

### 🔹 Possible Values

All padding properties can use the following values:

* `length` → Fixed value (e.g., `px`, `pt`, `cm`)
* `%` → Relative to the width of the containing element
* `inherit` → Inherits padding from parent element

---

### 🔹 Example with Different Values

```css id="r9d4ql"
div {
  padding-top: 10px;
  padding-right: 5%;
  padding-bottom: 15px;
  padding-left: inherit;
}
```

---

### ⚠️ Important Note

Negative values are **not allowed** in padding.

```css id="x1v7na"
/* ❌ Invalid */
div {
  padding-top: -10px;
}
```

---

💡 **Note:** Padding controls the space **inside** an element, between the content and the border.


---


## 📏 CSS Height and Width

The `height` and `width` properties are used to set the height and width of an element.

---

### 🔹 Example

This element has a height of **70 pixels** and a width of **100%**:

```css id="h3k9sd"
div {
  height: 70px;
  width: 100%;
}
```

---

### 🔹 Possible Values

Both `height` and `width` properties can use the following values:

* `auto` → Default value. The browser calculates the height and width
* `length` → Fixed value (e.g., `px`, `cm`, `em`)
* `%` → Relative to the size of the containing element
* `initial` → Sets the property to its default value
* `inherit` → Inherits the value from the parent element

---

### 🔹 Example with Different Values

```css id="7p2vla"
div {
  height: auto;
  width: 50%;
}
```

---

### 💡 Tips

* `width: 100%` makes the element take full width of its parent
* `height: auto` adjusts height based on content
* Avoid fixed heights when possible to keep layouts flexible

---

💡 **Note:** These properties control the size of an element’s content area (excluding padding, border, and margin).


---

## 📦 CSS Box Model

The CSS Box Model describes the structure of an element as a rectangular box. It consists of different layers from the **innermost** to the **outermost** part.

---

### 🔹 Parts of the Box Model

1. **Content**
   The actual content of the box where text, images, or other elements appear.

2. **Padding**
   Clears space around the content. The padding is transparent.

3. **Border**
   A border that wraps around the padding and content.

4. **Margin**
   Clears space outside the border. The margin is transparent.

---

### 🔹 Visual Structure (Inside → Outside)

```
Content → Padding → Border → Margin
```

---

### 🔹 Example

```css id="l8x2qp"
div {
  width: 200px;
  padding: 20px;
  border: 5px solid black;
  margin: 15px;
}
```

---

### 🔹 How It Works

* The **content** is the actual size (`width` & `height`)
* **Padding** adds space inside the element
* **Border** wraps around padding and content
* **Margin** creates space between elements

---

### 💡 Tip

Total element width =
`content width + padding + border + margin`

---

💡 **Note:** Understanding the box model is essential for layout and spacing in CSS.

---


## 📦 CSS Outline
 
CSS provides the `outline` property to draw a line around an element, outside its border. It doesn't take up space in the layout and doesn't affect other elements' positioning.
 
---
 
### 🔹 Outline Properties
 
* `outline-style` → Sets the style (solid, dashed, dotted, double, etc.)
* `outline-color` → Sets the color of the outline
* `outline-width` → Sets the thickness of the outline
* `outline-offset` → Sets the gap between the outline and the border
---
 
### 🔹 Example
 
```css
div {
  outline-style: solid;
  outline-color: red;
  outline-width: 3px;
  outline-offset: 5px;
}
```
 
---
 
### 🔹 Shorthand
 
```css
div {
  outline: 3px solid red;
}
```
 
---
 
### 🔹 Outline vs Border
 
| Feature | Border | Outline |
|---|---|---|
| Takes up space | ✅ Yes | ❌ No |
| Can style individual sides | ✅ Yes | ❌ No |
| Affects layout | ✅ Yes | ❌ No |


## 📦 CSS Text
 
CSS provides many properties to style and format text — color, alignment, decoration, spacing, transformation, and shadow.
 
---
 
### 🔹 Text Color
 
The `color` property sets the color of text.
 
```css
h1 {
  color: red;
}
 
p {
  color: #333333;
}
```
 
---
 
### 🔹 Text Alignment
 
The `text-align` property sets the horizontal alignment of text.
 
* `left` → Aligns text to the left (default)
* `right` → Aligns text to the right
* `center` → Centers the text
* `justify` → Stretches lines so each line has equal width
```css
h1 {
  text-align: center;
}
 
p {
  text-align: justify;
}
```
 
`text-align-last` sets how the **last line** of text is aligned.
 
`direction` and `unicode-bidi` can be used to change text direction (e.g., for right-to-left languages like Arabic or Bangla).
 
```css
p {
  direction: rtl;
}
```
 
`vertical-align` sets the vertical alignment of an inline or table-cell element.
 
```css
img {
  vertical-align: middle;
}
```
 
---
 
### 🔹 Text Decoration
 
The `text-decoration-line` property is used to add a line to text.
 
* `none` → No line (removes underline from links)
* `underline` → Underlines text
* `overline` → Adds a line above text
* `line-through` → Adds a strikethrough line
```css
h1 {
  text-decoration-line: overline;
}
 
h2 {
  text-decoration-line: line-through;
}
 
h3 {
  text-decoration-line: underline;
}
 
a {
  text-decoration-line: none;
}
```
 
`text-decoration-color` sets the color of the decoration line.
 
```css
h1 {
  text-decoration-line: underline;
  text-decoration-color: red;
}
```
 
`text-decoration-thickness` sets the thickness of the line.
 
```css
h1 {
  text-decoration-line: underline;
  text-decoration-thickness: 5px;
}
```
 
**Shorthand:**
 
```css
h1 {
  text-decoration: underline red 5px;
}
```
 
---
 
### 🔹 Text Decoration Styles
 
The `text-decoration-style` property sets the style of the decoration line.
 
* `solid` → A single line (default)
* `double` → A double line
* `dotted` → A dotted line
* `dashed` → A dashed line
* `wavy` → A wavy line
```css
h1 {
  text-decoration-line: underline;
  text-decoration-style: solid;
}
 
h2 {
  text-decoration-line: underline;
  text-decoration-style: double;
}
 
h3 {
  text-decoration-line: underline;
  text-decoration-style: dotted;
}
 
h4 {
  text-decoration-line: underline;
  text-decoration-style: dashed;
}
 
h5 {
  text-decoration-line: underline;
  text-decoration-style: wavy;
}
```
 
---
 
### 🔹 Text Transformation
 
The `text-transform` property controls the capitalization of text.
 
* `uppercase` → Transforms text to all UPPERCASE
* `lowercase` → Transforms text to all lowercase
* `capitalize` → Capitalizes the First Letter of Each Word
```css
p.uppercase {
  text-transform: uppercase;
}
 
p.lowercase {
  text-transform: lowercase;
}
 
p.capitalize {
  text-transform: capitalize;
}
```
 
---
 
### 🔹 Text Spacing
 
**Text Indentation** — `text-indent` indents the first line of text.
 
```css
p {
  text-indent: 50px;
}
```
 
**Letter Spacing** — `letter-spacing` sets the space between characters.
 
```css
h1 {
  letter-spacing: 3px;
}
 
h2 {
  letter-spacing: -2px;
}
```
 
**Line Height** — `line-height` sets the space between lines.
 
```css
p {
  line-height: 1.8;
}
```
 
**Word Spacing** — `word-spacing` sets the space between words.
 
```css
h1 {
  word-spacing: 10px;
}
 
h2 {
  word-spacing: -5px;
}
```
 
**White Space** — `white-space` controls how whitespace inside an element is handled.
 
```css
p {
  white-space: nowrap;
}
```
 
---
 
### 🔹 Text Shadow
 
The `text-shadow` property adds a shadow to text.
 
**Syntax:** `text-shadow: h-shadow v-shadow blur-radius color;`
 
```css
h1 {
  text-shadow: 2px 2px 5px red;
}
```
 
**Multiple shadows** can be added by comma-separating values:
 
```css
h1 {
  text-shadow: 0 0 3px #ff0000, 0 0 5px #0000ff;
}
```
 
---
 
### 🔹 Quick Summary Table
 
| Property | Purpose |
|---|---|
| `color` | Sets text color |
| `text-align` | Sets horizontal alignment |
| `text-decoration` | Adds line (underline, overline, etc.) |
| `text-decoration-style` | Sets style of decoration line |
| `text-transform` | Changes text case |
| `text-indent` | Indents first line |
| `letter-spacing` | Space between characters |
| `line-height` | Space between lines |
| `word-spacing` | Space between words |
| `white-space` | Controls whitespace handling |
| `text-shadow` | Adds shadow to text |

 

---


## 📖 একটা মজার গল্প: "CSS স্কুলের কাণ্ড"
 
একটা স্কুল ছিল নাম **HTML High School**। স্কুলটা দেখতে একদম সাদামাটা। দেয়াল সাদা, ছাত্রদের জামা সাদা, সবকিছু সাদা-কালো। 😴
 
একদিন স্কুলে নতুন একজন শিক্ষক এলেন। নাম **CSS স্যার**। তিনি ঢুকেই বললেন:
 
> "এই স্কুলটাকে আমি রঙিন করে দেবো!"
 
**প্রথম দিন:** স্যার বললেন, "Class 10 এর সবাই দাঁড়াও!"
সাথে সাথে Class 10 এর ৪০ জন ছাত্র দাঁড়িয়ে গেল। স্যার একবার বলেই সবাইকে নীল ইউনিফর্ম পরিয়ে দিলেন। ৪০ বার আলাদা করে বলতে হলো না।
 
এটাই হলো **Class**। 🎯 একবার বলো, সবার কাছে পৌঁছাও।
 
**দ্বিতীয় দিন:** স্যার বললেন, "Roll 7 এসো, তুমি আজ স্কুলের captain!"
শুধু একজন ছাত্র এগিয়ে এল, আর কেউ না। কারণ Roll নম্বর সবার আলাদা।
 
এটাই হলো **ID**। 🪪 শুধু একজনের জন্য, একদম unique।
 
**তৃতীয় দিন:** স্যার দেখলেন স্কুলের notice board এর লেখাগুলো সব একরকম, পড়তেই ইচ্ছে করে না। তিনি বললেন, "লেখার পোশাক বদলাতে হবে!" কোনোটা মোটা, কোনোটা বাঁকা, কোনোটা বড় হরফে।
 
এটাই হলো **Font**। ✍️ লেখার পোশাক।
 
কিছুদিন পর স্কুলটা পুরো শহরের সবচেয়ে সুন্দর স্কুল হয়ে গেল। আর HTML High School এর প্রিন্সিপাল সবাইকে বললেন:
 
> "আমি তো শুধু দালান বানিয়েছিলাম। সৌন্দর্য এনেছে CSS স্যার।" 😎
 
**গল্পের শিক্ষা:** HTML হলো ঘর, CSS হলো ঘরের রং, সাজসজ্জা আর আসবাব। ঘর ছাড়া সাজানো যায় না, আর সাজানো ছাড়া ঘরে থাকতে ভালো লাগে না।
 
---
 
## 🧩 Class
 
### Definition
 
`class` হলো HTML element এর একটা **গ্রুপের নাম**। একই নাম অনেক element কে দেওয়া যায়, তাই একবার স্টাইল লিখলেই সবগুলোতে কাজ করে।
 
**উদাহরণ:** স্কুলে "Class 10" এ অনেক ছাত্র থাকে। সবাই একই ক্লাসের, কিন্তু আলাদা মানুষ। HTML এ class ঠিক এরকম।
 
### কোথায় ব্যবহার হয়?
 
| ব্যবহার | উদাহরণ |
|---|---|
| একই স্টাইল অনেক জায়গায় | `.card`, `.btn`, `.menu-item` |
| CSS Framework | Bootstrap: `class="btn btn-primary"` |
| Tailwind CSS | `class="bg-blue-500 text-white p-4"` |
| React | `className="card"` (এখানে `class` না, `className` লিখতে হয়) |
| JavaScript এ সব element ধরা | `document.querySelectorAll(".card")` |
 
> 💡 **Special:** Real project এর প্রায় ৯০% স্টাইল class দিয়েই লেখা হয়। তাই CSS শেখার সময় class কে সবচেয়ে বেশি সময় দাও।
 
### Syntax
 
- HTML এ লেখা হয়: `class="নাম"`
- CSS এ ধরা হয় dot (`.`) দিয়ে: `.নাম { }`
```html
<style>
  /* .highlight হলো class selector, শুরুতে dot (.) থাকে */
  .highlight {
    background-color: yellow; /* হলুদ background */
  }
</style>
 
<!-- class="highlight" থাকলেই স্টাইল কাজ করবে -->
<p class="highlight">এটা হাইলাইট হবে</p>
<p>এটা normal</p>
<p class="highlight">এটাও হাইলাইট হবে</p>
```
 
**Output:** প্রথম আর তৃতীয় লাইনের পেছনে হলুদ রং আসবে, মাঝেরটা আগের মতোই থাকবে।
 
### একই Class, আলাদা Tag
 
Class যেকোনো tag এ বসানো যায়। Tag আলাদা হলেও স্টাইল একই আসবে।
 
```html
<!-- তিনটা আলাদা tag, কিন্তু class একই, তাই তিনটাই হলুদ হবে -->
<h2 class="highlight">Heading</h2>
<span class="highlight">Span</span>
<div class="highlight">Div</div>
```
 
### একটা Element এ একাধিক Class
 
Space দিয়ে আলাদা করে অনেকগুলো class দেওয়া যায়। ছোট ছোট স্টাইল জোড়া লাগিয়ে বড় ডিজাইন বানানো হয়।
 
```html
<style>
  /* সব button এর common স্টাইল */
  .btn {
    padding: 10px 20px;     /* ভেতরের ফাঁকা জায়গা */
    border: none;           /* default border বাদ */
    border-radius: 6px;     /* কোণা একটু গোল */
    cursor: pointer;        /* mouse আনলে হাতের আঙুল */
  }
 
  /* শুধু সবুজ রঙের স্টাইল */
  .btn-green {
    background-color: green;
    color: white;
  }
 
  /* শুধু লাল রঙের স্টাইল */
  .btn-red {
    background-color: red;
    color: white;
  }
</style>
 
<!-- দুইটা class একসাথে: .btn (common) + .btn-green (রং) -->
<button class="btn btn-green">Save</button>
<button class="btn btn-red">Delete</button>
```
 
এখানে `.btn` সব বাটনের কমন স্টাইল, আর `.btn-green` / `.btn-red` শুধু রং ঠিক করছে।
 
### Real Life Example: Card
 
একটা ওয়েবসাইটে অনেকগুলো card থাকে। প্রতিটার জন্য আলাদা CSS না লিখে একটা class দিয়েই কাজ হয়।
 
```html
<style>
  .card {
    border: 1px solid #ddd;   /* হালকা ধূসর border */
    border-radius: 8px;       /* গোল কোণা */
    padding: 16px;            /* ভেতরে জায়গা */
    margin-bottom: 12px;      /* এক card থেকে আরেক card এর ফাঁক */
  }
</style>
 
<div class="card">Product 1</div>
<div class="card">Product 2</div>
<div class="card">Product 3</div>
```
 
### Tag + Class একসাথে
 
```css
/* শুধু class="note" যুক্ত <p> এ কাজ করবে, <div class="note"> এ না */
p.note {
  background: #fffbe6;
}
```
 
### Class এর নাম দেওয়ার নিয়ম
 
| ঠিক ✅ | ভুল ❌ |
|---|---|
| `.main-title` (hyphen দিয়ে) | `.main title` (space চলবে না) |
| `.card2` (সংখ্যা শেষে চলে) | `.2card` (সংখ্যা দিয়ে শুরু হয় না) |
| `.btn-primary` (কাজ বোঝায়) | `.red-text` (পরে রং বদলালে নামটা ভুল হয়ে যাবে) |
 
### Class নিয়ে সাধারণ ভুল
 
```html
<!-- ❌ ভুল: CSS এ dot (.) দিতে ভুলে গেছো -->
<style>
  highlight { background: yellow; }   /* এটা তো tag এর নাম মনে করছে, কাজ করবে না */
</style>
 
<!-- ✅ ঠিক -->
<style>
  .highlight { background: yellow; }
</style>
 
<!-- ❌ ভুল: HTML এ dot দিয়ে ফেলেছো -->
<p class=".highlight">...</p>
 
<!-- ✅ ঠিক: HTML এ dot লাগে না -->
<p class="highlight">...</p>
```
 
---
 
## 🪪 ID
 
### Definition
 
`id` হলো একটা element এর **নিজস্ব, unique নাম**। পুরো পেজে একটা id শুধু **একবারই** ব্যবহার করা যায়।
 
**উদাহরণ:** Class হলো "Class 10", আর id হলো তোমার **Roll Number**। Roll নম্বর সবার আলাদা, দুজনের এক হয় না।
 
### কোথায় ব্যবহার হয়?
 
| ব্যবহার | উদাহরণ |
|---|---|
| JavaScript এ একটা নির্দিষ্ট element ধরা | `document.getElementById("menu")` |
| Page এর ভেতরে jump link (anchor) | `<a href="#contact">Contact</a>` |
| Form এ label আর input জোড়া লাগানো | `<label for="email">` আর `<input id="email">` |
| একদম unique কোনো অংশ | `#header`, `#footer` |
 
### Syntax
 
- HTML এ লেখা হয়: `id="নাম"`
- CSS এ ধরা হয় hash (`#`) দিয়ে: `#নাম { }`
```html
<style>
  /* #main-title হলো id selector, শুরুতে hash (#) থাকে */
  #main-title {
    color: crimson;        /* গাঢ় লাল */
    text-align: center;    /* মাঝখানে */
  }
</style>
 
<!-- পুরো পেজে এই id আর কোথাও থাকবে না -->
<h1 id="main-title">Welcome to My Site</h1>
```
 
### Anchor Link Example
 
ID এর সবচেয়ে মজার ব্যবহার হলো পেজের ভেতরে "লাফ" দেওয়া।
 
```html
<!-- এই link এ click করলে নিচের #contact section এ scroll করে চলে যাবে -->
<a href="#contact">Contact এ যাও</a>
 
<div style="height: 1000px;">অনেক লম্বা content...</div>
 
<!-- id="contact" এর জায়গায় এসে থামবে -->
<h2 id="contact">Contact Us</h2>
```
 
### Form এ ID এর ব্যবহার
 
```html
<!-- label এর for আর input এর id এক হলে, label এ click করলেই input এ cursor যায় -->
<label for="email">Email:</label>
<input type="email" id="email">
```
 
### Class vs ID
 
| বিষয় | Class | ID |
|---|---|---|
| Symbol | `.` (dot) | `#` (hash) |
| কতবার ব্যবহার | যতবার ইচ্ছা | পেজে মাত্র একবার |
| এক element এ | একাধিক দেওয়া যায় | একটাই |
| কখন ব্যবহার | Reusable স্টাইল | Unique element, anchor, JS |
| Specificity (জোর) | মাঝারি | অনেক বেশি |
 
### ID এর জোর বেশি কেন সমস্যা?
 
```html
<style>
  #title { color: red; }      /* ID এর জোর বেশি */
  .title { color: blue; }     /* class এর জোর কম */
</style>
 
<h1 id="title" class="title">Hello</h1>
<!-- Output: লাল। নিচে class লিখলেও ID জিতে যায় -->
```
 
> 💡 **Tip:** স্টাইলের জন্য সাধারণত class ব্যবহার করাই ভালো। ID এর জোর বেশি বলে পরে স্টাইল override করা কঠিন হয়ে যায়। ID রাখো JavaScript আর anchor link এর জন্য।
 
### ID নিয়ে সাধারণ ভুল
 
```html
<!-- ❌ ভুল: একই id দুইবার, browser কনফিউজ হয়ে যায় -->
<p id="note">প্রথম</p>
<p id="note">দ্বিতীয়</p>
 
<!-- ✅ ঠিক: অনেকগুলোতে একই স্টাইল চাইলে class ব্যবহার করো -->
<p class="note">প্রথম</p>
<p class="note">দ্বিতীয়</p>
```
 
---
 
## ✍️ Font
 
### Definition
 
Font properties দিয়ে লেখার **ধরন, আকার, মোটা-পাতলা ভাব আর স্টাইল** ঠিক করা হয়।
 
**উদাহরণ:** Font হলো লেখার পোশাক। একই মানুষ ফরমাল পোশাকে একরকম, পার্টির পোশাকে আরেকরকম দেখায়। একই লেখা আলাদা font এ আলাদা personality পায়।
 
### কোথায় ব্যবহার হয়?
 
| জায়গা | কেন গুরুত্বপূর্ণ |
|---|---|
| Body text | পড়তে আরাম লাগা দরকার |
| Heading | সাইটের personality বোঝায় |
| Button | স্পষ্ট ও আকর্ষণীয় হতে হয় |
| Logo / Banner | Brand এর পরিচয় |
| Code block | সমান চওড়া `monospace` font |
 
একটা সাইটের "চেহারা" বা mood অনেকটাই font এর উপর নির্ভর করে।
 
### font-family
 
কোন ধরনের অক্ষর ব্যবহার হবে সেটা ঠিক করে।
 
```css
body {
  /* প্রথমটা না পেলে পরেরটা, তারপর পরেরটা (fallback) */
  font-family: "Poppins", Arial, sans-serif;
}
```
 
নাম একাধিক শব্দের হলে quotes (`" "`) দিতে হয়। শেষে সবসময় একটা generic family দিতে হয়:
 
| Generic | অর্থ | Example |
|---|---|---|
| `serif` | অক্ষরের কোণায় ছোট "পা" থাকে, ঐতিহ্যবাহী | Times New Roman |
| `sans-serif` | পা নেই, আধুনিক আর পরিষ্কার | Arial, Poppins |
| `monospace` | সব অক্ষর সমান চওড়া, code এর জন্য | Courier New |
| `cursive` | হাতে লেখার মতো | Comic Sans |
 
### font-size
 
```css
p  { font-size: 18px; }      /* fixed size */
h1 { font-size: 2.5rem; }    /* relative size (16px x 2.5 = 40px) */
```
 
> 💡 পড়ার লেখার জন্য সাধারণত `16px` থেকে `18px` ভালো। এর চেয়ে ছোট হলে mobile এ পড়তে কষ্ট হয়।
 
### font-weight
 
```css
p    { font-weight: normal; }  /* 400, স্বাভাবিক */
h1   { font-weight: bold; }    /* 700, মোটা */
span { font-weight: 600; }     /* 100 থেকে 900 পর্যন্ত দেওয়া যায় */
```
 
| Value | অর্থ |
|---|---|
| `300` | পাতলা (light) |
| `400` / `normal` | স্বাভাবিক |
| `600` | আধা-মোটা (semi-bold) |
| `700` / `bold` | মোটা |
| `900` | অনেক মোটা (black) |
 
### font-style
 
```css
em { font-style: italic; }   /* বাঁকা লেখা */
p  { font-style: normal; }   /* সোজা লেখা */
```
 
### line-height
 
দুই লাইনের মাঝের দূরত্ব। পড়ার আরামের জন্য খুব গুরুত্বপূর্ণ।
 
```css
p {
  line-height: 1.6;   /* font-size এর 1.6 গুণ, কোনো unit লাগে না */
}
```
 
> 💡 Body text এর জন্য `1.5` থেকে `1.8` সবচেয়ে আরামদায়ক।
 
### letter-spacing আর text-transform
 
```css
h1 {
  letter-spacing: 2px;        /* অক্ষরের মাঝে ফাঁক */
  text-transform: uppercase;  /* সব বড় হাতের অক্ষর */
}
```
 
### Font Shorthand
 
একলাইনে সব লেখা যায়।
 
```css
p {
  /* style weight size/line-height family */
  font: italic bold 18px/1.6 Arial, sans-serif;
}
```
 
> ⚠️ Shorthand এ `font-size` আর `font-family` **অবশ্যই** দিতে হয়, না হলে পুরো line কাজ করবে না।
 
### Google Fonts ব্যবহার
 
ইন্টারনেটে হাজার হাজার সুন্দর font বিনামূল্যে পাওয়া যায়। সবচেয়ে জনপ্রিয় উৎস হলো **Google Fonts**।
 
**Step 1:** `fonts.google.com` এ গিয়ে font বেছে নাও, তারপর link টা copy করে HTML এর `<head>` এ বসাও।
 
```html
<!-- Google এর server এর সাথে আগে থেকে connection তৈরি (দ্রুত load হয়) -->
<link rel="preconnect" href="https://fonts.googleapis.com">
 
<!-- Poppins font এর 400 আর 600 weight load করা -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
```
 
**Step 2:** CSS এ ব্যবহার করো।
 
```css
body {
  font-family: "Poppins", sans-serif;   /* fallback সহ */
}
```
 
### বাংলা Font
 
বাংলা সাইটের জন্য Google Fonts এ ভালো কিছু font আছে:
 
```css
body {
  /* Hind Siliguri, Noto Sans Bengali, Baloo Da 2 জনপ্রিয় বাংলা font */
  font-family: "Hind Siliguri", "Noto Sans Bengali", sans-serif;
}
```
 
### Real Life Example: সুন্দর Article
 
```html
<style>
  .article {
    font-family: "Poppins", Arial, sans-serif;  /* পরিষ্কার font */
    font-size: 17px;                            /* আরামদায়ক size */
    line-height: 1.7;                           /* লাইনের মাঝে পর্যাপ্ত ফাঁক */
    color: #333;                                /* কালো না, হালকা ধূসর (চোখ কম ক্লান্ত হয়) */
    max-width: 650px;                           /* লাইন বেশি লম্বা হলে পড়া কঠিন */
    margin: 0 auto;                             /* মাঝখানে */
  }
  .article h1 {
    font-size: 2.2rem;
    font-weight: 700;
    margin-bottom: 10px;
  }
  .article .date {
    font-size: 0.85rem;       /* ছোট */
    color: #888;              /* ম্লান রং */
    font-style: italic;
  }
</style>
 
<div class="article">
  <h1>আমার প্রথম Blog</h1>
  <p class="date">১ জানুয়ারি, ২০২৬</p>
  <p>এখানে আমার লেখা শুরু হলো...</p>
</div>
```
 
### Font এর ভালো অভ্যাস
 
| অভ্যাস | কারণ |
|---|---|
| সাইটে ২টার বেশি font ব্যবহার না করা | বেশি font এ সাইট ধীর আর এলোমেলো হয় |
| সবসময় fallback font দেওয়া | Font load না হলেও সাইট দেখতে ঠিক থাকে |
| Heading এ একটা, body তে আরেকটা font | সুন্দর contrast আসে |
| `rem` unit ব্যবহার করা | User browser এ font বড় করলে সাইটও মানিয়ে নেয় |
| প্রয়োজনীয় weight শুধু load করা | বেশি weight load করলে সাইট ধীর হয় |
 
---
 
## 💡 CSS শেখার Tips
 
| Tip | কেন কাজে লাগে |
|---|---|
| **F12 চাপো, Inspect করো** | যেকোনো সাইটের CSS দেখতে পারবে, এটাই সবচেয়ে বড় শিক্ষক |
| **একটা একটা করে শেখো** | আজ শুধু Class, কাল ID, পরশু Font। একসাথে সব না |
| **প্রতিদিন কিছু বানাও** | পড়ে শেখা যায় ২০%, হাতে বানিয়ে শেখা যায় ৮০% |
| **ভুল করতে ভয় পেও না** | CSS এর ভুলে কিছু ভাঙে না, শুধু দেখতে একটু উল্টাপাল্টা হয় |
| **Comment লেখো** | এক সপ্তাহ পর নিজের কোডই নিজে বুঝবে না, comment তখন বাঁচায় |
| **ছোট থেকে বড় করো** | আগে একটা button বানাও, তারপর card, তারপর পুরো page |
| **সুন্দর সাইট কপি করে শেখো** | দেখো কীভাবে করেছে, নিজে আবার লেখো। হুবহু copy-paste না |
| **Browser এ বারবার Refresh দাও** | প্রতিটা বদলের ফলাফল সাথে সাথে দেখলে শেখা দ্রুত হয় |
| **Cheat sheet হাতের কাছে রাখো** | সব property মুখস্থ করতে হয় না, কোথায় খুঁজবে সেটা জানলেই হয় |
| **Figma দেখে design কোডে নামাও** | Job এ এটাই প্রতিদিনের কাজ |
 
### Debug করার ছোট কৌশল
 
CSS কাজ না করলে এই দুইটা কৌশল সবচেয়ে কাজে লাগে:
 
```css
/* কৌশল ১: element টা আসলে কোথায় আছে দেখতে border দাও */
.box {
  border: 2px solid red;   /* সাময়িক, দেখা শেষে মুছে ফেলো */
}
 
/* কৌশল ২: background রং দিয়ে জায়গা বোঝা */
.container {
  background: rgba(255, 0, 0, 0.2);
}
```
 
### সবচেয়ে কাজের ৩টা প্রশ্ন
 
CSS কাজ না করলে নিজেকে এই তিনটা প্রশ্ন করো:
 
- Class বা ID এর **বানান** ঠিক আছে তো? (`.card` লিখে HTML এ `class="cards"` দিলে হবে না)
- **Dot (.) বা Hash (#)** দিতে ভুলিনি তো?
- আরেকটা বেশি জোরের selector আমার স্টাইল **override** করছে না তো? (Inspect এ দেখো)
---
 
## 😄 CSS নিয়ে কিছু মজা
 
> **প্রশ্ন:** CSS এ কেন কেউ নিজের ছায়া ধরতে পারে না?
> **উত্তর:** কারণ `box-shadow` তো শুধু দেখায়, ধরা যায় না! 😂
 
> **প্রশ্ন:** Developer রা কেন মাঝখানে (center) কিছু রাখতে ভয় পায়?
> **উত্তর:** কারণ `margin: 0 auto` ভুলে গেলে সারাদিন সেটা নিয়েই বসে থাকতে হয়! 🥲
 
> একজন Developer বলল: "আমি তো বললাম `float: left`, তাও সে ডানে কেন যাচ্ছে?"
> আরেকজন বলল: "ভাই, `clear: both` দাও, আর বাকিটা ভাগ্যের উপর ছেড়ে দাও।" 🙏
 
> **সত্যি ঘটনা:** প্রতিটা Developer এর জীবনে একটা দিন আসে যেদিন সে একটা `div` মাঝখানে আনতে ৩০ মিনিট লাগিয়ে ফেলে। তুমি একা না। 😅
 
---
 
## 🎯 Practice Tasks
 
**Class:**
 
- তিনটা `.card` বানাও, প্রতিটাতে আলাদা product এর নাম থাকবে। সবগুলোর স্টাইল একটা class থেকে আসবে।
- `.btn` নামে একটা base class বানাও, তারপর `.btn-blue`, `.btn-green`, `.btn-red` দিয়ে তিনটা রঙের button বানাও।
**ID:**
 
- একটা পেজে তিনটা section বানাও (`#home`, `#about`, `#contact`)। উপরে একটা menu দাও যেখানে click করলে সেই section এ চলে যাবে।
- একটা form এ `label` আর `input` কে `for` আর `id` দিয়ে জোড়া লাগাও।
**Font:**
 
- Google Fonts থেকে দুইটা font বেছে নাও। একটা heading এর জন্য, আরেকটা paragraph এর জন্য।
- নিজের একটা ছোট Blog post এর পেজ বানাও যেখানে `line-height`, `font-size` আর `font-weight` ঠিকঠাক ব্যবহার করা থাকবে।
**Challenge 🏆:**
 
- নিজের একটা **Introduction Card** বানাও। তাতে নাম (heading), পেশা (ছোট লেখা), আর একটা ছোট bio থাকবে। Class দিয়ে স্টাইল করো, আর একটা সুন্দর Google Font ব্যবহার করো।
---
 
## 🔥 Motivation
 
> **"প্রতিটা Expert একসময় Beginner ছিল।"**
 
তুমি যখন প্রথম `color: red;` লিখে দেখলে লেখাটা সত্যিই লাল হয়ে গেছে, সেই অনুভূতিটা মনে আছে? ওই মুহূর্তটাই সবকিছুর শুরু ছিল। 🌱
 
আজ তুমি Class, ID, Font শিখছো। এগুলো ছোট জিনিস মনে হতে পারে, কিন্তু Facebook, YouTube, Daraz, প্রতিটা সাইটের পেছনে এই জিনিসগুলোই আছে। বড় বড় সাইট আসলে ছোট ছোট নিয়মের বিশাল সমষ্টি।
 
**মনে রেখো:**
 
- 🐢 **ধীরে চলো, কিন্তু থামো না।** প্রতিদিন ৩০ মিনিট, এক বছরে ১৮০ ঘণ্টা। এতেই তুমি দারুণ Developer হয়ে যাবে।
- 🐛 **Error মানে হার না।** Error মানে browser তোমাকে বলছে "এখানটা একটু ঠিক করো।" সে তোমার বন্ধু।
- 🧱 **একটা একটা করে ইট গাঁথো।** আজ Class, কাল Flexbox, পরশু Grid। একদিন দেখবে পুরো বাড়ি দাঁড়িয়ে গেছে।
- 🚀 **তুলনা করো শুধু গতকালের নিজের সাথে।** আজ যদি গতকালের চেয়ে একটুও বেশি জানো, তুমি জিতে গেছো।
একদিন তুমি নিজের বানানো সাইটে বসে কাউকে বলবে, "এটা আমি বানিয়েছি।" সেই দিনটার জন্য আজকের এই ছোট ছোট চেষ্টাগুলোই সবচেয়ে বড় বিনিয়োগ। 
 
---
