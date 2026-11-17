
<div align="center">

# HTML (Hyper Text Markup Language)



</div>

# Introduction 

Imagine you are building a house.  
The walls, doors, windows, and roof create the main structure of the house.  
In the same way, HTML creates the structure of a website.

Without structure, a house cannot stand properly.  
Similarly, without HTML, a webpage cannot exist.

A long time ago, websites were very simple. People needed a way to connect documents and share information over the internet. Then HTML was created.

HTML is the first step of web development.  
It helps developers create webpages using different tags and elements.

Today, almost every website in the world uses HTML.

---

# What is HTML?

HTML stands for:

## Hyper Text Markup Language

### Breakdown:
- **HyperText** = Text connected with links
- **Markup Language** = A language that uses tags to structure content

HTML is used to create webpages and display content on browsers.

Using HTML, we can create:
- Headings
- Paragraphs
- Images
- Links
- Tables
- Forms
- Videos and more

HTML tells the browser how the content should appear on the screen.

---

# History of HTML

HTML was invented in 1991 by **Tim Berners-Lee**, a British computer scientist.  
He created HTML while working at **CERN (European Organization for Nuclear Research)** in Switzerland.

The main goal of HTML was to make it easier for scientists and researchers to share documents and information through the internet.

At that time, there was no proper system for connecting documents online. Tim Berners-Lee introduced HTML along with the World Wide Web (WWW), which changed the way people access and share information globally.HTML has improved over time with many updated versions. Today, HTML5 is the latest and most powerful version used for modern web development.



---

# Evolution of HTML

| Version | Year | Features |
|----------|------|-----------|
| HTML 1.0 | 1991 | Basic webpage structure |
| HTML 2.0 | 1995 | Standard version |
| HTML 3.2 | 1997 | Added tables and scripting |
| HTML 4.01 | 1999 | Improved webpage structure |
| XHTML | 2000 | Stricter coding rules |
| HTML5 | 2014 | Modern multimedia support |

Today, HTML5 is the latest and most widely used version of HTML.

---

# Why HTML is Important?

HTML is important because:

1. It creates the structure of webpages
2. It is easy to learn
3. All browsers support HTML
4. It works with CSS and JavaScript
5. It is the foundation of web development

Without HTML:
- Websites cannot exist
- Webpages cannot be created
- Online forms and applications would not work

---


# Basic Structure of HTML

```html

<!DOCTYPE html>  <!-- এটি browser কে বলে যে এটি একটি HTML5 document -->
<html>           <!-- পুরো HTML page এর শুরু এখান থেকে -->
<head>
    <title>My First Webpage</title>  <!-- Browser এর tab-এ যে নাম দেখায় -->
</head>
<body>           <!-- এখানে যা লেখা হবে, তা webpage-এ দেখা যাবে -->
    <h1>Welcome to HTML</h1>
    <p>This is my first webpage.</p>
</body>
</html>          <!-- HTML document এর শেষ -->

```

###  মনে রাখার বিষয় (Key Points):
 
- **`<!DOCTYPE html>`** — প্রতিটি HTML document এর **সবার উপরে** এটি লিখতে হয়। এটি browser কে জানায় যে page টি কোন version এর HTML দিয়ে তৈরি। এটি **case sensitive নয়** — মানে `<!doctype html>` লিখলেও কাজ করবে।
- **`<html>` ... `</html>`** — পুরো HTML document এই দুটি tag এর ভেতরে থাকে। এটি HTML এর **root element**।
- **`<head>` ... `</head>`** — এই অংশে থাকে page এর **meta information**, যেমন title, CSS link ইত্যাদি — যা webpage-এ সরাসরি দেখা যায় না।
- **`<body>` ... `</body>`** — Webpage এ যা **দেখা যায়** (text, image, button ইত্যাদি) সব কিছু এই tag এর ভেতরে লিখতে হয়।
---
 
> 💡 **Tips:** HTML structure টা মনে রাখার সহজ উপায় — একটা বইয়ের মতো ভাবো।  
> `<!DOCTYPE>` = বইয়ের ধরন, `<head>` = বইয়ের কভার/তথ্য, `<body>` = বইয়ের ভেতরের পাতা।
 
---



## 2. HTML Tags — Webpage এর আসল নায়ক!
 
> **HTML Tag কী?**
> HTML Tag হলো browser কে দেওয়া একটি **নির্দেশনা** — যা বলে দেয় কোন content কীভাবে দেখাতে হবে। Tag ছাড়া browser বুঝতেই পারবে না কোনটা heading, কোনটা link, কোনটা ছবি। মোটকথা, Tag হলো HTML এর **প্রাণ** এগুলো ছাড়া webpage তৈরিই সম্ভব না।
>
> প্রতিটি tag `<` এবং `>` চিহ্ন দিয়ে ঘেরা থাকে। বেশিরভাগ tag জোড়ায় জোড়ায় আসে —
>
> ➡️ **Opening tag** → `<tag>` &nbsp;&nbsp;&nbsp; এখান থেকে শুরু হয়, browser পড়া শুরু করে  
> ➡️ **Closing tag** → `</tag>` &nbsp;&nbsp; এখানে শেষ হয়, সামনে `/` থাকে — এটাই পার্থক্য  
> ➡️ **Content** → দুই tag এর ঠিক মাঝখানে যা লেখা হয়, সেটাই webpage এ দেখা যায়
 
---
 
### 📝 Heading Tags — শিরোনামের জন্য
 
```html

<h1>এটি সবচেয়ে বড় Heading</h1>   <!-- Font Size: 32px (Default) -->
<h2>এটি ২য় বড় Heading</h2>        <!-- Font Size: 24px -->
<h3>এটি ৩য় বড় Heading</h3>        <!-- Font Size: 18.72px -->
<h4>এটি ৪র্থ Heading</h4>           <!-- Font Size: 16px -->
<h5>এটি ৫ম Heading</h5>             <!-- Font Size: 13.28px -->
<h6>এটি সবচেয়ে ছোট Heading</h6>   <!-- Font Size: 10.72px -->


```
> 💡 `<h1>` থেকে `<h6>` — মোট **6টি** heading tag আছে। বড় থেকে ছোট হয়।
 
---
 
### 📄 Paragraph & Text Tags — লেখার জন্য
 
**`<p>`** → সাধারণ paragraph লেখার জন্য। প্রতিটি `<p>` নতুন লাইনে শুরু হয়।
```html
<p>এটি একটি paragraph।</p>
```
 
**`<br>`** → Line break — এক লাইন থেকে পরের লাইনে যেতে। *(closing tag নেই)*
```html
প্রথম লাইন<br>দ্বিতীয় লাইন
```
 
**`<hr>`** → Horizontal rule — পেজে একটি আড়াআড়ি রেখা টানে। *(closing tag নেই)*
```html
<hr>
```
 
