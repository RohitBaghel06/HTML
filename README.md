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
- Text formatting in HTML refers to the way text is displayed on a web page.
- It is the process of applying various styles, colors, fonts, sizes, and other visual enhancements to text content within an HTML document.
- HTML offers a range of tags that can be used to format text, including: Bold text: <b> or <strong>

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
- HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.
- But through html, we can use it in this way..
```
<h3 style="
    text-align: center; background-color: aqua;
    color: blueviolet;">this tag needs some styling</h3>
```

## HTML Anchor tag
- The <a> HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address.
- Attributes of Anchor tag 
      - herf = the URL or the destination the link points to
      - Target = specifies where the linked content will be displayed (eg = _blank --> for a new window/tab)
      - rel = Describes the relationship between the current page and the linked page. "NOT used in real practice"
      - title =  provides additional information about the link
      - id = assigns a unique identifier to the anchor tag for linking within the page.
      "helps us redirect some request to a section of the page also"
      - Class = Assigns a class for styling or JavaScript interactions
      - style: Applies inline CSS styling to the anchor.  
      - tabindex: Specifies the tab order when navigating using the keyboard.
      - accesskey: Defines a keyboard shortcut to activate the link.
      - aria-*: Attributes for accessibility purposes (e.g., aria-label). 
      - Download: Suggests that the target will be downloaded when clicked.

```
<p>You can reach Rohit at:</p>

<ul>
  <li><a href="https://example.com">Website</a></li>
  <li><a href="mailto:m.bluth@example.com">Email</a></li>
  <li><a href="tel:+123456789">Phone</a></li>
</ul>

```

  - Bonus 
   - When to use Quotes
   <br>
   So the best practice is to Always include the attribute quotes. It avoids such problems, and results in more readable code.
   <br>
   - Single or Double Quotes?
   <br>
   **Double Quotes are Best Practice** 
   & remember that using one double and one single is **not RIGHT.** 

## HTML entities
 - HTML entities are codes used to represent special characters and symbols that have reserved meanings in HTML. These entities are especially important when you  want to display characters that might conflict with HTML syntax or when you want to display characters that aren't directly available on your keyboard. HTML entities are represented using an ampersand (&) followed by a code and a semicolon (;)
      - **&lt**; = Less than sign "<"
      - **&gt**; = greater than sign ">"
      - **&amp**; = Ampersand "&"
      - **&quot**; = Double Quote (")
      - **&apos**; = Apostrophe or Single Quote"'"
      - **&nbsp**; = non Breaking space " "
      - **&dollar**; = Dollar sign "$"
      - **&copy**; = Copyright symbol " &copy;"
      - **&reg**; = registered trademark symbol"&reg;"
      - **&trade**; = Trademark symbol "&trade;"
      - **&hearts**; = Heart symbol " &hearts;"
  
## Images
- The <img> tag is used to embed an image in an HTML page.
- Images are not technically inserted into a web page; images are linked to web pages.
- The <img> tag creates a holding space for the referenced image. It has two required attributes: src - Specifies the path to the image.
```
 <img src = "/image.png" alt= "alt text"/>

sre --> Specifies the path of the image
alt --> specifies an alternate text for the image, if the image for some reason cannot be displayed.
width --> width of the image
height --> height of the image
title --> give extra info about the image
loading --> lazy Meaning that the image will load only when you get to the section not before that 

This helps reduce the load on server side.
 ```
 - Some Deprecated image tags Align, Border, hspace, vpace.
 - Best practice 
 ``` 
 ❌ <img alt="image" src="penguin.jpg" /> 
 Bad for Seo ranking

 ✅<img  alt="A Rockhopper Penguin standing on a beach."  src="penguin.jpg" /> 
 ``` 

 - Always write proper description in alt Attribute
 - how to make image responsive 
      - Width = 100% 
      - height = auto
      - we can also update the css in that we can say max-width = 500px;
 - Advanced part
   - srcset --> The srcset attribute specifies the URL of the image to use in different situations.
   - sizes --> The sizes attribute on an <**img**> element specifies different image widths <br>  These widths are tied to browser conditions which helps create responsive images.

  ## Picture Tag 
 - The <**picture**> HTML elements contains zero or more <**source**> elements and one <**img**> element to offer alternative versions of an image for different display/devices scenarios.

 ```
 <picture>
 <source srcset = "./sahaj.webp">
 <source srcset = "./sahaj.png">
 <img src = "./Sahaj.jpg" alt = "" />
 </picture> 

 it will try to load 1st one and then the second and so on.

 the images in all 3 formats should be same
 ```
 - use webp because it's file size is smaller than any other extension.

 ```
     <picture>
      <source srcset="./images/html.webp" type="image/webp" />
      <source srcset="./images/html.jpg" type="image/jpg" />
      <source srcset="./images/html.jpeg" type="image/jpeg" />
      <source srcset="./images/html.svg" type="image/svg" />
      <img
        src="./images/html.png"
        alt="best html course by sah"
        width="500"
      />
    </picture>
``` 

## Figure HTML
 - The <**figure**> tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.

- While the content of the <**figure**> element is related to the main flow, its position is independent of the main flow, and if removed it should not affect the flow of the document.

- Tip: The <**figcaption**> element is used to add a caption for the <**figure**> element.

## List   
- The <li> HTML element is used to represent an item in a list.
  
- Unordered HTML List
An unordered list starts with the <**ul**> tag. Each list item starts with the <**li**> tag.
 - The list items will be marked with bullets (small black circles) by default:
 - Unordered List (<**ul**>) Styles:
```
<ul>
  <li>first item</li>
  <li>second item</li>
  <li>third item</li>
</ul>
```

- Ordered HTML List
An ordered list starts with the <**ol**> tag. Each list item starts with the <**li**> tag.
- The list items will be marked with numbers by default:

 ```
 <ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
 ```

- Description HTML List
  The <dl> HTML element represents a description list. The element encloses a list of groups of terms (specified using the <dt> element) and descriptions (provided by <dd> elements).
  ```
  <dl>
  <dt>Firefox</dt>
  <dd>
    A free, open source, cross-platform, graphical web browser developed by the
    Mozilla Corporation and hundreds of volunteers.
  </dd>

  <!-- Other terms and descriptions -->
</dl>
  ```
  
