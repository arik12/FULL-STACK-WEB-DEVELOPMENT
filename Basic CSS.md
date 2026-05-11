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





