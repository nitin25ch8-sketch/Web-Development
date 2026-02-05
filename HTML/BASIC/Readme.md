## BASIC HTML ##

### HTML- HyperText Markup Language
- ####  HTML is used for defyining layout of a page.
- ####  CSS is used to add styling in the page.
- ####  Javeseript is wied to program logic for the page.

### Structure of HTML
```html
<!DOCTYPE html> <!-- → specifies it is an html5 document -->
<html> <!-- → root of an HTML page --> 
<head> <!-- → contains page metadata-->
<title>... <title>  <!-- → contains title-->
</head>
<body> <!-- →  The main body of the page (rendered in browser)-->
<h1>..<h1> <!-- → heading tag-->
.
.
.
<h6>..</h6>
<P> </P> <!-- → paragraph tag-->
</body> <!-- → closing body tag-->
</html>  <!-- → closing html tag-->
```

- #### We can either use .htm or .html extension.
### HTML Element
Start tag + Content + End tag
### Comment in HTML
```html
<!-- HTML comment -->
```
### Case Sensitivity
- HTML is a case insensitive language
- ```<H1>``` & ```<h1>``` tags: both are same

### HTML Element
- Everything from starting to the ending tag
```html
<body> <!-- → opening tag -->
<!-- Content -->
</body> <!-- → closing tag -->
```
#### HTML Attributes
It is used to add more information corresponding to an HTML tag.
Example:
```
<a href="www.google.com">Google</a>
```
- a → anchor tag
- href → attribute

### HTML Tags

```<html></html> ``` → Specifies an HTML doc

```<head>``` → Specifies head section of an HTML document

```<title>``` → It is present in head section. Specifies the title of the webpage

```<body>``` → Specifies the main content of an HTML

```<div>``` → It is short for “division”, is a fundamental block-level element used for creating sections or divisions within a webpage

```<span```→ Unlike div, span tag does not start on a new line and only takes up as much width as its content requires

Heading tag ```<h1>–<h6>``` → Used to mark headings in HTML from h1 to h6 (most important to least important)

Paragraph tag ```<p>``` → Used to add paragraph to an HTML page

Anchor tag ```<a>``` → Used to add link to an existing content inside an HTML page

```<img>``` tag

img tag is used to add images in an HTML page

```<img src="image.jpg">``` → relative URL of an image

Bold, Italic & Underline tags
```
<b></b>

<i></i>

<u></u>
```

```<br> ```tag

The br tag is used to create line breaks in an HTML document

- Big & Small tag

We can make the text a bit larger & a bit smaller using big & small tags respectively

```<hr>``` tag

hr tag in HTML is used to create a horizontal ruler, often used to separate the content

#### Subscript & Superscript

We can add subscript & superscripts in HTML as follows:

```<sub></sub>``` → Subscript

```<sup></sup>``` → Superscript

#### Pre tag

HTML always ignores extra spaces & newlines

In order to display a piece of text as it is, we use pre tag
```
<pre>
Nitin is
very good
boy
</pre>
```

Output:
```
Nitin is
very good
boy
```
#### Web Browser

Unlike other programming, HTML doesn’t show output in any compiler

Web browser reads HTML files & determines how to show content with help of HTML tags

Any web browser can be used to open a .html or .htm file & view the results

### Creating a Page Layout

When we use the right tag in right place, it results in a better page layout, better indexing by search engines & better user experience

We use the following tags to get the job done:

```<header>``` → contains nav tag

```<main>```

```<footer>```

Inside the main tag we insert the following tags:

```<main>``` → the main opening tag

```<section>``` → a self page section

```<article>``` → a self contained content

```</main>``` → the main closing tag

```<aside>``` → content aside from the content (eg: Ads etc)

Creating a page like this is not necessary but it creates a readable & structured layout

Also, they are useful for SEO


