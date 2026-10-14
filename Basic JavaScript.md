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

JavaScript is a programming language that makes web pages interactive. While HTML gives structure and CSS gives style, JavaScript gives **behavior**  it decides what happens when a user clicks a button, submits a form, scrolls the page, or interacts in any way.

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



## 8. Functions

### 📖 Definition (বাংলা)
Function হলো একটা code-এর block যেটা একবার লিখে বারবার ব্যবহার করা যায়। কাজ করানোর জন্য function-কে call করতে হয়। এতে code ছোট, পরিষ্কার আর reusable থাকে।

### 📖 Definition (English)
A function is a reusable block of code designed to perform a specific task. It runs only when it is called, and can take inputs (parameters) and give back an output (return value).

### 🍵 Real-life Example
Cha banano-r kotha vabo। Cha banano-r recipe tumi ekbar likhe rakhlay: pani foto → cha-pata dao → chini dao → dud dao → cup-e dhalo। Ekhon jotobar cha khete icche korbe, recipe ta abar notun kore likhte hobe na, shudhu bolbe "cha banao"।

- Recipe ta = **function** (ekbar likhi, bar bar use kori)
- "Cha banao" bola = **function call**
- Chini koto chamoch, dud koto = **parameter / argument** (input)
- Cup-e ready cha = **return value** (output)

```js
function makeTea(sugar, milk) {       // recipe likhlam
  return "Tea with " + sugar + " sugar and " + milk + " milk";
}
console.log(makeTea(2, "full"));      // Tea with 2 sugar and full milk
console.log(makeTea(0, "no"));        // same recipe, notun input
```

### 📋 Function-er Types (List)

| # | Type | Ek line-e | Section |
|---|---|---|---|
| 1 | Function Declaration | `function` keyword + naam, hoisted hoy | 8.1 |
| 2 | Function Expression | function ke variable-e rakha hoy | 8.2 |
| 3 | Arrow Function | short syntax `=>`, ES6 | 8.3 |
| 4 | Anonymous Function | naam nai, shudhu value hishebe use hoy | 8.11 |
| 5 | Named Function Expression | expression-er vitore naam dewa | 8.11 |
| 6 | IIFE | define korar shathe shathe run | 8.10 |
| 7 | Callback Function | onno function-er argument hishebe pathano | 8.9 |
| 8 | Higher-Order Function | function nei ba function ferot dey | 8.12 |
| 9 | Recursive Function | nijeke nijei call kore | 8.13 |
| 10 | Constructor Function | `new` diye object banay | 8.14 |
| 11 | Method | object-er vitorer function | 8.15 |
| 12 | Async Function | `async/await` diye time-newa kaj handle kore | 8.16 |
| 13 | Generator Function | `function*` + `yield`, ek ek kore value dey | 8.17 |

> Parameter, default parameter, rest parameter, return, scope — eigulo function-er **type** na, function-er **feature**; 8.4 theke 8.8 e ache।

---

### 8.1 Function Declaration

```js
// function declaration: function keyword + name + () + { }
function greet(name) {
  // name -> parameter: function-e ja input dewa hoy tar naam
  return "Hello, " + name;   // return: function theke value ferot pathay
}

// function call: argument pass kore function run kora
console.log(greet("Arik"));  // Hello, Arik
```

**Part-wise explanation:**

- `function greet(name)` → function-er naam `greet`, `name` holo parameter।
- `return` → function-er result ferot dey ar function ekhanei shesh hoye jay। return er por kono code run hoy na।
- `greet("Arik")` → function call; `"Arik"` holo argument (parameter-er asol value)।

> 💡 Function declaration **hoisted** hoy — mane function define korar age thekei call kora jay।

```js
sayHi();                 // kaj korbe, karon hoisting
function sayHi() {
  console.log("Hi!");
}
```

---

### 8.2 Function Expression

```js
// function ke variable-er moddhe rakha hoy
const add = function (a, b) {
  return a + b;
};

console.log(add(2, 3));  // 5
```

**Part-wise explanation:**

- Function-ta ekta variable-e store hoy, tai `add(...)` diye call kora hoy।
- Declaration-er moto **hoisted hoy na** — define korar age call korle error dibe।

---

### 8.3 Arrow Function (ES6)

```js
// shortcut syntax: function keyword nai, => use hoy
const multiply = (a, b) => {
  return a * b;
};

// body te shudhu ekta expression thakle { } ar return dorkar nai
const square = (n) => n * n;

// ekta parameter hole () o chhara jay
const double = n => n * 2;

console.log(multiply(2, 3)); // 6
console.log(square(4));      // 16
console.log(double(5));      // 10
```