**`<strong>`** → লেখা **Bold** করে এবং গুরুত্বপূর্ণ বোঝায়।
```html
<strong>এই লেখা Bold ও গুরুত্বপূর্ণ</strong>
```
 
**`<b>`** → লেখা **Bold** করে, কিন্তু শুধু দেখতে — কোনো বিশেষ মানে নেই।
```html
<b>এই লেখাও Bold</b>
```
 
**`<em>`** → লেখা *Italic* করে এবং জোর দেওয়া বোঝায়।
```html
<em>এই লেখায় জোর দেওয়া হচ্ছে</em>
```
 
**`<i>`** → লেখা *Italic* করে, কিন্তু শুধু style এর জন্য।
```html
<i>এই লেখাও Italic</i>
```
 
**`<u>`** → লেখার নিচে Underline দেয়।
```html
<u>এই লেখায় দাগ আছে</u>
```
 
**`<mark>`** → লেখা হলুদ রঙে Highlight করে।
```html
<mark>এই অংশটি highlighted</mark>
```
 
**`<small>`** → লেখা একটু ছোট করে দেখায়।
```html
<small>এটি ছোট লেখা</small>
```
 
**`<del>`** → লেখার মাঝ দিয়ে কাটা দাগ দেয় — মানে সেটি বাদ দেওয়া হয়েছে।
```html
<del>পুরনো দাম: ৫০০ টাকা</del>
```
 
**`<sup>`** → লেখাকে উপরে ছোট করে দেখায়। যেমন: x²
```html
x<sup>2</sup>
```
 
**`<sub>`** → লেখাকে নিচে ছোট করে দেখায়। যেমন: H₂O
```html
H<sub>2</sub>O
```
 
---
 
### 🔗 Link Tag — লিংকের জন্য
 
```html
<a href="https://www.google.com">Google এ যাও</a>           <!-- সাধারণ link -->
<a href="https://www.google.com" target="_blank">নতুন tab এ খুলবে</a>  <!-- নতুন tab -->
```
> 💡 `href` = কোথায় যাবে। `target="_blank"` = নতুন tab এ খুলবে।
 
---
 
### 🖼️ Image Tag — ছবির জন্য
 
```html
<img src="photo.jpg" alt="একটি সুন্দর ছবি">          <!-- Local ছবি -->
<img src="https://example.com/img.png" alt="ছবি" width="300" height="200"> <!-- Online ছবি -->
```
> 💡 `src` = ছবির ঠিকানা। `alt` = ছবি না আসলে কী দেখাবে। `<img>` এর **closing tag নেই**।
 
---
 

### Semantic Tags — অর্থবহ ট্যাগ

HTML-এর এমন কিছু ট্যাগ, যেগুলো দিয়ে ওয়েবপেজের বিভিন্ন অংশের অর্থ ও কাজ বোঝানো হয়। যেমন: `header`, `footer`, `nav` ইত্যাদি। এসব ট্যাগ ব্যবহারের ফলে ব্রাউজার ও ডেভেলপার উভয়েই সহজে বুঝতে পারে ওয়েবপেজের কোন অংশটি কী কাজ করছে। এতে কোড পড়া, বোঝা এবং মেইনটেইন করা সহজ হয়।

---

### Types of HTML Elements

#### 1. Non-Semantic Elements

যেসব HTML ট্যাগ থেকে কনটেন্টের ধরন বা উদ্দেশ্য সম্পর্কে নির্দিষ্ট কোনো ধারণা পাওয়া যায় না, সেগুলোকে Non-Semantic Elements বলে।

**Examples:**

- `<div>` — Block-level content group করতে ব্যবহৃত হয়।
- `<span>` — Inline content group করতে ব্যবহৃত হয়।

#### 2. Semantic Elements

যেসব HTML ট্যাগ নিজের নামের মাধ্যমেই কনটেন্টের ধরন বা উদ্দেশ্য সম্পর্কে ধারণা দেয়, সেগুলোকে Semantic Elements বলে।

**Examples:**

- `<header>` — ওয়েবপেজের উপরের অংশ।
- `<nav>` — Navigation menu।
- `<main>` — পেজের মূল content।
- `<section>` — নির্দিষ্ট content section।
- `<article>` — স্বতন্ত্র লেখা বা post।
- `<aside>` — Sidebar বা অতিরিক্ত information।
- `<footer>` — ওয়েবপেজের নিচের অংশ।
- `<img>` — Image প্রদর্শন করে।
- `<table>` — Table আকারে data প্রদর্শন করে।

---

### Example

```html
<!-- উপরের অংশ -->
<header>Website Header</header>

<!-- menu -->
<nav>Navigation Menu</nav>

<main>
  <!-- একটা নির্দিষ্ট অংশ -->
  <section>
    <h2>About Us</h2>
    <p>Section Content</p>
  </section>

  <!-- স্বতন্ত্র post -->
  <article>
    <h2>Blog Post</h2>
    <p>Article Content</p>
  </article>

  <!-- পাশের অংশ -->
  <aside>Sidebar Content</aside>
</main>

<!-- নিচের অংশ -->
<footer>Website Footer</footer>

<!-- Non-semantic: শুধু group করার জন্য -->
<div>Normal Container</div>
<span>Inline Content</span>
```

---

### Remember

- Semantic Elements কনটেন্টের অর্থ ও উদ্দেশ্য প্রকাশ করে।
- Non-Semantic Elements কনটেন্টকে group বা organize করতে সাহায্য করে।
- Semantic HTML ব্যবহার করলে কোড আরও readable, maintainable এবং accessible হয়।

> 💡 **Tips:**
> - Tag এর নাম পড়েই যদি content বোঝা যায়, তাহলে ওটা semantic।
> - `<div>` আর `<span>` একদম বাদ দিতে হবে না। যেখানে কোনো semantic tag মানায় না, সেখানে এগুলো ব্যবহার করো।
> - `<main>` একটা page এ শুধু **একটাই** থাকবে।
> - Semantic tag use করলে **SEO** আর **accessibility** দুটোই ভালো হয়।
> - `<img>` এ সবসময় `alt` দিও, এতে screen reader ছবির মানে বুঝতে পারে।

 
---
 
###  Self-Closing Tags হলো এমন HTML ট্যাগ যেগুলোর আলাদা closing tag লাগে না।
 
| Tag | কাজ |
|-----|-----|
| `<br>` | Line break |
| `<hr>` | Horizontal line |
| `<img>` | Image |
| `<input>` | Input field |
| `<meta>` | Meta information |
| `<link>` | CSS file যুক্ত করা |
 
---
 
### Quick Notes
 
**১. Tags সবসময় lowercase লেখো**
HTML tags গুলো **case sensitive নয়** — মানে `<P>` আর `<p>` দুটোই কাজ করবে। কিন্তু সবসময় **lowercase** (`<p>`, `<h1>`, `<div>`) লেখাটাই সঠিক এবং professional। বড় হাতে লিখলে browser বুঝবে, কিন্তু দেখতে খারাপ লাগে এবং এটা industry standard না।
 
