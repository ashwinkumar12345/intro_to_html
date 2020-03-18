# Introduction to HTML


> ## Contents

**[Basics](#basics)**<br>
**[What does HTML look like?](#HTMLlooklike)**<br>
**[Writing HTML](#WritinganewHTML)**<br>
**[Lists and Comments](#lists)**<br>
**[Loading Images](#loadingimages)**<br>
**[Adding Links](#links)**<br>
**[Adding Images as Links](#imglinks)**<br>
**[Adding a Mailto Link](#mailto)**<br>

<a name="basics"></a>
> ## What is HTML?

HTML stands for Hypertext Markup Language. It's a standard markup language used to create web pages.

It tells your browser how to render web pages. A markup language is a language designed for processing the presentation of the text. 

You markup your text with tags and your browser interprets those tags to display the text. 

<a name="HTMLlooklike"></a>
> ## What does HTML look like?

HTML uses tags and elements to encode different parts of the content.
For example, you want to represent some text and you want that text to be represented as a paragraph of it's own.

```html
<p>Hello, World!</p>
```

You are marking up regular text with tags into these elements. The browser then interprets these elements to show you what you expect on a web page.

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
> ## Writing HTML

Open up `jsbin.com` and type up in the following HTML code.

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

You have six different types of headers starting from h1. The headers h1 to h6 get ascendingly smaller.

For emphasis, you can use strong (bold) or em (italics) tags.
Always remember to close of all your tags.

<a name="lists"></a>
> ## Lists and comments

List is a list of things. You can have an ordered or unordered list. For example, you can use an unordered list for ingrediants of a recipe and an ordered list for the actual directions of the recipe. You can also nest one list within a another list

Comments are for yourself and for other developers. it's not rendered by the browser

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
<a name="loadingimages"></a>
> ## Loading images

You can use an `img` tag to load an image.
It has an attribute `src` that holds the url of the image.
In this case, you don't need a closing `img` tag as it's not wrapping another element.
You can also add an `alt` attribute that loads if your image fails to load or if somebody is using an assistive device such as a screen reader.

```
<body>
  <img src="http://.....jpg" alt="description of the image"/>
</body>
```

You can nest images in lists as well.

<a name="links"></a>
> ## Adding links

You can use an `a` tag to load an image.
It has an attribute `href` that holds the url of the image.
The url can be an absolute or relative path. 
You also need to add the text that's to be seen. 

```
<a href="http://www.google.com">Google homepage</a>
```
You can nest links in lists as well

<a name="imglinks"></a>
> ## Adding images as links

You can convert an image to a link as follows:

```
<a href="http://www.google.com">
   <img src="http://.....jpg" alt="description of the image"/></a>
```

<a name="mailto"></a>
> ## Adding a Mailto Link

You can use a `mailto` attribute:

```
<a href="mailto:yourname@gmail.com">Email me</a>
```

<a name="div"></a>
> ## Adding a div

Used to divide up your page into logical chunks:

```
<div>
  <p></p>
</div>
```
