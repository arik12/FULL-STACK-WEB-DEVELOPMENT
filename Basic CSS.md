

## CSS (Cascading Style Sheets)

Imagine you are building a house.The walls, doors, and windows create the structure this is like HTML.But when you paint the walls, add lights, and decorate the rooms, the house becomes beautiful this is what CSS does for a web page.

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

h1 {
  color: blue;
}


```

Note: External CSS is used to apply styles to multiple HTML pages using a separate CSS file.

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
Note: Internal CSS is used to apply styles within a single HTML page using the <style> tag.

### 3️⃣ Inline CSS

```html

<h1 style="color: red;">Hello World</h1>

```

## Note: Inline CSS is used to apply style directly to a specific HTML element.