**২. Opening tag খুললে Closing tag বন্ধ করো**
যেকোনো tag খুললে সাথে সাথে closing tag লেখার অভ্যাস করো। যেমন `<p>` লিখলেই নিচে `</p>` লিখে রাখো, তারপর মাঝে content বসাও। এই অভ্যাস না থাকলে বড় project এ অনেক ভুল হয়।
 
**৩. Self-closing tags এর closing tag লাগে না**
`<br>`, `<hr>`, `<img>`, `<input>` — এই tags গুলো **একা একাই সম্পূর্ণ**। এগুলোতে কোনো content বসে না, তাই closing tag দেওয়ার দরকার নেই। ভুলেও `</br>` বা `</img>` লিখো না।
 
**৪. Tags nest করার সময় সঠিক order মেনে চলো**
একটার ভেতর আরেকটা tag দেওয়াকে **nesting** বলে। কিন্তু সঠিক order ছাড়া ভুল হয়।
```html
✅ সঠিক:   <b><i>লেখা</i></b>
❌ ভুল:    <b><i>লেখা</b></i>
```
যেটা আগে খোলা হয়েছে, সেটা পরে বন্ধ হবে — এই নিয়ম সবসময় মেনে চলো।
 
**৫. `<div>` আর `<span>` এর পার্থক্য মনে রাখো**
- `<div>` → **Block element** — পুরো লাইন জুড়ে থাকে, নতুন লাইনে শুরু হয়।
- `<span>` → **Inline element** — লেখার মাঝে থাকে, লাইন ভাঙে না।

---


 
### HTML Styles — এলিমেন্টকে সাজানোর জন্য
 
`style` attribute দিয়ে কোনো ট্যাগের ভিতরেই সরাসরি color, size, font ইত্যাদি বসিয়ে দেওয়া যায়। মানে আলাদা কোনো ফাইল লাগে না, সাথে সাথেই সাজিয়ে ফেলা যায়।
 
```html
<!-- এখানে style দিয়ে সরাসরি রং আর সাইজ দিয়ে দিলাম -->
<p style="color: blue; font-size: 18px;">This is a styled paragraph.</p>
<!-- color: blue -> লেখা নীল রঙের হয়ে গেল -->
<!-- font-size: 18px -> লেখার সাইজ একটু বড় হলো -->
```
 
---
 
### HTML Comments — নিজের নোট রাখার জন্য
 
Comment ব্রাউজারে দেখায় না, শুধু কোডের ভিতরে থাকে। নিজেকে মনে করিয়ে দেওয়ার জন্য বা টিমের অন্যদের বোঝানোর জন্য লেখা হয়।
 
```html
<!-- এটা একটা কমেন্ট, ব্রাউজার এটা দেখাবে না -->
<p>This text is visible.</p>
 
<!-- TODO: এখানে পরে আরেকটা প্যারাগ্রাফ যুক্ত করতে হবে -->
```
 
---
 
### Background Color — পেছনের রং দেওয়ার জন্য
 
`background-color` দিয়ে কোনো বক্স বা element এর পেছনের রং সেট করা হয়।
 
```html
<!-- div টার পেছনের রং হালকা সবুজ করে দিলাম -->
<div style="background-color: lightgreen;">
  Hello World
</div>
```
 
---
 
### Text Color — লেখার রং দেওয়ার জন্য
 
`color` দিয়ে লেখার রং বদলানো হয়। সবচেয়ে বেশি ব্যবহৃত একটা প্রোপার্টি এটা।
 
```html
<!-- লেখার রং লাল করে দিলাম -->
<p style="color: red;">This text is red colored.</p>
```
 
---
 
### Border Color — বর্ডারের রং দেওয়ার জন্য
 
`border-color` দিয়ে বর্ডারের রং সেট করা হয়। কিন্তু আগে বর্ডার (width + style) দিতে হবে, নাহলে কোনো বর্ডারই দেখাবে না।
 
```html
<!-- বর্ডার দিলাম 2px, সলিড লাইন, রং নীল -->
<p style="border: 2px solid; border-color: blue;">
  This paragraph has a blue border.
</p>
```
 
---
 
### `<blockquote>` — বড় কোনো উক্তি দেখানোর জন্য
 
যখন কোনো বড় উক্তি বা অন্য জায়গা থেকে কপি করা লেখা আলাদাভাবে দেখাতে চাও, তখন এটা ব্যবহার করো। ব্রাউজার এটাকে একটু ভেতরের দিকে সরিয়ে (indent) দেখায়, দেখলেই বোঝা যায় এটা আলাদা কিছু।
 
```html
<!-- বড় একটা কোটেশন আলাদা ব্লকের মতো দেখাচ্ছে -->
<blockquote>
  Stay hungry, stay foolish.
</blockquote>
```
 
---
 
### ❝ `<q>` — ছোট উক্তি দেখানোর জন্য
 
ছোট quote, এক লাইনের মধ্যেই বসে যায়। `blockquote` এর মতো আলাদা ব্লক বানায় না। আর মজার বিষয় হলো — ব্রাউজার নিজেই quotation mark (" ") যুক্ত করে দেয়, তোমাকে লিখতে হয় না।
 
```html
<!-- ব্রাউজার নিজেই quotation mark বসিয়ে দেবে -->
<p>He said <q>Practice makes perfect</q> in class.</p>
```
 
---
 
### `<abbr>` — সংক্ষিপ্ত শব্দ বোঝানোর জন্য
 
কোনো শব্দ শর্ট ফর্মে লেখা থাকলে (যেমন HTML, CSS) এবং সেটার ফুল ফর্ম মাউস হোভার করলে দেখাতে চাইলে এটা ব্যবহার করা হয়।
 
```html
<!-- মাউস hover করলে "HyperText Markup Language" দেখাবে -->
<abbr title="HyperText Markup Language">HTML</abbr>
```
 
---
 
###  `<address>` — যোগাযোগের ইনফো দেখানোর জন্য
 
কোনো লেখক বা প্রতিষ্ঠানের contact info (address, email, phone) দেখাতে এটা ব্যবহার হয়। ব্রাউজার এটাকে ডিফল্টভাবে italic করে দেখায়।
 
```html
<!-- লেখকের contact info দেখানো হচ্ছে -->
<address>
  Written by John Doe.<br>
  Visit us at: example.com<br>
  Dhaka, Bangladesh
</address>
```
 
---
 
### `<cite>` — বই/মুভি/আর্টিকেলের নাম বলার জন্য
 
কোনো বই, মুভি, গান বা আর্টিকেলের নাম রেফারেন্স হিসেবে লিখতে চাইলে এটা ব্যবহার করো। এটা সাধারণত italic দেখায়।
 
```html
<!-- বইয়ের নাম reference হিসেবে দেখানো হচ্ছে -->
<p><cite>The Alchemist</cite> is a novel by Paulo Coelho.</p>
```
 
