# Introduction to HTML


> ## Contents

**[Basics](#basics)**<br>
**[What does HTML look like?](#HTMLlooklike)**<br>
**[Writing a new HTML](#WritinganewHTML)**<br>
**[Intro to Lists and Comments](#lists)**<br>

<a name="basics"></a>
> ## Basics

What is HTML? HTML is an acronym that stands for Hypertext Markup Language. It's a standard markup language used to create web pages.
It tells your browser how to render web pages. A markup language is a language designed for processing the presentation of the text. You markup your text with tags and browser interprets those tags to display the text. 

<a name="HTMLlooklike"></a>
> ## What does HTML look like?

HTML uses tags and elements to encode different parts of the content.
For example, you want to represent some text and you want that text to be represented as a paragraph of it's own.

```html
<p>Hello, World!</p>
```
You are marking up regular text with tags into these elements. The browser then interprets these elements to show you what you are used to on a web page.

Boilerplate HTML code:

```html
<!DOCTYPE html> # informs the browser that the document type is HTML
<html> # wraps all the content
  <head> # put content here that shouldn't be shown to visitors, for example, link to style sheets or Javascript files
    <meta charset="utf-8"> # sets the character set, usually set to utf-8 which includes most characters in any language 
    <title>Your title here</title> # title of the page, shows up in the tab of the browser
  </head>
  <body> # contains all the content you want to show the visitors
  </body>
</html>
```
<a name="WritinganewHTML"></a>
> ## Writing our first HTML

Open up jsbin.com and type up in the following HTML code.

```
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
</head>
<body>
<h1>Header 1</h1>
<h2>Header 2</h2>
<p>Hello, <strong>World!</strong> or <em>World!</em></p>
</body>
</html>
```

You have six different types of headers starting from h1. The headers h1 to h6 get ascendingly smaller
For emphasis, you can use the strong (bold) or em (italics) tag
Always remember to close of all your tags

<a name="lists"></a>
> ## Intro to Lists and Comments

List is a list of things. You can have an ordered or unordered list. For example, you can use an unordered list for ingrediants of a recipe and an ordered list for the actual directions of the recipe.
Comments are for yourself and all for other developers. it's not rendered by the browser
You can also nest one list within a another list

```
<body>
<!--This is an ordered list -->
  <ol>
   <li>Step 1</li>
   <li>Step 2</li>
   <ul>
     <li>Sub bullets</li>
   </ul>
  </ol>
<!--This is an unordered list -->
  <ul>
    <li>Bullet 1</li>
    <li>Bullet 2</li>
  </ul>
</body>
```