**Part-wise explanation:**

- `(a, b) => ...` → parameter list, tarpor arrow `=>`, tarpor body।
- Single line body hole `return` automatic hoye jay (implicit return)।
- Arrow function-er nijer `this` thake na — eta bairer scope-er `this` use kore।

---

### 8.4 Parameters ar Arguments

```js
function introduce(name, age) {
  console.log(name + " is " + age + " years old");
}

introduce("Arik", 24);   // Arik is 24 years old
introduce("Arik");       // Arik is undefined years old  (age dewa hoy ni)
```

**Part-wise explanation:**

- Parameter = function define korar somoy naam; Argument = call korar somoy asol value।
- Argument kom dile baki parameter `undefined` hoy। Beshi dile extra gulo ignore hoy (kintu `arguments` object-e thake)।

---

### 8.5 Default Parameters

```js
function greet(name = "Guest") {
  // name na dile "Guest" use hobe
  console.log("Hello, " + name);
}

greet("Arik");  // Hello, Arik
greet();        // Hello, Guest
```

---

### 8.6 Rest Parameters

```js
// ...numbers -> baki shob argument ekta array te joma kore
function sum(...numbers) {
  let total = 0;
  for (let n of numbers) {
    total += n;
  }
  return total;
}

console.log(sum(1, 2, 3, 4)); // 10
```

**Part-wise explanation:**

- `...numbers` → joto khushi argument nite pare, shob ekta array-te chole ashe।
- Rest parameter shobsomoy **shesh parameter** hote hobe।

---

### 8.7 Return Value

```js
function checkAge(age) {
  if (age >= 18) {
    return "Adult";
  }
  return "Minor";     // upore return hole ekhane ar ashbe na
}

console.log(checkAge(20)); // Adult

function noReturn() {
  let x = 5;
}
console.log(noReturn());   // undefined (return na thakle undefined ferot dey)
```

---

### 8.8 Scope (Local vs Global)

```js
let globalVar = "I am global";   // global scope: shob jaygay use kora jay

function test() {
  let localVar = "I am local";   // local scope: shudhu function-er vitore
  console.log(globalVar);        // kaj korbe
  console.log(localVar);         // kaj korbe
}

test();
console.log(localVar);           // ❌ Error: localVar is not defined
```

**Part-wise explanation:**

- Function-er vitore declare kora variable bairer theke dekha jay na।
- Vitor theke bairer (global) variable dekha jay।
- `let` ar `const` **block scope** ({ } er moddhe), `var` **function scope**।

---

### 8.9 Callback Function

```js
// ekta function ke arekta function-er argument hishebe pathano
function processUser(name, callback) {
  console.log("Processing " + name);
  callback();                    // pore ei function ta call hobe
}

function done() {
  console.log("Done!");
}

processUser("Arik", done);
// Processing Arik
// Done!
```

**Part-wise explanation:**

- JavaScript-e function ekta value, tai arekta function-e argument hishebe dewa jay।
- `done` likhlam `()` chhara — karon amra function call korchi na, function ta pass korchi। Call korbe `processUser` nijei।
- Event handling, `setTimeout`, array methods (`map`, `filter`) shob jaygay callback use hoy।

```js
setTimeout(() => {
  console.log("2 second por run holo");
}, 2000);
```

---

### 8.10 IIFE (Immediately Invoked Function Expression)

```js
(function () {
  console.log("Ami shathe shathe run hoyechi!");
})();
```

**Part-wise explanation:**

- Define korar shathe shathei run hoy, ar kokhono call korte hoy na।
- Variable gulo private thake, global scope-e leak hoy na।

---

### 8.11 Anonymous Function ar Named Function Expression

```js
// Anonymous: function-er kono naam nai
setTimeout(function () {
  console.log("Naam chhara function");
}, 1000);

const hello = function () {      // variable-e rakha, kintu function-er nijer naam nai
  console.log("Hello");
};

// Named Function Expression: expression-er vitore naam ache
const factorial = function fact(n) {
  return n <= 1 ? 1 : n * fact(n - 1);   // vitor theke 'fact' naam diye nijeke call
};
console.log(factorial(5));  // 120
```

**Part-wise explanation:**

