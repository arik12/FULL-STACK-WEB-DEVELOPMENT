

## CSS (Cascading Style Sheets)

Imagine you’re building a house.The walls, doors, and windows create the structure this is like HTML.But when you paint the walls, add lights, and decorate the rooms, the house becomes beautiful this is what CSS does for a web page.

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

Once upon a time, there was a simple HTML page living in a browser. It had all the content—headings, paragraphs, and images—but it looked plain and boring .  

One day, CSS came to help! 
CSS said, *"Let me style you and make you beautiful!"*  

From that day on, the browser started reading the CSS rules and transformed the plain HTML into a colorful, well-designed webpage 🌈.  


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

# External CSS is used to apply styles to multiple HTML pages using a separate CSS file.

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
## Internal CSS is used to apply styles within a single HTML page using the <style> tag.

### 3️⃣ Inline CSS

```html

<h1 style="color: red;">Hello World</h1>

```

## Inline CSS is used to apply style directly to a specific HTML element.



