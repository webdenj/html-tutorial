# HTML 
**Code Editors**

 - [Visual Studio Code](https://code.visualstudio.com/)
 - [ATOM](https://github.blog/2022-06-08-sunsetting-atom/)
 - [BRACKETS](http://brackets.io/)
 - [Notepad++](https://notepad-plus-plus.org/downloads/)


Hyper Text Markup Language


**Tag**

```html
<tagname> Content </tagname>

<html> HTML document content </html>

<tagname />

<img />
```
  **Introduction to the HTML document**
  
All HTML documents must start with a `<!DOCTYPE>` declaration.

```html
<!doctype html>
```

## HTML Document structure

Simple HTML document

```html
<!doctype html>
<html lang="en" dir="rtl">
    <head>
    </head>
	    
    <body>
    </body>
</html>
```
head: _Search engine information structure_ body: _User information structure_

## HTML document title

The `<title>` tag defines the title of the document. The title must be text-only, and it is shown in the browser's title bar or in the page's tab.

```html
<!doctype html>
<html>
    <head>
	     <title> webdenj website </title>
    </head>
    <body>
    </body>
</html>
```
## HTML content

The `<body>` tag defines the document's body. There can only be one `<body>` element in an HTML document.

```html
<!doctype html>
<html>
    <head>
	     <title> webdenj website </title>
    </head>
    <body>
	     This is my website
    </body>
</html>
```
## Break line Tag
The `<br>` tag inserts a single line break.

```html
My name is Amir <br> I am Programmer
```

## Horizontal Tag
The `<hr>` tag defines a thematic break in an HTML page

```html
My name is Amir<hr> I am Programmer
```
## Paragraph Tag

The HTML `<p>` element defines a paragraph.

```html
<p>This is first paragraph</p>
<p>This is second paragraph</p>
<p>This is third paragraph</p>
```

## Heading Tags

The `<h1>` to `<h6>` tags are used to define HTML headings.

```html
<h1>heading1</h1>
<h2>heading2</h2>
<h3>heading3</h3>
<h4>heading4</h4>
<h5>heading5</h5>
<h6>heading6</h6>
```

## Formatting tags

Formatting elements were designed to display special types of text:

`<b>` - Bold text 
`<strong>` - Important text 
`<i>` - Italic text 
`<small>` - Smaller text ...

```html
<p>
	In publishing and <b>graphic design</b>, Lorem ipsum is a placeholder text commonly used to demonstrate the visual form of a document or a typeface without relying on <strong>meaningful content</strong>.
</p>
<p>
	Lorem ipsum may be used as a <small>placeholder</small> before <i>final copy is available</i>.
</p>
```


## Comment in HTML
You can add comments to your HTML source by using the following syntax:

```html
<!-- This is a comment -->  
<p>This is a paragraph.</p>  
<!-- Remember to add more information here -->
```	