- **Anonymous function** ekdom shurute naam chhara thake। Callback, event handler, `setTimeout`-e beshi use hoy।
- **Named function expression**-er naam shudhu **function-er vitore** dekha jay, bairer theke na।
- Naam thakle error hole console-e function-er naam dekha jay, tai debug kora shohoj hoy।

---

### 8.12 Higher-Order Function

```js
// 1. Je function onno function ke argument hishebe ney
const numbers = [1, 2, 3, 4, 5];

const doubled = numbers.map((n) => n * 2);          // [2, 4, 6, 8, 10]
const evens = numbers.filter((n) => n % 2 === 0);   // [2, 4]
const total = numbers.reduce((sum, n) => sum + n, 0); // 15

// 2. Je function onno function ke ferot dey
function multiplier(x) {
  return function (y) {
    return x * y;
  };
}

const triple = multiplier(3);   // triple ekhon ekta function
console.log(triple(5));         // 15
```

**Part-wise explanation:**

- Je function **function nei** ba **function ferot dey**, take Higher-Order Function bole।
- `map`, `filter`, `reduce`, `forEach` shob built-in higher-order function।
- `multiplier(3)` ekta notun function ferot dey, jeta pore `y` pele `3 * y` korbe।

---

### 8.13 Recursive Function

```js
function countdown(n) {
  if (n === 0) {              // base case: ekhane thamte hobe
    console.log("Go!");
    return;
  }
  console.log(n);
  countdown(n - 1);           // function nijeke abar call korche
}

countdown(3);  // 3, 2, 1, Go!
```

**Part-wise explanation:**

- Je function **nijeke nijei call kore**, take recursive function bole।
- **Base case** (kokhon thambe) na thakle infinite call hoy, ar `Maximum call stack size exceeded` error ashe।
- Loop diye jeta kora jay, recursion diyeo kora jay; kintu tree/folder-er moto nested jinish-e recursion beshi shohoj।

---

### 8.14 Constructor Function

```js
// naam-er prothom okkhor boro hat dewa hoy (convention)
function Person(name, age) {
  this.name = name;     // this -> je notun object ta banche
  this.age = age;
  this.greet = function () {
    console.log("Hi, I am " + this.name);
  };
}

const p1 = new Person("Arik", 24);   // new keyword lagbei
const p2 = new Person("Rahim", 30);

p1.greet();  // Hi, I am Arik
p2.greet();  // Hi, I am Rahim
```

**Part-wise explanation:**

- Ekoi blueprint theke onek gulo object banate constructor function use hoy।
- `new` na likhle `this` object-e na, shobar upore ba `undefined` hoye jay, tai `new` bhule jeyo na।
- Modern JavaScript-e eta-r jaygay `class` use kora hoy, kintu vitore ei concept-i kaj kore।

---

### 8.15 Method (Object-er vitorer Function)

```js
const user = {
  name: "Arik",
  greet: function () {                // method
    console.log("Hello, " + this.name);
  },
  sayBye() {                          // short syntax
    console.log("Bye, " + this.name);
  },
};

user.greet();   // Hello, Arik
user.sayBye();  // Bye, Arik
```

**Part-wise explanation:**

- Object-er property-r value jodi function hoy, take **method** bole। Array-r `push()`, string-er `toUpperCase()` o method।
- Method-er vitore `this` mane **je object diye method ta call kora hoyeche** (ekhane `user`)।
- Object-er method-e arrow function dio na, karon arrow function-e `this` object-ke point kore na।

---

### 8.16 Async Function

```js
async function getUser() {
  try {
    const res = await fetch("https://jsonplaceholder.typicode.com/users/1");
    const data = await res.json();      // await: result ashar jonno opekkha kore
    console.log(data.name);
  } catch (err) {
    console.log("Error:", err);
  }
}

getUser();
console.log("Ami age print hobo");     // getUser opekkha korar somoy baki code cholte thake
```

**Part-wise explanation:**

- `async` function shobsomoy ekta **Promise** ferot dey।
- `await` shudhu `async` function-er vitore use kora jay; eta result na ashe porjonto oi function-ke opekkha koray, kintu pura page-ke atkay na।
- Server theke data ana, file read kora-r moto **somoy-newa** kaje use hoy। Error dhorar jonno `try...catch` lagao।
- Arrow-o async hote pare: `const fn = async () => { ... }`।

---

### 8.17 Generator Function

```js
function* numberGenerator() {
  yield 1;      // ekhane pause kore 1 dey
  yield 2;
  yield 3;
}

const gen = numberGenerator();
console.log(gen.next());  // { value: 1, done: false }
console.log(gen.next());  // { value: 2, done: false }
console.log(gen.next());  // { value: 3, done: false }
console.log(gen.next());  // { value: undefined, done: true }
```