---
 
### `<bdo>` — লেখার দিক বদলানোর জন্য
 
`bdo` মানে Bi-Directional Override। এটা দিয়ে লেখাকে normal left-to-right এর জায়গায় right-to-left করে দেখানো যায়।
 
```html
<!-- লেখা ডান থেকে বাম দিকে দেখাবে -->
<bdo dir="rtl">This text will be reversed!</bdo>
```
 
---

## HTML Table

### Table Basics — টেবিল বানানোর নিয়ম

`<table>` দিয়ে টেবিল শুরু হয়। `<tr>` মানে row, `<th>` মানে header cell, আর `<td>` মানে normal data cell।

```html
<!-- সবচেয়ে সহজ একটা টেবিল -->
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Arik</td>
    <td>24</td>
  </tr>
</table>
```

| Tag | কাজ |
|-----|-----|
| `<table>` | পুরো টেবিল |
| `<tr>` | একটা row |
| `<th>` | header cell (bold + center হয়) |
| `<td>` | data cell |
| `<caption>` | টেবিলের টাইটেল |

---

### Table Border — টেবিলের বর্ডার

`border` property দিয়ে টেবিল আর cell এর চারপাশে দাগ দেওয়া হয়। শুধু `table` এ দিলে বাইরের বক্সে বর্ডার আসে, ভেতরে পেতে চাইলে `th` আর `td` তেও দিতে হয়।

```html
<style>
  table, th, td {
    border: 1px solid black; /* 1px মোটা, solid লাইন, কালো রং */
  }
</style>

<table>
  <tr>
    <th>Name</th>
    <th>City</th>
  </tr>
  <tr>
    <td>Arik</td>
    <td>Dhaka</td>
  </tr>
</table>
```

---

### Border Collapse — ডবল বর্ডার ঠিক করা

ডিফল্টে প্রতিটা cell এর আলাদা বর্ডার থাকে, তাই ডবল দাগ দেখা যায়। `border-collapse: collapse` দিলে দাগগুলো এক হয়ে যায়।

```html
<style>
  table {
    border-collapse: collapse; /* ডবল বর্ডার মিশিয়ে একটা করে দিলাম */
  }
  th, td {
    border: 1px solid #333;
  }
</style>
```

**Extra:** বর্ডারের কোণা গোল করতে চাইলে `border-radius` লাগে, কিন্তু সেটা `border-collapse: separate` এর সাথে ভালো কাজ করে।

---

### Table Size — টেবিলের width আর height

`width` আর `height` দিয়ে টেবিলের সাইজ ঠিক করা হয়। `%` দিলে parent এর তুলনায় সাইজ হয়, `px` দিলে fixed হয়।

```html
<style>
  table {
    width: 100%;   /* পুরো জায়গা জুড়ে থাকবে */
  }
  th {
    height: 50px;  /* header এর উচ্চতা */
  }
  td:first-child {
    width: 30%;    /* প্রথম column টা 30% জায়গা নেবে */
  }
</style>
```

---

### Table Header — th এর স্টাইল

`<th>` ডিফল্টে bold আর center থাকে। CSS দিয়ে রং, alignment বদলানো যায়।

```html
<style>
  th {
    background-color: #4CAF50; /* সবুজ ব্যাকগ্রাউন্ড */
    color: white;              /* সাদা লেখা */
    text-align: left;          /* বাম দিকে লেখা */
  }
</style>

<table>
  <tr>
    <th>Product</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>Pen</td>
    <td>10 Tk</td>
  </tr>
</table>
```

**Column header vs Row header:** উপরের সারিতে `<th>` দিলে column header হয়। প্রতি row এর শুরুতে `<th>` দিলে row header হয়।

```html
<tr>
  <th>Monday</th>   <!-- row header -->
  <td>Math</td>
</tr>
```

---

### Table Padding — cell এর ভেতরের ফাঁকা জায়গা

`padding` দিয়ে লেখা আর বর্ডারের মাঝে ফাঁকা রাখা হয়। এটা না দিলে লেখা বর্ডারের সাথে লেগে থাকে।

```html
<style>
  th, td {
    padding: 12px;  /* চারদিকে 12px ফাঁকা */
  }
</style>
```

আলাদা আলাদা দিকে দিতে চাইলে:

```css
td {
  padding: 10px 20px;   /* উপর-নিচে 10px, ডান-বামে 20px */
}
```

**Extra:** দুইটা cell এর মাঝের দূরত্ব `border-spacing` দিয়ে ঠিক হয় (শুধু `separate` mode এ কাজ করে)।

```css
table {
  border-collapse: separate;
  border-spacing: 10px;
}
```

---

### Text Alignment — লেখা কোথায় থাকবে

```html
<style>
  td {
    text-align: center;     /* left, center, right */
    vertical-align: middle; /* top, middle, bottom */
  }
</style>
```

---

### Table Styling — Zebra Stripes আর Hover

একটা row পরপর আলাদা রং দিলে টেবিল পড়তে সুবিধা হয়। `nth-child` দিয়ে এটা করা হয়।

```html
<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }
  th, td {
    padding: 10px;
    border: 1px solid #ddd;
    text-align: left;
  }
  th {
    background-color: #333;
    color: white;
  }
  tr:nth-child(even) {
    background-color: #f2f2f2; /* জোড় নম্বর row তে হালকা ধূসর */
  }
  tr:hover {
    background-color: #ddd;    /* mouse নিলে রং বদলাবে */
  }
</style>
```

শুধু horizontal লাইন চাইলে:

```css
th, td {
  border-bottom: 1px solid #ddd; /* শুধু নিচে দাগ */
}
```

---

### Caption — টেবিলের টাইটেল

`<caption>` অবশ্যই `<table>` এর ঠিক পরে প্রথমে বসাতে হয়।

```html
<table>
  <caption>Student List</caption>
  <tr>
    <th>Name</th>
    <th>Roll</th>
  </tr>
</table>
```

---

### Colspan আর Rowspan — cell মার্জ করা

`colspan` দিয়ে একটা cell কে অনেক column জুড়ে বসানো যায়। `rowspan` দিয়ে অনেক row জুড়ে।

```html
<table border="1">
  <tr>
    <th colspan="2">Contact Info</th>  <!-- 2টা column জুড়ে -->
  </tr>
  <tr>
    <td>Phone</td>
    <td>01700000000</td>
  </tr>
  <tr>
    <td rowspan="2">Address</td>       <!-- 2টা row জুড়ে -->
    <td>Dhaka</td>
  </tr>
  <tr>
    <td>Bangladesh</td>
  </tr>
</table>
```

---

### Responsive Table — ছোট স্ক্রিনের জন্য

টেবিল বড় হলে মোবাইলে বাইরে চলে যায়। `div` দিয়ে wrap করে scroll দিলে সমস্যা মেটে।

```html
<div style="overflow-x: auto;">
  <table>
    ...
  </table>
</div>
```

