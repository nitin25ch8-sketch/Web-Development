📄 **Javascript (Introduction, Data Types, Variables)** 

---

# JAVASCRIPT

* JavaScript is a programming language used to create dynamic content for websites.
* It is a light-weight, cross-platform, and single-threaded programming language.
* It is an interpreted language that executes code line by line, providing more flexibility.
* JavaScript is a Client-Side language.
* On client side, JavaScript works along with HTML & CSS. JavaScript on client side is directly executed in the user’s browser.
* JavaScript is a single-threaded language that executes one task at a time.
* It is an interpreted language which means it executes the code line by line.
* The data type of the variable is decided at run-time in JavaScript, which is why it is called dynamically typed.

### Eg Code:

```javascript
console.log("Hello, World");
```

Output: Hello, World → at console in Web browser

---

# Comments in JavaScript

### Single-line comment

```javascript
// Single line comment
```

### Multi-line comment

```javascript
/* 
   Multi
   line
   comment 
*/
```

---

# Key Features of JavaScript

### 1. Versatile

* Can be used for a wide range of tasks from simple calculations to complex server-side applications.

### 2. Client-Side Scripting

* JavaScript runs on the user’s browser, so has a faster response time without needing to communicate with the server.

### 3. Event-Driven

* Responds to user actions (clicks, keystrokes) in real time.

### 4. Asynchronous

* Can handle tasks like fetching data from servers without freezing the user interface.

### 5. Rich Ecosystem

* There are numerous libraries & frameworks built on JavaScript such as React, Angular & Vue.js which make development faster & more efficient.

---

# Client-Side vs Server-Side

## Client-Side

* Involves controlling the browser and its DOM (Document Object Model).
* Handles events like clicks & form inputs.
* Common libraries include AngularJS, ReactJS & VueJS.

## Server-Side

* Involves interacting with databases, manipulating files & generating responses.
* Node.js & framework like Express.js are widely used for server-side JavaScript, enabling full stack development.

---

# Data Types in JavaScript

## Primitive Data Types

### Numeric Type

* Number
* BigInt

### Non-Numeric Type

* String
* Boolean
* Null
* Undefined
* Symbol

---

## Number

Represents numeric value (integers & decimal both)

```javascript
let n = 42;
let pi = 3.14;
```

---

## BigInt

Represents integers larger than Number.MAX_SAFE_INTEGER

```javascript
let bigNumber = 123456789012345678901234567890n;
```

---

## String

Represents text enclosed in single or double quotes.

```javascript
let s = "Hello, World";
```

---

## Boolean

Represents a logical value (true or false)

```javascript
let bool = true;
```

---

## Undefined

A variable that has been declared but not assigned a value.

```javascript
let notAssigned;
```

---

## Null

Represents an intentional absence of any value.

```javascript
let empty = null;
```

---

## Symbol

Represents unique & immutable values often used as object keys.

---

# Non-Primitive Data Types

## 1. Objects

Represents key-value pair.

```javascript
let obj = {
   name: "Ankit",
   age: 21
};
```

---

## 2. Array

Represents an ordered list of values.

```javascript
let a = ["red", "green", "blue"];
```

---

## 3. Function

Represents reusable block of code.

```javascript
function func() {
   console.log("Nitin");
}
```

---

# JavaScript Operators

### Ternary Operator

```javascript
condition ? exp1 : exp2
```

### Arithmetic Operators

```
+, -, /, %, *
```

### Logical Operators

```
&&, ||, !
```

### Unary Operators

```
+, -, ++, --
typeof, delete, void
```

### BigInt Operators

```
+, -, /, %
Example: 10n + 20n
```

### Comma Operator

```javascript
let x = (1,2);   // assigns 2 to x
```

### Comparison Operators

```
==, !=, ===, !==
```

### Bitwise Operators

```
&, |, ^, ~, <<, >>, >>> 
```

### Relational Operators

```
<, >, <=, >=, in, instanceof
```

### Assignment Operators

```
=, +=, -=, *=, /=, %= 
```

---

# JavaScript Variables

Variables in JavaScript are used to store data values.

### Note:

1. Variable can be declared using var, let or const (mostly let & const is used).
2. JavaScript is dynamically typed, so types are declared at runtime.
3. You don’t need to specify a data type when creating a variable.

### Example:

```javascript
var a = 20;      // old style
let b = 30;      // preferred for non-const
const c = 30;    // preferred for const (cannot be changed)
```

---

# Declaring Variables

* Variables were declared only with var before ES6 (2015), which is function-scoped & global-scoped causing issues like hoisting & global pollution.
* let & const are block-scoped (limited to { } block) reducing errors compared to var.

---

# Rules for Naming Variables

* Variables must start with letter (A–Z), underscore (_) or dollar sign ($).
* Subsequent characters can be letters, numbers, underscore or dollar sign.
* Variable names are case-sensitive.
* Reserved keywords (cannot be used) such as function, new, object, etc.

---



