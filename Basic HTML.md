
<div align="center">

# HTML (Hyper Text Markup Language)

## Web Development Notes

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
 
### Semantic Tags 
HTML এর এমন ট্যাগ যেগুলো দিয়ে ওয়েবপেজের আলাদা আলাদা অংশের অর্থ বোঝানো হয় (যেমন header, footer, nav ইত্যাদি), যাতে ব্রাউজার ও মানুষ দুজনেই সহজে বুঝতে পারে কোন অংশটা কী কাজ করছে। এগুলো ব্যবহার করলে কোড সহজে বুঝা যায় এবং ওয়েবপেজ সুন্দরভাবে সাজানো থাকে। 
**`উদাহরণ:`**
 
```html
<header>এখানে website এর উপরের অংশ থাকে</header>
<nav>এখানে navigation menu থাকে</nav>
<main>এখানে page এর মূল content থাকে</main>
<section>একটি নির্দিষ্ট অংশ</section>
<article>একটি স্বতন্ত্র লেখা বা post</article>
<aside>পাশের অংশ — যেমন sidebar</aside>
<footer>এখানে website এর নিচের অংশ থাকে</footer>
```

 
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
 