---

## HTML Lists

### Unordered List — বুলেট পয়েন্টের লিস্ট

`<ul>` দিয়ে লিস্ট শুরু হয়, আর প্রতিটা item `<li>` এর ভেতরে থাকে। ডিফল্টে বুলেট (●) দেখায়।

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

---

### List Style Type — বুলেটের ধরন বদলানো

`list-style-type` দিয়ে বুলেটের চেহারা ঠিক করা হয়।

```html
<ul style="list-style-type: circle;">
  <li>Circle</li>
</ul>

<ul style="list-style-type: square;">
  <li>Square</li>
</ul>

<ul style="list-style-type: none;">
  <li>কোনো বুলেট নেই</li>
</ul>
```

| Value | ফলাফল |
|-------|--------|
| `disc` | ● (ডিফল্ট) |
| `circle` | ○ |
| `square` | ■ |
| `none` | বুলেট থাকবে না |

---

### Ordered List — নম্বর দেওয়া লিস্ট

`<ol>` দিয়ে নম্বর সহ লিস্ট হয়। যেখানে ধাপে ধাপে কিছু বোঝাতে হয়, সেখানে এটা কাজে লাগে।

```html
<ol>
  <li>ঘুম থেকে ওঠো</li>
  <li>ব্রাশ করো</li>
  <li>নাস্তা করো</li>
</ol>
```

---

### Ordered List Type — নম্বরের ধরন

`type` attribute দিয়ে নম্বরের স্টাইল বদলানো যায়।

```html
<ol type="1"> <li>Number (1, 2, 3)</li> </ol>
<ol type="A"> <li>Capital letter (A, B, C)</li> </ol>
<ol type="a"> <li>Small letter (a, b, c)</li> </ol>
<ol type="I"> <li>Roman capital (I, II, III)</li> </ol>
<ol type="i"> <li>Roman small (i, ii, iii)</li> </ol>
```

---

### Start আর Reversed

```html
<!-- 5 থেকে শুরু হবে -->
<ol start="5">
  <li>Five</li>
  <li>Six</li>
</ol>

<!-- উল্টো ক্রমে নম্বর হবে (3, 2, 1) -->
<ol reversed>
  <li>Third</li>
  <li>Second</li>
  <li>First</li>
</ol>
```

---

### Nested List — লিস্টের ভেতরে লিস্ট

একটা `<li>` এর ভেতরেই আরেকটা `<ul>` বা `<ol>` বসানো যায়।

```html
<ul>
  <li>Frontend
    <ul>
      <li>React</li>
      <li>Vue</li>
    </ul>
  </li>
  <li>Backend
    <ul>
      <li>Laravel</li>
      <li>Node.js</li>
    </ul>
  </li>
</ul>
```

**মনে রাখো:** ভেতরের লিস্ট অবশ্যই `<li>` এর ভেতরে থাকবে, `<ul>` এর সরাসরি ভেতরে না।

---

### Description List — নাম আর ব্যাখ্যার লিস্ট

`<dl>` দিয়ে শুরু হয়। `<dt>` হলো term (নাম), আর `<dd>` হলো description (ব্যাখ্যা)। Glossary বা FAQ এর জন্য ভালো।

```html
<dl>
  <dt>HTML</dt>
  <dd>ওয়েব পেজের স্ট্রাকচার বানানোর ভাষা</dd>

  <dt>CSS</dt>
  <dd>ওয়েব পেজ সুন্দর করার ভাষা</dd>
</dl>
```

---

### List Style Position — বুলেট ভেতরে না বাইরে

```html
<style>
  ul.outside { list-style-position: outside; } /* ডিফল্ট, বুলেট বাইরে */
  ul.inside  { list-style-position: inside; }  /* বুলেট লেখার ভেতরে */
</style>
```

---

### Custom Bullet Image — নিজের ছবি দিয়ে বুলেট

```css
ul {
  list-style-image: url('star.png');
}
```

**Extra:** সহজ উপায় হলো `list-style` shorthand ব্যবহার করা।

```css
ul {
  list-style: square inside;  /* type + position একসাথে */
}
```

---

### Horizontal List — লিস্ট পাশাপাশি বসানো (Navbar)

Navigation menu বানানোর সময় এই টেকনিক সবচেয়ে বেশি লাগে।

```html
<style>
  ul.nav {
    list-style-type: none;   /* বুলেট বাদ */
    margin: 0;
    padding: 0;
    display: flex;           /* পাশাপাশি বসাবে */
    gap: 20px;
  }
  ul.nav a {
    text-decoration: none;
    color: #333;
  }
</style>

<ul class="nav">
  <li><a href="#">Home</a></li>
  <li><a href="#">About</a></li>
  <li><a href="#">Contact</a></li>
</ul>
```

---

### Quick Summary — এক নজরে

| বিষয় | Tag / Property |
|-------|----------------|
| টেবিল শুরু | `<table>` |
| বর্ডার | `border: 1px solid` |
| ডবল বর্ডার ঠিক | `border-collapse: collapse` |
| সাইজ | `width`, `height` |
| ভেতরের ফাঁকা | `padding` |
| header | `<th>` |
| Cell মার্জ | `colspan`, `rowspan` |
| বুলেট লিস্ট | `<ul>` + `<li>` |
| নম্বর লিস্ট | `<ol>` + `<li>` |
| Description লিস্ট | `<dl>`, `<dt>`, `<dd>` |
| বুলেটের ধরন | `list-style-type` |


---



## 1. Class
 
### 1.1 Class কী?
 
`class` হলো একটা **গ্রুপের নাম**। একই নাম অনেক element কে দেওয়া যায়, তাই একবার স্টাইল লিখলেই সবগুলোতে কাজ করে।
 
**উদাহরণ:** স্কুলে "Class 10" এ অনেক ছাত্র থাকে। সবাই একই ক্লাসের, কিন্তু আলাদা মানুষ। HTML এ class ঠিক এরকম।
 
### 1.2 Syntax
 
- HTML এ লেখা হয়: `class="নাম"`
- CSS এ ধরা হয় **dot (`.`)** দিয়ে: `.নাম { }`
```html
<style>
  .highlight {
    background-color: yellow;
  }
</style>
 
<p class="highlight">এটা হাইলাইট হবে</p>
<p>এটা normal</p>
<p class="highlight">এটাও হাইলাইট হবে</p>
```
 
**Output:** প্রথম আর তৃতীয় লাইনের পেছনে হলুদ রং আসবে, মাঝেরটা আগের মতোই থাকবে।
 
### 1.3 একই Class, আলাদা Tag
 
Class যেকোনো tag এ বসানো যায়। Tag আলাদা হলেও স্টাইল একই আসবে।
 
```html
<h2 class="highlight">Heading</h2>
<span class="highlight">Span</span>
<div class="highlight">Div</div>
```
 
### 1.4 একটা Element এ একাধিক Class
 
