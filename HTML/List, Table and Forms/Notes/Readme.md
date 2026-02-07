# HTML Lists, Tables, and Forms

This document covers the basics of **HTML Lists, Tables, Forms, and Video Embedding** with syntax and examples.

---

## 📌 HTML Lists

Lists are used to display content that represents a collection of items.

---

### 🔹 Unordered List

Used to list unordered items (bulleted list).

**Syntax:**
```html
<ul>
  <li>Home</li>
  <li>About</li>
</ul>
```
### 🔸 Ordered List

Used to list ordered items (numbers, letters, Roman numerals).

**Syntax:**
```html
<ol>
  <li>Pen</li>
  <li>Pencil</li>
  <li>Eraser</li>
  <li>Copy</li>
</ol>
```
### 🔸 Types of Ordered Lists
```html 
<ol type="1">   <!-- Default -->
<ol type="A">   <!-- A, B, C -->
<ol type="a">   <!-- a, b, c -->
<ol type="I">   <!-- I, II, III -->
<ol type="i">   <!-- i, ii, iii -->
```

Example:
```html
<ol type="A">
  <li>HTML</li>
  <li>CSS</li>
</ol>
```
### 🔸 Reversed Ordered List

Displays list in reverse order.
```html
<ol reversed>
  <li>First</li>
  <li>Second</li>
  <li>Third</li>
</ol>
```

### 🔸 Control List Counting

Used to change the starting number of an ordered list.
```html
<ol start="5">
  <li>Java</li>
  <li>Python</li>
</ol>
```

### 🔸 Nested Ordered List (Sub-list)
```html
<ol>
  <li>JavaScript
    <ol>
      <li>React</li>
      <li>Node</li>
    </ol>
  </li>
  <li>Python
    <ol>
      <li>Django</li>
      <li>Flask</li>
    </ol>
  </li>
</ol>
```

## 📊 HTML Tables

The <table> tag is used to format and display tabular data.

### 🔹 Table Tags
```html
<tr> → Table row

<td> → Table data

<th> → Table header

Basic Table Example:

<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Nitin</td>
    <td>21</td>
  </tr>
</table>
```
### 🔹 Table Caption

Used to add a title to the table.
```html
<table>
  <caption>Student Details</caption>
</table>
```
### 🔹 Table Sections
```
<thead> → Table head

<tbody> → Table body
```
```html
<table>
  <thead>
    <tr><th>Name</th><th>Marks</th></tr>
  </thead>
  <tbody>
    <tr><td>Aman</td><td>90</td></tr>
  </tbody>
</table>
```
### 🔹 Colspan Attribute

Used to merge columns.
```html
<th colspan="3">Student Info</th>
```

This spans 3 columns.

## 📝 HTML Forms

HTML forms are used to collect user input.


### 🔹 Syntax
```html
<form>
  <!-- form elements -->
</form>
```
### 🔹 Input Elements
```
text

checkbox

radio

button

submit

file
```
```html
<input type="text" placeholder="Enter name">
<input type="radio"> Male
<input type="checkbox"> Agree
```

### 🔹 Textarea Element

Used for multi-line text input.
```html
<textarea rows="4" cols="30"></textarea>
```
### 🔹 Select Element

Defines a dropdown list.
```html
<select>
  <option>India</option>
  <option>USA</option>
</select>
```
## 🎥 Embedding Videos in HTML

The <video> tag is used to play videos.
```html
<video src="video.mp4" controls>
  Error
</video>
```
### 🔹 Video Attributes
```
controls

autoplay

loop

width
```
```html
<video src="demo.mp4" controls autoplay loop width="300"></video>
```
