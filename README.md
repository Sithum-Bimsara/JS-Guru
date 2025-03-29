# Table of Contents
- [Introduction](#Introduction_to_JavaScript)
- [JavaScript_Variables_Constants_and_Primitive_Types](#JavaScript_Variables_Constants_and_Primitive_Types)

# 📖 Introduction_to_JavaScript

## ❓ Frequently Asked Questions about JavaScript

In this document, we'll go over four commonly asked questions about JavaScript, explaining its purpose, capabilities, execution environment, and its relationship with ECMAScript. Along the way, we'll demonstrate JavaScript in action! 🚀

### 1️⃣ What is JavaScript?

JavaScript is one of the most popular programming languages in the world today. It is growing rapidly and is used by major companies like Netflix, Walmart, and PayPal to build internal applications.

💰 The **average salary** of a JavaScript developer in the United States is **$72,000 per year**, making it a great career choice.

👨‍💻 JavaScript developers can work in three main roles:
- **Front-end Developer** (Building user interfaces)
- **Back-end Developer** (Managing server-side logic)
- **Full-stack Developer** (Working on both front-end and back-end)

### 2️⃣ What can you do with JavaScript?

Originally, JavaScript was only used in browsers to create interactive web pages. However, **today JavaScript is much more powerful** thanks to community support and investments by big tech companies like Facebook and Google.

🛠️ With JavaScript, you can build:
- Web and mobile applications 📱
- Real-time applications like chat apps and video streaming services 🎥
- Command-line tools 💻
- Games 🎮

### 3️⃣ Where does JavaScript run?

Originally, JavaScript was designed to run only inside **web browsers**, where each browser has its own JavaScript engine:
- **SpiderMonkey** (Firefox)
- **V8** (Chrome)

In **2009**, Ryan Dahl took Chrome's open-source V8 JavaScript engine and embedded it inside a **C++ program** called **Node.js**. This enabled JavaScript to run **outside of browsers**, allowing developers to build server-side applications.

💡 **JavaScript can now run in two environments:**
- **Inside a web browser** 🖥️
- **In a Node.js runtime** 🏗️

### 4️⃣ What is the difference between JavaScript and ECMAScript?

📜 **ECMAScript** (ES) is just a specification that defines how the JavaScript language should work.

🔹 JavaScript is an implementation of ECMAScript. The **ECMA** organization defines standards for JavaScript.

🗓️ The first version of ECMAScript was released in **1997**. Since **2015**, new versions have been released every year:
- **ES6 (ECMAScript 2015)** introduced major improvements like `let`, `const`, arrow functions, and classes.

---

## 🚀 Let's See JavaScript in Action!

You can run JavaScript directly in your browser using the **Developer Console**.

### Step 1️⃣: Open Chrome Developer Tools
- Right-click on an empty area of a webpage.
- Select **Inspect**.
- Click on the **Console** tab.

### Step 2️⃣: Write JavaScript Code
#### ✅ Printing a Message to the Console
```javascript
console.log('Hello, World!');
```
**Output:**
```
Hello, World!
```
✅ This prints the message "Hello, World!" to the console.

#### ✅ Performing Math Operations
```javascript
2 + 2;
```
**Output:**
```
4
```
✅ JavaScript can be used as a calculator in the console.

#### ✅ Displaying an Alert Box
```javascript
alert('Yo!');
```
**Output:**
🚨 A pop-up alert with the message **"Yo!"** appears on the screen.

---

### 🎯 Conclusion
JavaScript is a powerful and versatile language used for **web development, backend programming, real-time applications, and more**. With ECMAScript defining its standards, JavaScript continues to evolve every year.

----

# JavaScript_Variables_Constants_and_Primitive_Types

## Variables in JavaScript
In JavaScript, variables are used to store data values. There are three ways to declare variables:

### 1. `var` (Function-scoped, can be re-declared and updated)
```js
var name = "Sithum";
console.log(name);
```

### 2. `let` (Block-scoped, can be updated but not re-declared in the same scope)
```js
let firstName = "Sithum";
let lastName = "Bimsara";
console.log(firstName, lastName);
```

### 3. `const` (Block-scoped, cannot be updated or re-declared)
```js
const interestRate = 0.3;
interestRate = 1; // This will throw an error
console.log(interestRate);
```
*Error: Assignment to constant variable.*


**JavaScript has 2 data types:**
* Primitive Types
* Reference Types

## JavaScript Primitive Types
Primitive types are value types in JavaScript. They include:

### 1. String
Used to represent text.
```js
let name = "Mosh"; // String Literal
console.log(typeof name); // "string"
```

### 2. Number
Represents both integer and floating-point numbers.
```js
let age = 30; // Number Literal
console.log(typeof age); // "number"
```

### 3. Boolean
Represents logical values `true` or `false`.
```js
let isApproved = false; // Boolean Literal
console.log(typeof isApproved); // "boolean"
```

### 4. Undefined
A variable that has been declared but not assigned a value.
```js
let firstName;
console.log(firstName); // undefined
console.log(typeof firstName); // "undefined"
```

### 5. Null
Represents an explicitly empty value.
```js
let selectedColor = null;
console.log(selectedColor); // null
console.log(typeof selectedColor); // "object" (this is a historical JavaScript bug)
```

## Summary
| Type      | Example       | Description  |
|-----------|--------------|--------------|
| String    | `"Mosh"`     | Text values  |
| Number    | `30`, `3.14` | Numeric values  |
| Boolean   | `true`, `false` | Logical values |
| Undefined | `let x;`     | No value assigned |
| Null      | `let y = null;` | Empty or unknown value |

This covers the fundamental aspects of variables, constants, and primitive types in JavaScript.