Space দিয়ে আলাদা করে অনেকগুলো class দেওয়া যায়। ছোট ছোট স্টাইল জোড়া লাগিয়ে বড় ডিজাইন বানানো হয়।
 
```html
<style>
  .btn {
    padding: 10px 20px;
    border: none;
    border-radius: 6px;
    cursor: pointer;
  }
  .btn-green {
    background-color: green;
    color: white;
  }
  .btn-red {
    background-color: red;
    color: white;
  }
</style>
 
<button class="btn btn-green">Save</button>
<button class="btn btn-red">Delete</button>
```
 
এখানে `.btn` সব বাটনের কমন স্টাইল, আর `.btn-green` / `.btn-red` শুধু রং ঠিক করছে।
 
### 1.5 Real Life Example: Card
 
একটা ওয়েবসাইটে অনেকগুলো card থাকে। প্রতিটার জন্য আলাদা CSS না লিখে একটা class দিয়েই কাজ হয়।
 
```html
<style>
  .card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 16px;
    margin-bottom: 12px;
  }
</style>
 
<div class="card">Product 1</div>
<div class="card">Product 2</div>
<div class="card">Product 3</div>
```
 
### 1.6 কোথায় Class ব্যবহার করি?
 
| ব্যবহার | উদাহরণ |
|---------|---------|
| একই স্টাইল অনেক জায়গায় | `.card`, `.btn`, `.menu-item` |
| CSS Framework | Bootstrap: `class="btn btn-primary"` |
| Tailwind CSS | `class="bg-blue-500 text-white p-4"` |
| React | `className="card"` (এখানে `class` না, `className` লিখতে হয়) |
| JavaScript এ সব element ধরা | `document.querySelectorAll(".card")` |
 
---
 
## 2. ID
 
### 2.1 ID কী?
 
`id` হলো একটা element এর **নিজস্ব পরিচয়**। পুরো পেজে একটা id শুধু একটা element এর থাকবে, কারো সাথে মিলবে না।
 
**উদাহরণ:** ছাত্রের **Roll Number** বা মানুষের **NID নম্বর**। প্রত্যেকের আলাদা, দুজনের এক হয় না। HTML এ id ঠিক এরকম।
 
### 2.2 Syntax
 
- HTML এ লেখা হয়: `id="নাম"`
- CSS এ ধরা হয় **hash (`#`)** দিয়ে: `#নাম { }`
```html
<style>
  #main-title {
    color: crimson;
    text-align: center;
  }
</style>
 
<h1 id="main-title">My Website</h1>
```
 
### 2.3 ID এর ৩টা প্রধান ব্যবহার
 
**ব্যবহার ১: Page Jump Link (Bookmark)**
 
লিংকে ক্লিক করলে পেজের নির্দিষ্ট জায়গায় চলে যায়। Long page এ খুব কাজের।
 
```html
<a href="#contact">Contact এ যাও</a>
 
<!-- অনেক কন্টেন্ট থাকবে এখানে -->
 
<section id="contact">
  <h2>Contact Us</h2>
</section>
```
 
`href="#contact"` মানে হলো "যে element এর id `contact`, ওখানে নিয়ে যাও"।
 
**ব্যবহার ২: JavaScript দিয়ে একটা নির্দিষ্ট Element ধরা**
 
```html
<h2 id="title">Hello</h2>
<button onclick="changeText()">Change</button>
 
<script>
  function changeText() {
    document.getElementById("title").innerText = "Hello Arik!";
  }
</script>
```
 
**ব্যবহার ৩: Form এ Label এর সাথে Input জোড়া**
 
`label` এর `for` আর input এর `id` একই হলে label এ ক্লিক করলেই input সিলেক্ট হয়।
 
```html
<label for="email">Email:</label>
<input type="email" id="email">
```
 
### 2.4 ID এর নিয়ম
 
- একই পেজে **একই id দুইবার দেওয়া যাবে না**
- একটা element এ **একটাই id** থাকতে পারে
- Space দেওয়া যাবে না
```html
<!-- ভুল: একই id দুইবার -->
<div id="box">One</div>
<div id="box">Two</div>
 
<!-- ঠিক -->
<div id="box-one">One</div>
<div id="box-two">Two</div>
```
 
---
 
## 3. Class vs ID
 
| বিষয় | Class | ID |
|-------|-------|-----|
| সহজ কথায় | গ্রুপের নাম | নিজস্ব পরিচয় |
| কয়টা element এ ব্যবহার | অনেকগুলোতে | শুধু ১টাতে |
| এক element এ কয়টা | একাধিক (space দিয়ে) | মাত্র ১টা |
| CSS এ | `.name` | `#name` |
| JavaScript এ | `querySelectorAll(".name")` | `getElementById("name")` |
| Jump link | হয় না | হয় (`href="#name"`) |
| Priority | কম | বেশি |
| বেশি ব্যবহার | Styling | JS, jump link, label |
 
**একসাথে ব্যবহার:**
 
```html
<style>
  .card { border: 1px solid #ccc; padding: 15px; }
  #featured { border-color: red; }
</style>
 
<div class="card">Card 1</div>
<div class="card" id="featured">Card 2 (Featured)</div>
<div class="card">Card 3</div>
```
 
তিনটাই card এর স্টাইল পাবে, কিন্তু শুধু Card 2 এর বর্ডার লাল হবে।
 
---
 
## 4. Specificity
 
একই element এ class আর id দুটো দিয়ে আলাদা স্টাইল দিলে **id জিতে যায়**।
 
```html
<style>
  .text { color: blue; }
  #text1 { color: red; }
</style>
 
<p class="text" id="text1">এই লেখা লাল হবে</p>
```
 
**Priority ক্রম (বেশি থেকে কম):**
 
```
Inline style  >  #id  >  .class  >  tag
```
 
---
 
## 5. Naming Rules
 
| নিয়ম | ভালো | খারাপ |
|-------|------|-------|
| অক্ষর দিয়ে শুরু করো | `box1` | `1box` |
| Space দেওয়া যাবে না | `main-menu` | `main menu` |
| Case sensitive | `Box` আর `box` আলাদা | |
| কাজ বুঝে নাম দাও | `error-message` | `red-text` |
| ছোট হাতের অক্ষর + hyphen | `nav-link` | `NavLink` |
 
**মনে রাখো:** `class="my box"` লিখলে এটা একটা class না, দুটো আলাদা class (`my` আর `box`) হয়ে যায়।
 
---
 
## 6. Best Practices & Tips
 
1. **Styling এর জন্য class ব্যবহার করো, id না।** Id এর priority বেশি, তাই পরে স্টাইল বদলানো কঠিন হয়।
2. **Id শুধু এই কাজে রাখো:** jump link, JavaScript এ একটা নির্দিষ্ট element ধরা, আর `label for`।
3. **নাম দেখে কাজ বোঝা যায় এমন নাম দাও।** রং পরে বদলাতে পারে, কিন্তু কাজ একই থাকে।
```html
   <!-- খারাপ -->
   <div class="red-big"></div>
 
   <!-- ভালো -->
   <div class="error-message"></div>
```
 
