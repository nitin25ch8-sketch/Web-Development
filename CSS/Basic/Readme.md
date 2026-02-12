# CSS (Cascading Style Sheets)
CSS stands fo **Cascading Style Sheets** . It is a stylesheet language used to style and enhance website presentation. CSS is one of the three main components of a webpage, along with HTML and JavaScript.

### Why CSS?

CSS is a highly demanded skill in web development.    
If you master CSS, you can customize your website according to your liking.

### Basic Example of CSS
```css 
body {
    background-color: red;
}
```

➡ This will make the webpage background red.

##  DOM (Document Object Model)

- DOM stands for Document Object Model.

- When a page is loaded, the browser creates a DOM of the page.   
The DOM is constructed as a tree of objects.

## HTML ID & Class Attribute
### ID

When an HTML element is given an id, it serves as a unique identifier.   
Each element must have a unique id (if assigned).

### Class

When an HTML element is given a class, it belongs to that class.  
Multiple elements can belong to the same class.

#### Multiple Classes Example
```css
<div id="first" class="C1 C2 C3">
</div>
```

- Multiple classes are separated by spaces.

- ID must be unique.

### Three Ways to Add CSS to HTML

- Internal CSS – Using ```<style>``` tag inside HTML.

- Inline CSS – Using style attribute inside an element.

- External CSS – Linking a .css file using ```<link>``` tag.

### CSS Selectors

A CSS selector is used to select HTML element(s) for styling.

Example:
```css
body {
    color: red;
    background: pink;
}
```
- color and background are properties.  
red and pink are values.  
property: value; is called a declaration.

### Element Selector

Selects elements based on tag name.

Example:
```css
h2 {
    color: blue;
}
```
### ID Selector

Selects element with a specific ID.

Example:
```css
#red {
    background: red;
}
```
### Class Selector

Selects elements with a specific class.

Example:
```css
.red {
    background: red;
}
```
## Important Notes
### 1. Grouping Selectors
```css
h1, h2, h3, div {
    color: blue;
}
```

➡ h1, h2, h3, and div will all be blue.

### 2. Element.Class Selector
```css
p.red {
    color: red;
}
```

➡ All paragraphs with class "red" will get red color.

### 3. Universal Selector
```css
* {
    margin: 0;
    padding: 0;
}
```

➡ Selects all elements.

### 4. Priority Rule

Inline styles override internal and external styles.