**Part-wise explanation:**

- `function*` (star shoho) likhle generator hoy। `yield` e function pause hoy ar value dey।
- `next()` call korle porer `yield` porjonto cholte thake।
- Beshi use hoy na, kintu lomba/infinite list, step-by-step kaj-e kaje lage। Shurute eta bujhte na parle skip kore porer topic-e jete paro।

---

### ⚠️ Common Mistakes

- Function call korar somoy `()` dite bhule jawa — `greet` likhle function run hoy na, `greet()` likhte hobe।
- `return` er pore code likhe fela — oi code kokhono run hobe na।
- Function-er vitorer variable bairer theke use korte jawa — scope error dey।
- Function expression-ke define korar age call kora — hoisting hoy na, error dey।
- Callback pass korar somoy `done()` likhe fela — eta shathe shathe call kore dey, `done` likhte hobe।
- Arrow function-e `{ }` dile `return` na likhle `undefined` ferot ashe।

### 💡 Tip
Ekta function-e ekta kaj-i rakho — chhoto, clear naam dao (`getUser`, `calculateTotal`)। Simple kaj hole arrow function, hoisting lagle declaration, ar callback-e arrow function use koro। Default parameter use korle `undefined` error onek kome jay।

---
---

## 9. DOM (Document Object Model)

### 📖 Definition (বাংলা)
DOM-এর full form Document Object Model। আমরা যখন একটা HTML file লিখি, browser সেটা সরাসরি screen-এ দেখায় না। আগে browser পুরো HTML পড়ে একটা tree-এর মতো structure বানায়, যেখানে প্রতিটা tag (h1, p, button, img...) একটা করে object (node) হয়ে যায়। এই tree-টাকেই DOM বলে।

JavaScript এই object গুলোর সাথে কথা বলতে পারে। তাই JS দিয়ে page-এর যেকোনো অংশ পড়া (read), বদলানো (change), নতুন কিছু যোগ করা (add) বা মুছে ফেলা (remove) যায় — page reload ছাড়াই।

সহজ কথায়: **HTML = page-এর নকশা, DOM = সেই নকশা থেকে browser-এর বানানো জীবন্ত (live) রূপ, আর JavaScript = সেই রূপ বদলানোর রিমোট কন্ট্রোল।**

### 📖 Definition (English)
The DOM (Document Object Model) is a programming interface that the browser builds from your HTML. It represents the page as a tree of objects called nodes, where every tag, attribute, and piece of text becomes a node. JavaScript can read and change these nodes to update the content, structure, and style of the page instantly, without reloading it.

```
document
 └── html
      ├── head
      │    └── title
      └── body
           ├── h1
           └── p
```

---

### 🏠 Real-life Story — Bari, Noksha ar Electrician

Dhoro, Arik ekta bari-r **noksha (blueprint)** aanklo: "ekta bari, tar vitore 2ta room, proti room-e ekta kore batti।"

- **Noksha = HTML file।** Eta shudhu kagoje lekha plan।
- Contractor (**browser**) noksha dekhe **asol bari** baniye felo। Eta holo **DOM।** Ekhon room, deyal, batti shob asol jinish, ar tader moddhe sompork ache: bari → room → batti। Thik family tree-r moto (parent, child, sibling)।
- Ekhon batti jalate ba deyal-e rong korte hole noksha-r kagoje kichu likhle kichu hobe na, **bari-te giye kaj korte hobe।** Ei "bari-te giye kaj kora" holo **JavaScript।**

| Bari-te ja kora hoy | DOM-e JS-er kaj |
|---|---|
| "2 number room-er batti ta khuje ber kora" | `getElementById` / `querySelector` |
| "Batti-r rong bodlano, nameplate bodlano" | `style`, `textContent`, `classList` |
| "Notun room baniye bari-r sathe jora lagano" | `createElement` + `appendChild` |
| "Room ta bhenge fela" | `remove()` |

**Ekta important kotha:** JS diye change korle noksha (HTML file) ager moto-i thake, shudhu asol bari (page) bodlay। Tai page **reload** korle browser abar noksha theke notun bari baniye felbe, ar tomar JS-er kora change gulo **hariye jabe।**

**Web-er real example:** Facebook-e Like dile count 1 bere jay, kintu page reload hoy na। Ota DOM change: JS ei like count-er text ta khuje ber kore bodle dey।