4. **একই id কখনো দুইবার ব্যবহার করবে না।** HTML ভুল হয় আর JavaScript এ গোলমাল লাগে।
5. **BEM naming convention শেখো।** বড় প্রজেক্টে সবচেয়ে বেশি ব্যবহার হয়।
```html
   <div class="card">
     <h2 class="card__title">Title</h2>
     <p class="card__text">Text</p>
     <button class="card__btn card__btn--primary">Read</button>
   </div>
```
   Format: `block__element--modifier`
 
6. **সব element এ class দিও না।** আগে parent-child selector দিয়ে চেষ্টা করো।
```css
   .card p { color: gray; }   /* card এর ভেতরের সব p */
```
 
7. **Inspect Tool ব্যবহার করো।** Browser এ `F12` চাপলে কোন element এ কোন class/id আছে আর কোন CSS কাজ করছে সব দেখা যায়।
8. **Reusable class বানাও।** `.btn`, `.card`, `.container` এর মতো class একবার বানিয়ে সব পেজে ব্যবহার করো।
---
 

# HTML Layout, Responsive Design, Semantic Elements, Symbols & Emojis

---

## 1. HTML Layout — ওয়েবপেজ সাজানোর কাঠামো

HTML Layout দিয়ে একটা webpage কে কয়েকটা অংশে ভাগ করা হয়: উপরে **header**, তারপর **nav** (menu), মাঝে **main** content, পাশে **aside** (sidebar), আর একদম নিচে **footer**। এতে page টা সহজে পড়া যায়, search engine বুঝতে পারে, আর code ও গোছানো থাকে।

```
+---------------------------+
|          header           |
+---------------------------+
|            nav            |
+-----------------+---------+
|                 |         |
|      main       |  aside  |
|                 |         |
+-----------------+---------+
|          footer           |
+---------------------------+
```

```html
<body>
  <!-- একদম উপরে: logo আর site এর নাম -->
  <header>
    <h1>My Website</h1>
  </header>

  <!-- menu: বিভিন্ন page এর link -->
  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <!-- মূল content এখানে -->
  <main>
    <h2>Welcome</h2>
    <p>এটা আমার main content।</p>
  </main>

  <!-- পাশের অংশ: extra info, ads, related links -->
  <aside>
    <h3>Related Links</h3>
  </aside>

  <!-- একদম নিচে: copyright, contact info -->
  <footer>
    <p>© 2026 My Website</p>
  </footer>
</body>
```

### CSS দিয়ে main আর aside পাশাপাশি আনা (Flexbox)

শুধু HTML দিলে সব উপর-নিচ হয়ে থাকে। পাশাপাশি আনতে CSS লাগে।

```html
<style>
  /* main আর aside কে একসাথে row তে রাখবে */
  .container {
    display: flex;
    gap: 20px;
  }

  main  { flex: 3; background-color: lightyellow; }  /* বেশি জায়গা */
  aside { flex: 1; background-color: lightblue; }    /* কম জায়গা */
</style>

<div class="container">
  <main>Main Content</main>
  <aside>Sidebar</aside>
</div>
```

> 💡 **Tips:**
> - Layout এর প্রতিটা অংশের কাজ আলাদা, তাই সব জায়গায় `<div>` না দিয়ে সঠিক tag ব্যবহার করো।
> - একটা page এ `<main>` শুধু **একটাই** থাকবে।
> - `<header>` আর `<footer>` শুধু page এর উপর-নিচে না, `<article>` বা `<section>` এর ভেতরেও ব্যবহার করা যায়।
> - Layout বানানোর আগে কাগজে একটা rough sketch করে নিলে কাজ অনেক সহজ হয়।
> - আজকাল layout এর জন্য **Flexbox** আর **CSS Grid** সবচেয়ে বেশি use হয়। পুরনো `float` এড়িয়ে চলো।

---

## 2. HTML Responsive Web Design — সব screen এ সুন্দর দেখানো

Responsive Design মানে তোমার website টা mobile, tablet, laptop সব device এ নিজে নিজে screen এর size অনুযায়ী adjust হবে। আলাদা আলাদা website বানাতে হবে না।

### Step 1: Viewport meta tag (সবচেয়ে জরুরি)

```html
<head>
  <!-- mobile এ page টা screen এর width অনুযায়ী দেখাবে -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

এটা না দিলে mobile browser পুরো desktop page টাকে ছোট করে দেখায়, তখন লেখা পড়াই যায় না।

### Step 2: Image কে flexible করা

```html
<!-- image কখনো তার box এর বাইরে যাবে না -->
<img src="photo.jpg" style="max-width: 100%; height: auto;" alt="My Photo">
```

### Step 3: Media Query দিয়ে screen অনুযায়ী style বদলানো

```html
<style>
  .container {
    display: flex;          /* বড় screen এ পাশাপাশি */
    gap: 20px;
  }

  /* screen এর width 600px বা তার কম হলে এই style চলবে */
  @media (max-width: 600px) {
    .container {
      flex-direction: column;   /* mobile এ উপর-নিচ হয়ে যাবে */
    }
  }
</style>
```

### কিছু common breakpoint

| Device | Width |
|--------|-------|
| Mobile | `max-width: 600px` |
| Tablet | `max-width: 768px` |
| Laptop | `max-width: 1024px` |

> 💡 **Tips:**
> - **Mobile First** approach নাও: আগে ছোট screen এর জন্য style লেখো, তারপর `min-width` দিয়ে বড় screen এর জন্য বাড়াও।
> - Fixed `px` এর বদলে `%`, `rem`, `vw` ব্যবহার করলে layout বেশি flexible হয়।
> - Browser এ **F12 → Device Toolbar** দিয়ে mobile view টেস্ট করতে পারবে।
> - Viewport meta tag ভুলে গেলে responsive কাজই করবে না, তাই এটা সবসময় আগে লিখো।
> - Real phone এ একবার test করে নিও, কারণ emulator এ সব সময় ঠিক ধরা পড়ে না।

---

## 3. Semantic vs Non-semantic Elements — অর্থবহ আর অর্থহীন tag

**Non-semantic element** কিছুই বলে না তার ভেতরে কী আছে। যেমন `<div>` আর `<span>`।

**Semantic element** নিজের নাম দিয়েই বলে দেয় তার কাজ কী। যেমন `<header>`, `<nav>`, `<article>`, `<footer>`।

### Non-semantic ভাবে লেখা

```html
<!-- দেখে বোঝা যায় না কোনটা কী -->
<div id="header">My Blog</div>
<div id="nav">Home | About</div>
<div id="content">Some text...</div>
<div id="footer">© 2026</div>
```

### Semantic ভাবে লেখা

```html
<!-- tag দেখেই বোঝা যাচ্ছে কোনটা কী -->
<header>My Blog</header>
<nav>Home | About</nav>
<main>Some text...</main>
<footer>© 2026</footer>
```

### কিছু গুরুত্বপূর্ণ Semantic Tag

| Tag | কাজ |
|-----|-----|
| `<header>` | page বা section এর উপরের অংশ |
| `<nav>` | navigation links |
| `<main>` | মূল content |
| `<section>` | একটা বিষয়ের group |
| `<article>` | নিজে নিজে পূর্ণ content (blog post, news) |
| `<aside>` | পাশের বা অতিরিক্ত তথ্য |
| `<figure>` + `<figcaption>` | image আর তার caption |
| `<footer>` | নিচের অংশ |

```html
<article>
  <h2>HTML শেখার সহজ উপায়</h2>
  <p>প্রতিদিন একটু একটু practice করো।</p>

  <!-- image আর তার নিচে লেখা -->
  <figure>
    <img src="html.png" alt="HTML logo">
    <figcaption>HTML এর logo</figcaption>
  </figure>
