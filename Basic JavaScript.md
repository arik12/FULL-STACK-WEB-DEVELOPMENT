<div align="center">

# JavaScript

</div>

# Introduction

Imagine you built a house.You constructed the walls, doors, windows, and roof that's the structure. Then you painted the walls, added lights, placed furniture, and decorated everything beautifully.Now the house looks amazing.

But there's still something missing. The lights don't turn on by themselves. The doors don't lock automatically. There's no security system, no smart features, nothing that *reacts* when you do something.

Now imagine you add electricity, switches, sensors, and automation to the house. You press a switch and the light turns on. You approach the door and it unlocks. The house now **responds** to your actions.

This is exactly what JavaScript does for a website.

If HTML is the structure (skeleton) and CSS is the design (skin, colors, fashion), then **JavaScript is the brain and nervous system** of a website. It makes the page interactive, dynamic, and alive.

JavaScript stands for **JavaScript** (yes, just that — it's not related to Java despite the name). It is a programming language that runs in the browser and allows websites to:

- Respond to clicks, typing, and other user actions
- Change content on the page without reloading
- Validate forms before submission
- Create animations and interactive effects
- Fetch data from servers and update the page dynamically
- Build entire web applications (with frameworks like React, Vue, etc.)

Without JavaScript, websites would just sit there — looking nice, but doing nothing. With JavaScript, a website can think, react, and interact.

So, HTML builds the structure, CSS makes it beautiful, and **JavaScript brings it to life.**

---

# History of JavaScript

JavaScript was created in **1995** by **Brendan Eich**, while he was working at **Netscape Communications**.

Interestingly, Brendan Eich wrote the first version of JavaScript in just **10 days**. At that time, websites were static — they could only display content, not interact with users. Netscape wanted a lightweight scripting language that could run inside the browser and make web pages more dynamic.

The language was originally called **Mocha**, then renamed to **LiveScript**, and finally renamed to **JavaScript** — mainly as a marketing move, since Java was a popular programming language at that time. Despite the similar name, JavaScript and Java are completely different languages.

> "A language born in 10 days ended up powering almost every website on the internet."

Over time, JavaScript evolved through many versions:

- **ES5 (2009)** — Added many useful methods and stabilized the language
- **ES6 / ES2015** — A major update: introduced `let`, `const`, arrow functions, classes, promises, and more
- **ES2016 and later** — Continued yearly updates adding modern features like `async/await`, optional chaining, and more

Today, JavaScript is one of the **most popular programming languages in the world**. It runs not just in browsers, but also on servers (Node.js), mobile apps, desktop apps, and even IoT devices.

---
---

## What is JavaScript?

JavaScript is a programming language that makes web pages interactive. While HTML gives structure and CSS gives style, JavaScript gives **behavior** — it decides what happens when a user clicks a button, submits a form, scrolls the page, or interacts in any way.

In simple terms:

- HTML = Structure
- CSS = Design & Style
- JavaScript = Behavior & Interactivity

JavaScript makes web pages dynamic, interactive, and functional — turning a static page into a real application.

---

## What can JavaScript do?

- 🖱️ Respond to user actions (clicks, typing, scrolling)
- 🔄 Change HTML content and CSS styles dynamically
- ✅ Validate form data before sending
- 🌐 Fetch data from servers (APIs) without reloading the page
- 🎬 Create animations and interactive effects
- 🧠 Store and manage data (variables, arrays, objects)
- 🏗️ Build full web applications (with React, Vue, Node.js, etc.)

---

##JavaScript can be added in **three ways**, just like CSS:

- **External JavaScript** – using a separate `.js` file, linked to the HTML page
- **Internal JavaScript** – using a `<script>` tag inside the HTML page
- **Inline JavaScript** – writing JS directly inside an HTML element's attribute (like `onclick`)

### 🔹 External JavaScript
 
```html
<!-- index.html -->
<!DOCTYPE html>
<html>
<body>
  <h1>Hello World</h1>
  <button onclick="showMessage()">Click Me</button>
 
  <script src="script.js"></script>
</body>
</html>
```
 
```js
// script.js
function showMessage() {
  alert("Button was clicked!");
}
```
 
### 🔹 Internal JavaScript
 
```html
<!DOCTYPE html>
<html>
<body>
  <h1 id="title">Hello World</h1>
  <button onclick="changeText()">Click Me</button>
 
  <script>
    function changeText() {
      document.getElementById("title").innerHTML = "Text Changed!";
    }
  </script>
</body>
</html>
```
 
### 🔹 Inline JavaScript
 

 
```html
<button onclick="alert('You clicked the button!')">Click Me</button>
```
 
---


# How JavaScript Works

## A Short Story About JavaScript

Imagine you are creating a website.First, you create a page using **HTML**.

HTML gives your website a structure:

- Heading
- Paragraph
- Button
- Image
- Form


Then you use **CSS** to make your website beautiful.

CSS adds:

- Colors
- Fonts
- Layout
- Animation


Now your website looks amazing.But there is a problem.When users click a button, nothing happens.When users submit a form, the website cannot respond.The website looks beautiful but it is not interactive.It is like a beautiful car without an engine.

Then JavaScript comes and says: "I will add life to your website." JavaScript brings life to websites by making them interactive and responsive.

With JavaScript, we can:

- Handle button clicks
- Change webpage content
- Validate user input
- Create animations
- Fetch data from servers
- Build full web applications


So we can say:

HTML = Structure
CSS = Design
JavaScript = Behavior

Together:

HTML + CSS + JavaScript -> Structure + Design + Interaction


# What is JavaScript Framework?

## Introduction

A JavaScript Framework is a collection of ready-made code and rules that helps developers build websites and web applications easily.

Normally, developers need to write a lot of code from the beginning. A framework provides a basic structure, so developers can create applications faster and manage code easily.

In simple words:

**A JavaScript Framework is a tool that helps developers build modern websites faster and in an organized way.**

---

## Why Do We Need JavaScript Frameworks?

When a website becomes large, managing everything with plain JavaScript becomes difficult.

JavaScript Framework helps developers to:

- Write less code
- Organize code properly
- Build websites faster
- Create reusable parts
- Manage complex applications easily

---

## How Does a JavaScript Framework Work?

A framework gives developers a ready structure to build applications.

For example:

Instead of creating every button, page, and feature from zero, developers can use framework tools and create them quickly.

It helps to manage:

- User interface (what users see)
- Data handling
- Page updates
- Application structure

---

# Popular JavaScript Frameworks

## 1. React.js

React is a popular JavaScript library used to create fast and interactive user interfaces.

**Used for:**
- Single page websites
- Social media apps
- Dashboard applications
- E-commerce websites

---

## 2. Angular

Angular is a complete JavaScript framework created by Google.

It provides many built-in features for building large applications.

**Used for:**
- Enterprise applications
- Large websites
- Business software

---

## 3. Vue.js

Vue.js is a simple and beginner-friendly JavaScript framework.

It is easy to learn and helps developers create interactive websites.

**Used for:**
- Small to medium websites
- Web interfaces
- Single page applications

---

## 4. Next.js

Next.js is a framework based on React.

It helps developers create faster and SEO-friendly websites.

**Used for:**
- Modern websites
- Blogs
- E-commerce platforms

---

# Benefits of JavaScript Frameworks

- Faster development
- Cleaner code
- Easy maintenance
- Reusable components
- Better project structure

---

# JavaScript Framework vs Normal JavaScript

### Normal JavaScript:
Developers write most features manually.

### JavaScript Framework:
Provides ready tools and structure to build applications faster.

---



## 🔹 1. Variables — `let`, `const`, `var`

### 📖 Definition (বাংলা)
**Variable** মানে হলো একটা container বা বাক্স, যেখানে আমরা data রাখি এবং পরে সেই data ব্যবহার করি। JavaScript-এ variable declare করার জন্য তিনটা keyword ব্যবহার হয়: `var`, `let`, এবং `const`।

### 📖 Definition (English)
A **variable** is a container used to store data values. In JavaScript, you can declare variables using `var`, `let`, or `const` — each with different scoping and reassignment rules.

| Keyword | Scope | Re-declare | Re-assign | Kobe use korbo |
|---|---|---|---|---|
| `var` | Function scope | ✅ Yes | ✅ Yes | Purano code, generally avoid করা ভালো |
| `let` | Block scope | ❌ No | ✅ Yes | Value পরে change হবে এমন ক্ষেত্রে |
| `const` | Block scope | ❌ No | ❌ No | Value fixed/constant থাকবে এমন ক্ষেত্রে |

### 💻 Example
```javascript
var name = "Arik";        // function scoped, purano style
let age = 25;              // block scoped, change kora jabe
const country = "Bangladesh"; // block scoped, change kora jabe na

age = 26;        // ✅ thik ache, let re-assign kora jai
// country = "India"; // ❌ Error dibe, const re-assign kora jai na
```

### ⚠️ Common Mistakes
- `const` দিয়ে declare করা variable-এর value পরে পরিবর্তন করার চেষ্টা করলে **error** আসবে।
- `var` ব্যবহার করলে **hoisting**-এর কারণে অনেক সময় unexpected bug হতে পারে — তাই modern JS-এ `let`/`const` recommend করা হয়।

### 💡 Tip
> সবসময় default হিসেবে `const` ব্যবহার করো। Value change করা লাগলে তখন `let` ব্যবহার করো। `var` প্রায় avoid করাই ভালো।

---

## 🔹 2. Data Types — String, Number, Boolean, Null, Undefined, Object

### 📖 Definition (বাংলা)
JavaScript-এ প্রতিটা value-এর একটা **data type** থাকে। এগুলো মূলত দুই ভাগে ভাগ করা যায় — **Primitive** (String, Number, Boolean, Null, Undefined) আর **Non-Primitive/Reference** (Object, Array, Function)।

### 📖 Definition (English)
A **data type** defines what kind of value a variable holds. JavaScript has primitive types (String, Number, Boolean, Null, Undefined, Symbol, BigInt) and reference types (Object, Array, Function).

### 💻 Example
```javascript
let myName = "Arik";        // String — text data
let myAge = 25;             // Number — integer or float
let isDeveloper = true;     // Boolean — true/false
let salary = null;          // Null — intentionally "kono value nai"
let address;                // Undefined — value assign kora hoyni
let user = {                // Object — key-value pair
  name: "Arik",
  role: "Web Developer"
};

console.log(typeof myName);      // "string"
console.log(typeof myAge);       // "number"
console.log(typeof isDeveloper); // "boolean"
console.log(typeof salary);      // "object" (ei ta ekta famous JS quirk!)
console.log(typeof address);     // "undefined"
```

### ⚠️ Common Mistakes
- `null` এবং `undefined` গুলিয়ে ফেলা — `undefined` মানে variable-এ কোনো value দেওয়াই হয়নি, আর `null` মানে ইচ্ছাকৃতভাবে "empty" set করা হয়েছে।
- `typeof null` আসলে `"object"` return করে — এটা JavaScript-এর একটা পুরনো bug, কিন্তু এখন fix করা যাবে না backward compatibility-এর জন্য।

### 💡 Tip
> `typeof` operator দিয়ে যেকোনো variable-এর data type check করা যায় — debugging-এর সময় খুব কাজে লাগে।

---

## 🔹 3. Operators — Arithmetic, Comparison, Logical

### 📖 Definition (বাংলা)
**Operator** হলো special symbol যা দিয়ে আমরা values-এর উপর কোনো operation (গণনা, তুলনা, বা logic) করি।

### 📖 Definition (English)
**Operators** are special symbols used to perform operations on values and variables — such as arithmetic calculations, comparisons, or logical checks.

### 💻 Example — Arithmetic
```javascript
let a = 10, b = 3;

console.log(a + b);  // 13 — Addition
console.log(a - b);  // 7  — Subtraction
console.log(a * b);  // 30 — Multiplication
console.log(a / b);  // 3.33 — Division
console.log(a % b);  // 1  — Modulus (remainder)
console.log(a ** b); // 1000 — Exponent (power)
```

### 💻 Example — Comparison
```javascript
console.log(5 == "5");   // true  — value check kore, type check kore na
console.log(5 === "5");  // false — value ar type dutai check kore
console.log(5 != "5");   // false
console.log(5 !== "5");  // true
console.log(5 > 3);      // true
console.log(5 <= 5);     // true
```

### 💻 Example — Logical
```javascript
let isLoggedIn = true;
let isAdmin = false;

console.log(isLoggedIn && isAdmin); // false — dutai true hote hobe
console.log(isLoggedIn || isAdmin); // true  — jekono ekta true hole hobe
console.log(!isLoggedIn);           // false — reverse kore dey
```

### ⚠️ Common Mistakes
- `==` আর `===`-এর difference না বোঝা — সবসময় `===` (strict equality) ব্যবহার করা better practice, কারণ এটা type mismatch এড়িয়ে চলে।
- Logical operator `&&` আর `||`-এর priority গুলিয়ে ফেলা।

### 💡 Tip
> Comparison-এর সময় সবসময় `===` এবং `!==` ব্যবহার করো, `==`/`!=` না — unexpected bug থেকে বাঁচবে।

---

## 🔹 4. Input & Output — `prompt()`, `alert()`, `console.log()`

### 📖 Definition (বাংলা)
Browser-এ user-এর সাথে interact করার জন্য বা developer হিসেবে output দেখার জন্য JavaScript কিছু built-in method দেয় — `prompt()` দিয়ে input নেওয়া যায়, `alert()` দিয়ে popup message দেখানো যায়, আর `console.log()` দিয়ে browser console-এ output print করা যায়।

### 📖 Definition (English)
JavaScript provides built-in functions for basic input/output: `prompt()` takes user input via a popup, `alert()` displays a popup message, and `console.log()` prints output to the browser's developer console — mainly used for debugging.

### 💻 Example
```javascript
// Input neya (browser popup)
let userName = prompt("Tomar naam ki?");

// Alert box e message dekhano
alert("Welcome, " + userName + "!");

// Console e output print kora (debugging er jonno best)
console.log("User entered:", userName);
console.log("Sum is:", 5 + 10);
```

### ⚠️ Common Mistakes
- `prompt()` থেকে আসা value সবসময় **String** টাইপে আসে — number হিসেবে ব্যবহার করতে চাইলে `Number()` দিয়ে convert করতে হয়।
- Production website-এ `alert()` বেশি ব্যবহার না করা ভালো, কারণ এটা user experience-এর জন্য বিরক্তিকর।

### 💡 Tip
> Debugging-এর জন্য `console.log()` সবচেয়ে বেশি ব্যবহৃত tool — code-এর কোন জায়গায় সমস্যা হচ্ছে সেটা বের করতে এটা সবচেয়ে সহজ উপায়।

---

## 🔹 5. Conditional Statements — `if`, `else`, `switch`

### 📖 Definition (বাংলা)
**Conditional statement** ব্যবহার করা হয় কোনো condition-এর উপর ভিত্তি করে আলাদা আলাদা code execute করার জন্য। `if-else` দিয়ে সাধারণ condition check করা হয়, আর অনেকগুলো fixed value check করতে হলে `switch` ব্যবহার করা হয়।

### 📖 Definition (English)
**Conditional statements** let you execute different blocks of code based on different conditions. `if-else` is used for general condition checking, while `switch` is preferred when comparing a single value against multiple fixed cases.

### 💻 Example — if / else
```javascript
let marks = 75;

if (marks >= 80) {
  console.log("Grade: A+");
} else if (marks >= 60) {
  console.log("Grade: A");
} else {
  console.log("Grade: F");
}
```

### 💻 Example — switch
```javascript
let day = "Saturday";

switch (day) {
  case "Friday":
    console.log("Weekend শুরু!");
    break;
  case "Saturday":
    console.log("আজকে ছুটি!");
    break;
  case "Sunday":
    console.log("শেষ ছুটির দিন");
    break;
  default:
    console.log("আজকে কাজের দিন");
}
```

### ⚠️ Common Mistakes
- `switch` statement-এ `break` দিতে ভুলে যাওয়া — এতে পরের সব `case` execute হয়ে যায় (fall-through bug)।
- `if` condition-এর মধ্যে `=` (assignment) আর `==`/`===` (comparison) গুলিয়ে ফেলা।

### 💡 Tip
> শুধু ২-৩টা fixed value-এর মধ্যে compare করলে `switch` পড়তে সহজ হয়, কিন্তু complex condition (যেমন range check) হলে `if-else` ব্যবহার করাই ভালো।

---


## 🔹 6. Loops — `for`, `while`, `do...while`
 
### 📖 Definition (বাংলা)
**Loop** ব্যবহার করা হয় একই কাজ বারবার repeat করার জন্য, যতক্ষণ না একটা নির্দিষ্ট condition পূরণ হয়। এতে code ছোট থাকে এবং বারবার একই লাইন লিখতে হয় না।
 
### 📖 Definition (English)
A **loop** is used to execute a block of code repeatedly as long as a specified condition is true — helping avoid writing the same code multiple times.
 
### 💻 Example — for loop
```javascript
// for loop e 3ta part thake: initialization; condition; increment/decrement
for (let i = 1; i <= 5; i++) {
  // let i = 1        -> initialization: loop shuru howar age ekbar e run hoy, counter set kore
  // i <= 5            -> condition: protibar loop body run howar age check hoy, true thakle loop cholte thake
  // i++               -> increment: protibar loop body run howar por i-r man 1 kore barbe
  console.log(i);       // loop body: ei code ta protibar run hobe jotokkhon condition true thake
}
```
 
**Part-wise explanation:**
- `let i = 1` → **Initialization** — counter variable declare o set kore, loop shuru howar somoy shudhu 1 bar run hoy।
- `i <= 5` → **Condition** — প্রতিবার loop body execute howar age check hoy, true hole loop chole, false hole loop theme jai।
- `i++` → **Increment/Decrement** — protibar body run shesh hole counter update hoy, na hole infinite loop hoye jabe।
### 💻 Example — while loop
```javascript
let i = 1;            // initialization: loop-er baire condition check howar age counter set kora hoy
 
while (i <= 5) {       // condition: age check hoy, true hole tobei loop body-te dhoke
  console.log(i);       // loop body: condition true thakle ei code run hobe
  i++;                  // increment: body-r ses e counter update kora hoy, na hole loop kokhono thambe na
}
```
 
**Part-wise explanation:**
- `let i = 1;` → loop shuru howar age counter alada line-e set korte hoy (for loop-er moto ekshathe na)।
- `while (i <= 5)` → **Condition** — body-te dhokar age protibar check hoy, condition false hole loop ekbare o run hobe na।
- `i++` → **Increment** — body-r vitore manually likhte hoy, na hole condition kখনো false hobe na।
### 💻 Example — do...while loop
```javascript
let i = 1;            // initialization: counter set kora
 
do {
  console.log(i);       // loop body: condition check howar AGE ekbar obosshoi run hobe
  i++;                  // increment: protibar body run howar por counter update hoy
} while (i <= 5);      // condition: body run howar POR check hoy, true hole abar loop cholbe
```
 
**Part-wise explanation:**
- `let i = 1;` → counter age theke set kora hoy, jemon while loop-e hoy।
- `do { ... }` → **Loop body** — eikhane condition check howar age e ekbar mandatory run hoy, eta e `while` theke main difference।
- `while (i <= 5);` → **Condition** — body run howar por check hoy; true hole abar loop e dhoke, false hole loop shesh, ar `;` dite hobe seshe।
### ⚠️ Common Mistakes
- Loop-এর ভিতরে counter variable (`i++`) update করতে ভুলে গেলে **infinite loop** হয়ে যায় — browser hang হয়ে যেতে পারে।
- `while` আর `do...while`-এর difference না বোঝা — `do...while` এ condition false হলেও body একবার অবশ্যই run হবে।
- `for` loop-এ 3টা part (initialization; condition; increment)-এর মধ্যে সঠিক জায়গায় `;` না দেওয়া — syntax error দিবে।
- `do...while`-এর শেষে `;` (semicolon) দিতে ভুলে যাওয়া — এটা while loop থেকে ভিন্ন, do...while-এ শেষে `;` লাগবেই।
- `while` loop-এ counter (`i++`) body-এর ভিতরে লিখতে ভুলে যাওয়া — condition কখনো false না হয়ে infinite loop হয়ে যায়।
### 💡 Tip
> কতবার loop চালাতে হবে সেটা আগে থেকে জানা থাকলে `for` loop ব্যবহার করো — কারণ initialization, condition, increment সব একসাথে থাকে তাই readable। Condition-based repeat (কতবার run হবে জানা নাই) হলে `while` ব্যবহার করো। আর body অন্তত একবার run হওয়া লাগবেই এমন ক্ষেত্রে `do...while` ব্যবহার করো।
 
---


## 🔹 7. Arrays — Store Multiple Values

### 📖 Definition (বাংলা)

**Array** হলো JavaScript-এর একটি data structure, যেখানে একটি single variable-এর মধ্যে একাধিক value store করা যায়। Array-এর প্রতিটি value একটি নির্দিষ্ট **index**-এর মাধ্যমে access করা যায়, এবং index সবসময় `0` থেকে শুরু হয়।

### 📖 Definition (English)

An **Array** is a JavaScript data structure used to store multiple values in a single variable. Each value can be accessed using an **index**, which starts from `0`.

---

### 💻 Example — Create an Array

```javascript
let fruits = ["Apple", "Mango", "Banana"];

console.log(fruits);
```

**Output:**

```text
["Apple", "Mango", "Banana"]
```

---

### 💻 Example — Access Array Elements

```javascript
let fruits = ["Apple", "Mango", "Banana"];

console.log(fruits[0]); // Apple
console.log(fruits[1]); // Mango
console.log(fruits[2]); // Banana
```

> 💡 Array-এর first element-এর index হলো `0`, second element-এর `1`, এবং third element-এর `2`।

---

### 💻 Example — Change an Array Element

```javascript
let fruits = ["Apple", "Mango", "Banana"];

fruits[1] = "Orange";

console.log(fruits);
```

**Output:**

```text
["Apple", "Orange", "Banana"]
```

---

### 💻 Example — Array Length

```javascript
let colors = ["Red", "Blue", "Green", "Black"];

console.log(colors.length); // 4
```

> `length` property ব্যবহার করে Array-এর মোট element সংখ্যা জানা যায়।

---

### 💻 Example — Add Elements with `push()`

`push()` method ব্যবহার করে Array-এর শেষে নতুন element যোগ করা যায়।

```javascript
let fruits = ["Apple", "Mango"];

fruits.push("Banana");

console.log(fruits);
```

**Output:**

```text
["Apple", "Mango", "Banana"]
```

---

### 💻 Example — Remove Element with `pop()`

`pop()` method Array-এর শেষ element remove করে।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

fruits.pop();

console.log(fruits);
```

**Output:**

```text
["Apple", "Mango"]
```

---

### 💻 Example — Add Element with `unshift()`

`unshift()` method ব্যবহার করে Array-এর শুরুতে নতুন element যোগ করা যায়।

```javascript
let fruits = ["Mango", "Banana"];

fruits.unshift("Apple");

console.log(fruits);
```

**Output:**

```text
["Apple", "Mango", "Banana"]
```

---

### 💻 Example — Remove Element with `shift()`

`shift()` method Array-এর প্রথম element remove করে।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

fruits.shift();

console.log(fruits);
```

**Output:**

```text
["Mango", "Banana"]
```

---

### 💻 Example — Find an Element with `includes()`

`includes()` method ব্যবহার করে কোনো element Array-এর মধ্যে আছে কি না check করা যায়।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

console.log(fruits.includes("Mango")); // true
console.log(fruits.includes("Orange")); // false
```

---

### 💻 Example — Find Index with `indexOf()`

`indexOf()` method কোনো element-এর index খুঁজে বের করে।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

console.log(fruits.indexOf("Mango")); // 1
console.log(fruits.indexOf("Orange")); // -1
```

> Element না পাওয়া গেলে `indexOf()` `-1` return করে।

---

### 💻 Example — Loop Through an Array

```javascript
let fruits = ["Apple", "Mango", "Banana"];

for (let i = 0; i < fruits.length; i++) {
  console.log(fruits[i]);
}
```

**Output:**

```text
Apple
Mango
Banana
```

---

### 💻 Example — Loop with `for...of`

`for...of` loop দিয়ে সরাসরি Array-এর value গুলো access করা যায়, index ছাড়াই।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

for (let fruit of fruits) {
  console.log(fruit);
}
```

**Output:**

```text
Apple
Mango
Banana
```

---

### 💻 Example — Loop with `forEach()`

`forEach()` method Array-এর প্রতিটি element-এর উপর একটি function চালায়।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

fruits.forEach(function (fruit, index) {
  console.log(index, fruit);
});
```

**Output:**

```text
0 Apple
1 Mango
2 Banana
```

---

### 💻 Example — Array with Numbers

```javascript
let numbers = [10, 20, 30, 40, 50];

console.log(numbers[0]); // 10
console.log(numbers[3]); // 40
```

---

### 💻 Example — Mixed Data Types

JavaScript Array-তে বিভিন্ন ধরনের data রাখা সম্ভব।

```javascript
let student = ["Arik", 25, true];

console.log(student[0]); // Arik
console.log(student[1]); // 25
console.log(student[2]); // true
```

---

### 💻 Example — Join Array into a String with `join()`

`join()` method Array-এর সব element-কে একটি string-এ convert করে, নির্দিষ্ট separator দিয়ে।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

console.log(fruits.join(", "));
```

**Output:**

```text
Apple, Mango, Banana
```

---

### 💻 Example — Extract Part of an Array with `slice()`

`slice(start, end)` method Array থেকে একটি অংশ copy করে নতুন Array হিসেবে return করে। Original Array পরিবর্তন হয় না।

```javascript
let fruits = ["Apple", "Mango", "Banana", "Orange"];

let citrus = fruits.slice(1, 3);

console.log(citrus);
console.log(fruits);
```

**Output:**

```text
["Mango", "Banana"]
["Apple", "Mango", "Banana", "Orange"]
```

---

### 💻 Example — Add/Remove Elements Anywhere with `splice()`

`splice(start, deleteCount, ...items)` method Array-এর যেকোনো জায়গায় element যোগ বা remove করতে পারে। এটি Original Array পরিবর্তন করে।

```javascript
let fruits = ["Apple", "Mango", "Banana"];

// Remove 1 element from index 1
fruits.splice(1, 1);
console.log(fruits); // ["Apple", "Banana"]

// Add elements at index 1 without removing
fruits.splice(1, 0, "Orange", "Grape");
console.log(fruits); // ["Apple", "Orange", "Grape", "Banana"]
```

---

### 💻 Example — Transform an Array with `map()`

`map()` method প্রতিটি element-এর উপর একটি function চালিয়ে নতুন একটি Array return করে।

```javascript
let numbers = [1, 2, 3, 4];

let doubled = numbers.map(function (num) {
  return num * 2;
});

console.log(doubled);
```

**Output:**

```text
[2, 4, 6, 8]
```

---

### 💻 Example — Filter an Array with `filter()`

`filter()` method একটি condition-এর ভিত্তিতে নতুন Array তৈরি করে, যেখানে শুধু matching element গুলো থাকে।

```javascript
let numbers = [1, 2, 3, 4, 5, 6];

let evenNumbers = numbers.filter(function (num) {
  return num % 2 === 0;
});

console.log(evenNumbers);
```

**Output:**

```text
[2, 4, 6]
```

---

### 💻 Example — Reduce an Array with `reduce()`

`reduce()` method Array-এর সব element-কে একটি single value-তে convert করে।

```javascript
let numbers = [1, 2, 3, 4];

let sum = numbers.reduce(function (total, num) {
  return total + num;
}, 0);

console.log(sum);
```

**Output:**

```text
10
```

---

### 💻 Example — Sort an Array with `sort()`

`sort()` method Array-এর element গুলোকে order করে। Number sort করার সময় compare function ব্যবহার করা জরুরি।

```javascript
let fruits = ["Banana", "Apple", "Mango"];
fruits.sort();
console.log(fruits); // ["Apple", "Banana", "Mango"]

let numbers = [40, 100, 1, 5, 25];
numbers.sort(function (a, b) {
  return a - b;
});
console.log(numbers); // [1, 5, 25, 40, 100]
```

> ⚠️ Compare function ছাড়া `sort()` numbers-কে string হিসেবে sort করে, যা ভুল result দেয় (যেমন: `100` `25`-এর আগে চলে আসে)।

---

### Example — Reverse an Array with `reverse()`

```javascript
let fruits = ["Apple", "Mango", "Banana"];

fruits.reverse();

console.log(fruits);
```

**Output:**

```text
["Banana", "Mango", "Apple"]
```

---

### Example — Check if it's an Array with `Array.isArray()`

```javascript
let fruits = ["Apple", "Mango"];
let name = "Arik";

console.log(Array.isArray(fruits)); // true
console.log(Array.isArray(name)); // false
```

---

### Example — Nested Arrays (Array of Arrays)

```javascript
let matrix = [
  [1, 2, 3],
  [4, 5, 6],
  [7, 8, 9],
];

console.log(matrix[1][2]); // 6
```

> Nested Array-এর element access করতে দুইটা index ব্যবহার করতে হয় প্রথমটা outer Array-এর, দ্বিতীয়টা inner Array-এর।

---

### Common Array Methods

| Method        | Description                                        |
| ------------- | --------------------------------------------------- |
| `push()`      | Adds an element to the end                          |
| `pop()`       | Removes the last element                             |
| `unshift()`   | Adds an element to the beginning                     |
| `shift()`     | Removes the first element                            |
| `includes()`  | Checks whether an element exists                     |
| `indexOf()`   | Finds the index of an element                        |
| `length`      | Returns the number of elements                       |
| `join()`      | Joins all elements into a string                     |
| `slice()`     | Copies a portion of an array (non-destructive)       |
| `splice()`    | Adds/removes elements at any position (destructive)  |
| `map()`       | Creates a new array by transforming each element     |
| `filter()`    | Creates a new array with elements matching a condition |
| `reduce()`    | Reduces the array to a single value                  |
| `sort()`      | Sorts the elements of an array                       |
| `reverse()`   | Reverses the order of elements                       |
| `Array.isArray()` | Checks whether a value is an array                |

---

### ⚠️ Common Mistakes

* Array index `0` থেকে শুরু হয়, `1` থেকে নয়।
* Non-existing index access করলে `undefined` return করে।
* `push()` এবং `unshift()` element যোগ করে।
* `pop()` এবং `shift()` element remove করে।
* `length` হলো মোট element-এর সংখ্যা, শেষ index নয়।
* `indexOf()` element না পেলে `-1` return করে।
* `sort()` compare function ছাড়া ব্যবহার করলে numbers ভুলভাবে sort হয়।
* `slice()` original Array পরিবর্তন করে না, কিন্তু `splice()` করে — এই পার্থক্য মনে রাখা জরুরি।
* `map()`, `filter()`, `reduce()` — এই তিনটা method সবসময় নতুন value/Array return করে, original Array পরিবর্তন করে না।

### 💡 Tips

* একই ধরনের অনেকগুলো value যদি আলাদা আলাদা variable-এ রাখো তাহলে কোড অনেক বড় আর এলোমেলো হয়ে যায়। তার বদলে একটা **Array**-তে সব value একসাথে রাখো কোড ছোট থাকে, আর পরে কাজ করাও সহজ হয়।
* Array শেখার শুরুতে `push()`, `pop()`, `shift()`, `unshift()` এই চারটা method ভালোভাবে practice করো। এগুলো দিয়ে Array-এর শুরুতে বা শেষে element যোগ করা এবং বাদ দেওয়া শেখা যায়, এবং বাকি সব method বোঝার basic এখান থেকেই তৈরি হয়।
* Basic method গুলো আয়ত্ত হয়ে গেলে `map()`, `filter()`, `reduce()` শেখো। এই তিনটা method দিয়ে পুরো Array-এর উপর একবারে কাজ করা যায় যেমন সব element পরিবর্তন করা, নির্দিষ্ট শর্ত অনুযায়ী element বাছাই করা, অথবা সব element মিলিয়ে একটা মাত্র ফলাফল বের করা।
* `slice()` আর `splice()` দেখতে প্রায় একই রকম, কিন্তু কাজ আলাদা। `slice()` শুধু Array-এর একটা অংশের কপি বানায়, original Array তে কোনো পরিবর্তন হয় না। `splice()` সরাসরি original Array-তে element যোগ বা বাদ দেয়। এই পার্থক্যটা মনে রাখা জরুরি নাহলে ভুল জায়গায় ভুল method ব্যবহার হয়ে যেতে পারে।
* যেকোনো নতুন method শেখার পর শুধু পড়ে বা দেখে গেলে বেশিদিন মনে থাকে না। নিজে একটা ছোট example বানিয়ে code editor এ রান করে দেখো  এতে method গুলো কীভাবে কাজ করে তা ভালোভাবে বোঝা যায় এবং মনেও থাকে বেশি দিন।

---