```js
// noksha (HTML): <button id="like">Like</button> <span id="count">0</span>
const count = document.querySelector("#count");   // bari-te batti khuje paoa
count.textContent = 1;                            // batti-r rong bodlano (text change)
```

---

### 9.1 Element Select kora

```html
<h1 id="title">Hello</h1>
<p class="text">First</p>
<p class="text">Second</p>
```

```js
// id diye ekta element
const title = document.getElementById("title");

// CSS selector diye prothom match howa element
const firstText = document.querySelector(".text");

// CSS selector diye shob match howa element (NodeList)
const allTexts = document.querySelectorAll(".text");

// class / tag name diye (HTMLCollection)
const byClass = document.getElementsByClassName("text");
const byTag = document.getElementsByTagName("p");

console.log(title, firstText, allTexts.length);
```

**Part-wise explanation:**

- `getElementById` → id diye ekta element dey; na pele `null`।
- `querySelector` → CSS-er moto selector (`#id`, `.class`, `tag`) use kore **prothom** ta dey।
- `querySelectorAll` → **shob** match howa element dey; `forEach` diye loop kora jay।
- Modern code-e shobcheye beshi `querySelector` / `querySelectorAll` use hoy।

---

### 9.2 Text ar HTML Change kora

```js
const title = document.querySelector("#title");

title.textContent = "New Title";            // shudhu text, safe
title.innerHTML = "<span>Bold</span> Text"; // HTML shoho
title.innerText = "Visible text";           // CSS-e visible text
```

**Part-wise explanation:**

- `textContent` → plain text set kore; HTML tag hole text hishebe dekhay, tai safe।
- `innerHTML` → HTML parse kore। **User-er dewa input kokhono innerHTML-e dio na** (XSS risk)।
- `innerText` → shudhu screen-e visible text dhore, CSS (`display: none`) mane।

---

### 9.3 Style Change kora

```js
const box = document.querySelector(".box");

box.style.color = "red";
box.style.backgroundColor = "yellow";   // background-color -> camelCase
box.style.fontSize = "20px";
```

**Part-wise explanation:**

- CSS property-te `-` thake, JS-e seta camelCase hoy: `background-color` → `backgroundColor`।
- Value shobsomoy string hoy, unit shoho (`"20px"`)।
- `style` shudhu **inline style** change kore।

---

### 9.4 classList

```js
const box = document.querySelector(".box");

box.classList.add("active");        // class add
box.classList.remove("active");     // class remove
box.classList.toggle("active");     // thakle remove, na thakle add
console.log(box.classList.contains("active")); // true / false
```

**Part-wise explanation:**

- Beshi style change korte hole CSS-e class banay, JS diye shudhu class on/off kora best practice।
- `toggle` dark mode, menu open/close-er moto jaygay khub kaje lage।

---

### 9.4.1 Attribute

```js
const link = document.querySelector("a");

console.log(link.getAttribute("href"));
link.setAttribute("href", "https://example.com");
link.removeAttribute("target");
console.log(link.hasAttribute("href")); // true

const img = document.querySelector("img");
img.src = "photo.jpg";   // direct property diyeo kora jay
img.alt = "My photo";
```

---

### 9.5 Notun Element Create, Add ar Remove

```js
// 1. element banano
const li = document.createElement("li");

// 2. text / content dewa
li.textContent = "New item";
li.classList.add("item");

// 3. page-e add kora
const ul = document.querySelector("ul");
ul.appendChild(li);        // shesh e
ul.prepend(li);            // shurute (li ta move hobe, copy na)
ul.append("text", li);     // ekshathe onek ta (text-o dewa jay)

// 4. remove kora
li.remove();               // element nijei nijeke remove kore
ul.removeChild(li);        // parent theke child remove

// 5. copy kora
const copy = li.cloneNode(true);  // true = vitorer shob shoho
```

**Part-wise explanation:**

- `createElement` shudhu memory-te element banay, page-e add na korle dekha jabe na।
- `appendChild` / `append` / `prepend` diye page-e boshano hoy।
- Ekta element ekshathe duita jaygay thakte pare na; ager jayga theke move hoy। Duplicate lagle `cloneNode(true)` use koro।

---

### 9.6 insertAdjacentHTML

```js
const list = document.querySelector("ul");

list.insertAdjacentHTML("beforeend", "<li>Item 4</li>");
// 'beforebegin' -> element-er age (bairey)
// 'afterbegin'  -> element-er vitore, shurute
// 'beforeend'   -> element-er vitore, shesh e
// 'afterend'    -> element-er pore (bairey)
```