</article>
```

> 💡 **Tips:**
> - Semantic tag ব্যবহার করলে **SEO** ভালো হয়, কারণ Google সহজে বুঝতে পারে কোনটা কী।
> - **Accessibility** বাড়ে: screen reader ব্যবহারকারীরা সহজে page ঘুরে দেখতে পারে।
> - `<div>` একদম বাদ দিতে হবে না। যখন কোনো semantic tag মানায় না (শুধু styling এর জন্য group করা), তখন `<div>` ঠিক আছে।
> - `<section>` আর `<article>` এ confuse হলে ভাবো: content টা কি আলাদা করে অন্য জায়গায় দিলেও মানে থাকবে? থাকলে `<article>`।
> - Interview এ প্রায়ই জিজ্ঞেস করে, তাই 4-5 টা semantic tag এর নাম মুখস্থ রাখো।

---

## 4. HTML Symbols — বিশেষ চিহ্ন লেখা

কিছু চিহ্ন keyboard এ নেই (যেমন ©, ™, €), আবার কিছু চিহ্ন HTML এর নিজের কাজে লাগে (যেমন `<` আর `>`)। এগুলো দেখাতে **HTML Entity** ব্যবহার করা হয়।

Entity শুরু হয় `&` দিয়ে আর শেষ হয় `;` দিয়ে।

```html
<!-- Copyright আর Trademark -->
<p>&copy; 2026 My Company&trade;</p>

<!-- HTML tag কে লেখা হিসেবে দেখানো -->
<p>&lt;h1&gt; হলো সবচেয়ে বড় heading।</p>

<!-- টাকা ও মুদ্রার চিহ্ন -->
<p>Price: &euro;50, &pound;40, &yen;500</p>
```

**Output:**
© 2026 My Company™
`<h1>` হলো সবচেয়ে বড় heading।
Price: €50, £40, ¥500

### বহুল ব্যবহৃত Symbol

| দেখতে | Entity Name | Entity Number |
|-------|-------------|---------------|
| © | `&copy;` | `&#169;` |
| ® | `&reg;` | `&#174;` |
| ™ | `&trade;` | `&#8482;` |
| < | `&lt;` | `&#60;` |
| > | `&gt;` | `&#62;` |
| & | `&amp;` | `&#38;` |
| " | `&quot;` | `&#34;` |
| € | `&euro;` | `&#8364;` |
| ♥ | `&hearts;` | `&#9829;` |
| → | `&rarr;` | `&#8594;` |

### Non-breaking space

```html
<!-- HTML এ অনেকগুলো space দিলেও একটাই দেখায় -->
<p>Hello          World</p>

<!-- &nbsp; দিলে জোর করে space দেখাবে -->
<p>Hello&nbsp;&nbsp;&nbsp;&nbsp;World</p>
```

> 💡 **Tips:**
> - `<` আর `>` সরাসরি লিখলে browser ওটাকে tag মনে করবে। তাই code দেখাতে চাইলে সবসময় `&lt;` আর `&gt;` ব্যবহার করো।
> - Entity name মনে না থাকলে **entity number** (`&#169;`) দিয়েও কাজ হয়।
> - `&nbsp;` দিয়ে layout এর gap বানানো ভালো অভ্যাস না। gap এর জন্য CSS `margin` বা `padding` ব্যবহার করো।
> - Entity সবসময় **case-sensitive**: `&copy;` কাজ করবে, `&COPY;` না।
> - `&amp;` ভুলে যেও না। URL এর ভেতরে `&` থাকলে ওটা `&amp;` লিখতে হয়।

---

## 5. Emojis in HTML — Emoji ব্যবহার করা

Emoji আসলে Unicode character। তাই HTML এ সহজেই ব্যবহার করা যায়, কোনো image লাগে না।

### আগে charset ঠিক করো

```html
<head>
  <!-- UTF-8 না দিলে emoji এর জায়গায় ??? বা অদ্ভুত চিহ্ন দেখাবে -->
  <meta charset="UTF-8">
</head>
```

### Emoji দেখানোর ৩টা উপায়

```html
<!-- ১. সরাসরি emoji লেখা (সবচেয়ে সহজ) -->
<p>I love coding 😍</p>

<!-- ২. Decimal code দিয়ে -->
<p>I love coding &#128525;</p>

<!-- ৩. Hexadecimal code দিয়ে -->
<p>I love coding &#x1F60D;</p>
```

তিনটাই একই emoji দেখাবে।

### কিছু জনপ্রিয় Emoji

| Emoji | Decimal | Hex |
|-------|---------|-----|
| 😀 | `&#128512;` | `&#x1F600;` |
| 😍 | `&#128525;` | `&#x1F60D;` |
| 👍 | `&#128077;` | `&#x1F44D;` |
| 🔥 | `&#128293;` | `&#x1F525;` |
| ❤️ | `&#10084;` | `&#x2764;` |
| 🚀 | `&#128640;` | `&#x1F680;` |

### Emoji কে বড় বা ছোট করা

```html
<!-- emoji আসলে text, তাই font-size দিয়েই size বদলায় -->
<p style="font-size: 50px;">🚀</p>
```

> 💡 **Tips:**
> - `<meta charset="UTF-8">` সবসময় `<head>` এর একদম শুরুর দিকে দাও।
> - Emoji দেখতে একেক device আর browser এ একটু আলাদা হয় (Android, iPhone, Windows এ ভিন্ন design)।
> - শুধু emoji দিয়ে কিছু বোঝালে screen reader সেটা ঠিকমতো পড়তে পারে না। দরকার হলে পাশে লেখাও দাও।
> - Heading বা button এ emoji ব্যবহার করলে page টা বেশি friendly লাগে, কিন্তু বেশি দিলে unprofessional দেখায়।
> - Emoji কে text হিসেবে copy-paste করাই সবচেয়ে সহজ, code মুখস্থ রাখার দরকার নেই।

---




 
