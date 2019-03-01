# Introduction to HTML

To fully understand the difference between REST and SOAP, it is important to understand what an API is and how it works, how to use HTTP and perform REST and SOAP operations.

> ## Contents

**[Basics](#basics)**<br>
**[What does HTML look like?](#HTMLlooklike)**<br>
**[Writing a new HTML](#WritinganewHTML)**<br>

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
> ## Writing a new HTML