---

### 9.7 DOM Traversing (Parent, Child, Sibling)

```js
const ul = document.querySelector("ul");

ul.parentElement;          // parent
ul.children;               // shob child element (HTMLCollection)
ul.firstElementChild;      // prothom child
ul.lastElementChild;       // shesh child

const li = document.querySelector("li");
li.nextElementSibling;     // porer bhai
li.previousElementSibling; // ager bhai

li.closest("ul");          // upore-r dike shobcheye kachher match howa element
```

**Part-wise explanation:**

- `...Element...` wala property gulo shudhu element dey, text/whitespace node dey na — tai eta use kora bhalo।
- `closest()` event delegation-e khub kaje lage।

---

### 9.8 Input-er Value Neowa

```js
const input = document.querySelector("#name");

console.log(input.value);   // user ja likhechhe (shobsomoy string)
input.value = "";           // input khali kora

const checkbox = document.querySelector("#agree");
console.log(checkbox.checked); // true / false
```

---

### 9.9 Practical Example

```html
<h1 id="counter">0</h1>
<button id="btn">+1</button>
```

```js
const counter = document.querySelector("#counter");
const btn = document.querySelector("#btn");

let count = 0;

btn.addEventListener("click", () => {
  count++;                          // count barao
  counter.textContent = count;      // page-e update koro
});
```

---

### ⚠️ Common Mistakes

- `<script>` tag `<body>`-er shurute dile element pawa jay na (`null` ashe) — script `</body>`-er thik age dao, ba `defer` use koro।
- `querySelector`-e `.` ba `#` dite bhule jawa — `querySelector("title")` tag khoje, id na।
- `querySelectorAll` er result e direct style dewa — age loop korte hobe: `all.forEach(el => ...)`।
- `innerHTML`-e user input boshano — security risk (XSS)।
- `input.value` ke number vabe — eta string, `Number(input.value)` kore nao।
- `background-color` likhe style dewa — JS-e `backgroundColor` hobe।
- `getElementById("#title")` — eikhane `#` dite hoy na।
- `null`-er upor property access kora — element nai hole `Cannot read properties of null` error ashe।

### 💡 Tip
Prothome `querySelector` / `querySelectorAll` shikho, shob jaygay kaje lagbe। Style change-er jonno `classList` use koro, inline style na। Text-er jonno `textContent`, shudhu trusted HTML-er jonno `innerHTML`। Browser-er DevTools (F12 → Elements tab) e DOM tree live dekha jay, practice-er jonno khub helpful।

---
---

## 10. Events

### 📖 Definition (বাংলা)
Event মানে ঘটনা। Browser-এর page-এ প্রতি মুহূর্তে অনেক কিছু ঘটে — user button-এ click করে, keyboard-এ কিছু type করে, mouse নাড়ায়, form submit করে, page scroll করে, এমনকি page load হওয়াও একটা ঘটনা। এই ঘটনাগুলোকেই event বলে।

Browser এই ঘটনাগুলো নিজে থেকেই টের পায়। কিন্তু ঘটনা ঘটলে **কী করতে হবে** সেটা আমরা JavaScript দিয়ে ঠিক করে দিই। এটাকে বলে event handling।

Event handling-এর ৩টা অংশ:
1. **Event** — যা ঘটলো (যেমন click)
2. **Event Listener** — যে ঘটনার জন্য কান পেতে অপেক্ষা করে (`addEventListener`)
3. **Event Handler** — ঘটনা ঘটলে যে function চলে

### 📖 Definition (English)
An event is something that happens in the browser, such as a click, a key press, a form submission, or a page load. The browser detects these automatically, and we use JavaScript to attach an event listener to an element so that a handler function runs whenever that event occurs. This is what makes a web page interactive.

---

### 🔔 Real-life Story — Doorbell

Tumi ghore boshe ache, ar bairer dorjay ekta **doorbell** ache।

- Keu bell chaple = **Event** (jemon `click`)
- Tumi kan pete ache, bell bajle shunbe = **Event Listener** (`addEventListener`)। Bell na baja porjonto tumi kichui korcho na, shudhu "opekkha" korcho।
- Bell shune uthe giye dorja khulle = **Event Handler** (function)। Bell jotobar bajbe, totobar ei kaj hobe।
- Keu ashche ta dekhe kon manush (bondhu na delivery man) bujhle = **Event Object** (`event.target`, `event.key`...), mane ghotonar details।
- Alada bell alada kaj: dorjar bell (click), phone-er ring (aro ekta event) — kon ghotona-y ki korbe ta tumi alada kore thik koro।

