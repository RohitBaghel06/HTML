# HTML
* Hypertext Markup Language
  
## What is HyperText?
- hypertext is the text that contains links to other text.
- Markup lang is a way to give instructions to a computer about how content should be organized and displayed.

## HTML Documents and Structure

```
<!DOCTYPE html>

<html>
<head>
<title> Home page </title>
</head>


<body>
<h1> best html course </h1>
</body>
</html>

```
- !DOCTYPE html --> Let the browser know it's an HTML5 Appear once, at the top of the page.
- HTML --> Root of an HTML document

- head --> Contains the information about the HTML Document
- title --> title of the HTML page

- body --> Contains everything you want to display on the Web page

- h1 --> defines a large heading


## How the browser determines the language of an HTML document.
- after DOCTYPE we have to write another line that is
- html lang = "en"
- lang is an Attribute
- Lang is a type of attribute that specifies the language of the element's contents.
- en --> Specify the language code for the element's content
- if i want to write in Hindi --> lang = "hi"
for Korean lang = "ko"
for France lang = "fr"


## HTML Attribute

- The language Attribute
- en Specifies the language code for teh element's content 
- What are Attribute in HTML
- Attributes are used along with the HTML tags to define the element's characteristics.
- Attributes provide additional information about the elements

## What is HTML heading tags?
- The heading tag is used in HTML to define headings of a page.
```
<hn>This is a Heading</hn>
<h1></h1> Biggest to
<h6></h6> smallest one
```
## Paragraphs tags
- The HTML <p> element defines a paragraph
```
<p>This is a paragraph</p>
<pre>This is a paragraph tag which also counts spaces</pre>
```

## Comments in HTML 
``` 
<!-- Comment here-- >
```
- To comment out in HTML, Insert Information between <!-- and --> tags (Browser won't show these notes)

- commenting in HTML allows developers to leave notes about their code and its functionality or to indicate necessary changes for the future.

## Text Formatting
-Text formatting in HTML refers to the way text is displayed on a web page.
-It is the process of applying various styles, colors, fonts, sizes, and other visual enhancements to text content within an HTML document.
-HTML offers a range of tags that can be used to format text, including: Bold text: <b> or <strong>

- Bold and Italic   
      ```
         <strong>, <em>
      ```
  
- Subscript and superscript
      ```
      <sub>, <sup>
      ```
  
- Text Highlighting
      ```
      <mark> --> Highlighting of text, 
      <small> --> makes text smaller,
      <del> -->  It was used to show the modification of the document the output may be the same as strikethrough but the use case is different.
      ```
   
      - the **s** Tag specifies text that is no longer correct, accurate or relevant, 
      - The **del** Tag is used to identify text that has been deleted from a document but retained to show  the history of modification made to the document.
   - Inline Styling
      ```
      <sub>, <sup>
      ```
## Colors
-HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
-But through html, we can use it in this way..
```
<h3 style="
    text-align: center; background-color: aqua;
    color: blueviolet;">this tag needs some styling</h3>
```
