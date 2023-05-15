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
## Image Tag
The `<img>` tag is used to embed an image in an HTML page.

```html
<img src="webdenj.png" alt="webdenj.png" width="200" height="100" />
```
## List Tag

**Order lists** An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

```html
<ol>
	<li>Home</li>
	<li>About Us</li>
	<li>News</li>
	<li>Contact Us</li>
</ol>
```

**Unorder list** An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

```html
<ul>
	<li>Home</li>
	<li>About Us</li>
	<li>News</li>
	<li>Contact Us</li>
</ul>
```
## Link tag

The `<a>` tag defines a hyperlink, which is used to link from one page to another.

```html
<a href="http://google.com"> Go to Google</a>
```

A linked page is normally displayed in the current browser window, unless you specify another target.

```html
<a href="http://google.com" target="_blank"> Go to Google</a>
```

> Target attribute values:
>  _self: _Opens the linked document in the same frame as it was clicked (**this is default**)_ 
>  _blank: _Opens the linked document in a new window or tab_
>  _parent: _Opens the linked document in the parent frame_ 
>  _top: _Opens the linked document in the full body of the window_ 


The `rel` attribute specifies the relationship between the current document and the linked document.

 
 ```html
<a rel="nofollow" href="http://google.com" target="_blank"> Go to Google</a>
<a rel="author" href="http://webdenj.com" target="_blank"> Go to Webdenj</a>
```

> Search engines can use this attribute to get more information about a link!
## Table Tag

The `<table>` tag defines an HTML table. An HTML table consists of one `<table>` element and one or more `<tr>`  `<th>` and `<td>` elements.

```html
<table>  
   <tr>  
       <th>Name</th>  
       <th>Family</th> 
       <th>Age</th>  
   </tr>  
   <tr>  
       <td>Mohammad</td>  
       <td>Hosseini</td>  
       <td>30</td>
   </tr>
   <tr>  
       <td>Ali</td>  
       <td>Mohammadi</td>  
       <td>25</td>
   </tr>  
</table>
```
An HTML table with a `<thead>` and `<tbody>` element:

```html
<table>
    <thead>  
        <tr>  
            <th>Name</th>  
            <th>Family</th> 
            <th>Age</th>  
        </tr>
    </thead> 
    <tbody>
        <tr>  
            <td>Mohammad</td>  
            <td>Hosseini</td>  
            <td>30</td>
        </tr>
        <tr>  
            <td>Ali</td>  
            <td>Mohammadi</td>  
            <td>25</td>
        </tr>
    </tbody> 
    </table>
```
## Video Tag

The HTML `<video>` element is used to show a video on a web page.

```html
<video width="320"  height="240"  controls>  
	<source src="movie.mp4"  type="video/mp4">  
	Your browser does not support the video tag.  
</video>
```

To start a video automatically, use the `autoplay` attribute:

```html
<video width="320"  height="240"  autoplay>  
	<source src="movie.mp4"  type="video/mp4">    
	Your browser does not support the video tag.  
</video>
```

## Audio Tag

The HTML  `<audio>`  element is used to play an audio file on a web page.

```html
<audio controls>    
	<source src="audio.mp3"  type="audio/mpeg">  
	Your browser does not support the audio element.  
</audio>
```

To start an audio file automatically, use the `autoplay` attribute:

```html
<audio controls autoplay>    
	<source src="audio.mp3"  type="audio/mpeg">  
	Your browser does not support the audio element.  
</audio>
```
	
## Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.


```html
<form action="http://webdenj.com" method="GET">
...
</form>
```

**Input tag** One of the most used form element is the `<input>` element. The `<input>` element can be displayed in several ways, depending on the `type` attribute.

```html
<label for="fname">First name:</label>  
<input type="text" id="fname" name="fname">
```

> text: _Displays a single-line text input field_  
> radio: _Displays a radio button (for selecting one of many choices)_  
> checkbox: _Displays a checkbox (for selecting zero or more of many choices)_  
> submit: Displays a submit button (for submitting the form)_ 
> button: _Displays a clickable button_  
> color: _Displays a color picker_ 
> file: _ Display a "Browse" button for file uploads._

`<input type="submit">` defines a button for **submitting** form data to a **form-handler**:

```html
<input type="submit" value="Submit">
```

**Textarea tag** The `<textarea>` element defines a multi-line input field (a text area):

```html
<textarea name="message" rows="10" cols="30">  
	The cat was playing in the garden.  
</textarea>
```