| Doorbell story | JavaScript |
|---|---|
| Doorbell | Button / element |
| Bell chapa | `click` event |
| Kan pete thaka | `addEventListener` |
| Dorja khola | handler function |
| Ke eshechhe tar info | event object (`e`) |

**Web-er real example:** Like button-e click korle count barhe, menu icon-e click korle menu khole, form-e Enter chaple data jay — shob jaygay "keu kichu korlo, tai kichu hoilo", mane event + handler।

```js
const bell = document.querySelector("#doorbell");        // doorbell (button)

bell.addEventListener("click", (e) => {                  // kan pete thaka: click shunbo
  console.log("Ding dong! Dorja kholo 🚪");              // bell bajle ei kaj
  console.log("Ke click korlo:", e.target);              // ghotonar details
});
```

---

### 10.1 addEventListener

```js
const btn = document.querySelector("#btn");

// element.addEventListener("event-naam", handlerFunction)
btn.addEventListener("click", function () {
  console.log("Button clicked!");
});

// arrow function diyeo kora jay
btn.addEventListener("click", () => {
  console.log("Clicked again!");
});
```

**Part-wise explanation:**

- 1st argument → event-er naam (string), `"on"` chhara (`"click"`, `"onclick"` na)।
- 2nd argument → handler function; event hole ei function run hoy।
- Ekta element-e ekoi event-e **onek gulo** listener lagano jay।

> Ager style `btn.onclick = function() {...}` — eta e ekta-i handler thake, porer ta ager tare replace kore dey। Tai `addEventListener` better।

---

### 10.2 Common Events

| Event | Kokhon hoy |
|---|---|
| `click` | element-e click korle |
| `dblclick` | double click korle |
| `mouseover` / `mouseout` | mouse upore ashle / chole gele |
| `keydown` / `keyup` | key chaple / chhare dile |
| `input` | input-e value change hole (proti character e) |
| `change` | value change hoye focus chole gele (select, checkbox) |
| `submit` | form submit hole |
| `focus` / `blur` | input-e focus hole / focus chole gele |
| `scroll` | scroll korle |
| `resize` | window size change hole |
| `DOMContentLoaded` | HTML load shesh hole |
| `load` | page + image shob load shesh hole |

```js
const input = document.querySelector("#name");

input.addEventListener("input", () => {
  console.log("Typing:", input.value);
});

document.addEventListener("keydown", (e) => {
  console.log("Key pressed:", e.key);
});

document.addEventListener("DOMContentLoaded", () => {
  console.log("DOM ready!");
});
```

---

### 10.3 Event Object

```js
btn.addEventListener("click", (event) => {
  // event -> browser automatic pathay, event-er shob information thake
  console.log(event.type);      // "click"
  console.log(event.target);    // je element-e click hoyeche
  console.log(event.currentTarget); // je element-e listener lagano
  console.log(event.clientX, event.clientY); // mouse-er position
});

input.addEventListener("keydown", (e) => {
  console.log(e.key);    // "a", "Enter", "Escape"
  console.log(e.code);   // "KeyA", "Enter"
  if (e.key === "Enter") {
    console.log("Enter chapa hoyeche");
  }
});
```

**Part-wise explanation:**

- Handler function-er prothom parameter-i event object (naam `e`, `event`, `evt` jekono hote pare)।
- `event.target` → je element theke event shuru hoyeche।
- `event.currentTarget` → je element-e listener lagano ache।

---

### 10.4 preventDefault()

```js
const form = document.querySelector("form");

form.addEventListener("submit", (e) => {
  e.preventDefault();     // browser-er default kaj (page reload) bondho kore
  console.log("Form submit hoyeche, kintu page reload hoy ni");
});

const link = document.querySelector("a");
link.addEventListener("click", (e) => {
  e.preventDefault();     // link-e gele na
});
```

**Part-wise explanation:**

- Form submit korle browser by default page reload kore, link-e click korle onno page-e jay। `preventDefault()` eta thamay।
- JS diye form validate ba data pathate hole eta lagbei।

---

### 10.5 Event Bubbling ar Capturing

```html
<div id="parent">
  <button id="child">Click</button>
</div>
```

```js
document.querySelector("#parent").addEventListener("click", () => {
  console.log("Parent clicked");
});

document.querySelector("#child").addEventListener("click", () => {
  console.log("Child clicked");
});

// button-e click korle output:
// Child clicked
// Parent clicked    <- event upore (parent-er dike) uthe jay: eta bubbling
```

**Part-wise explanation:**

- **Bubbling** (default): event prothome je element-e hoyeche tate run hoy, tarpor ek ek kore parent-er dike uthe jay।
- **Capturing**: ulta, upor theke niche. Use korte hole 3rd argument `true` dite hoy: `addEventListener("click", fn, true)`।
- `e.stopPropagation()` diye event-er upore uthha bondho kora jay।

```js
document.querySelector("#child").addEventListener("click", (e) => {
  e.stopPropagation();   // parent-er handler ar run hobe na
  console.log("Child clicked");
});
```

---

### 10.6 Event Delegation

```html
<ul id="list">
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

```js
const list = document.querySelector("#list");

// proti li-te alada listener na diye parent-e ekta-i listener
list.addEventListener("click", (e) => {
  if (e.target.tagName === "LI") {
    console.log("Clicked:", e.target.textContent);
    e.target.classList.toggle("done");
  }
});

// pore notun li add korleo kaj korbe
const newLi = document.createElement("li");
newLi.textContent = "Item 4";
list.appendChild(newLi);
```

**Part-wise explanation:**

- Bubbling-er subidha niye parent-e ekta listener lagiye `event.target` diye bujha jay kon child-e click hoyeche।
- Fayda: kom memory, ar **pore add kora element-eo** automatic kaj kore (todo list-e khub lage)।
- Child-er vitore aro element thakle `e.target.closest("li")` use koro।

---

### 10.7 removeEventListener

```js
function handleClick() {
  console.log("Clicked");
}

btn.addEventListener("click", handleClick);
btn.removeEventListener("click", handleClick);  // same function reference lagbe
```

**Part-wise explanation:**

- Remove korte hole **same function** pass korte hobe। Anonymous / arrow function diye add korle remove kora jay na, tai naam dewa function use koro।

---

### 10.8 Listener Options

```js
btn.addEventListener("click", () => {
  console.log("Shudhu ekbar run hobe");
}, { once: true });   // ekbar run hoye nijei remove hoye jay
```

---

### 10.9 Practical Example — Todo List

```html
<form id="todo-form">
  <input type="text" id="todo-input" placeholder="Add a task" />
  <button type="submit">Add</button>
</form>
<ul id="todo-list"></ul>
```

```js
const form = document.querySelector("#todo-form");
const input = document.querySelector("#todo-input");
const list = document.querySelector("#todo-list");

// 1. form submit hole notun task add
form.addEventListener("submit", (e) => {
  e.preventDefault();                  // page reload bondho

  const text = input.value.trim();     // age-pore space fele dao
  if (text === "") return;             // khali hole kichu korbe na

  const li = document.createElement("li");
  li.textContent = text;
  list.appendChild(li);

  input.value = "";                    // input khali koro
});

// 2. event delegation: li-te click korle done / undone
list.addEventListener("click", (e) => {
  if (e.target.tagName === "LI") {
    e.target.classList.toggle("done");
  }
});
```

---

### ⚠️ Common Mistakes

- `addEventListener("onclick", ...)` likhe fela — `"click"` hobe, `"on"` chhara।
- Handler-e `fn()` likhe fela — eta shathe shathe call kore dey; `fn` likhte hobe (`btn.addEventListener("click", fn)`)।
- Form-e `preventDefault()` na dewa — page reload hoye data hariye jay।
- Anonymous function diye listener add kore pore `removeEventListener` korte chawa — kaj korbe na।
- `querySelectorAll` er result-e direct `addEventListener` dewa — loop korte hobe।
- Arrow function-e `this` use kora — arrow function-e `this` element hoy na; `e.currentTarget` use koro।
- `e.stopPropagation()` jaygay-onujayi na bujhe use kora — onno listener bondho hoye jete pare।
- `input` ar `change` event-er difference na bojha — `input` proti character-e, `change` focus hariye gele।

### 💡 Tip
Notun listener lagate hole shobsomoy `addEventListener` use koro। Form-er jonno `submit` event-e `preventDefault()` mone rakho। List-er moto jaygay (jekhane element pore add hoy) **event delegation** use koro। Kono event-er details bujhte `console.log(e)` kore dekho, browser-er console-e shob property dekha jabe।
