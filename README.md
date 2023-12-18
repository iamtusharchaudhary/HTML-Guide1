# HTML-Guide1

# What is HTML
HTML is the standard markup language for Web pages.
HTML is easy to learn - You will enjoy it!...
HTML stands for Hyper Text Markup Language.
HTML is the standard markup language for creating Web pages.
HTML describes the structure of a Web page.
HTML consists of a series of elements.
HTML elements tell the browser how to display the content.

# HTML Elements:-
An HTML file is made of elements. These elements are responsible for creating web pages and define content in that webpage. An element in HTML usually consist of a start tag <tag name>, close tag </tag name> and content inserted between them. Technically, an element is a collection of start tag, attributes, end tag, content between them.

Some Important Elements:-
`<h1></h1>`
`<p></p>`
`<br>`

# HTML Documents
All HTML documents must start with a document type declaration: `<!DOCTYPE html>`.

The HTML document itself begins with <html> and ends with `</html>`.

The visible part of the HTML document is between `<body>` and `</body>`.

# HTML Attributes
All HTML elements can have attributes.
Attributes provide additional information about elements.
Attributes are always specified in the start tag.
Attributes usually come in name/value pairs like: name="value".

The href Attribute:-

The `<a>` tag defines a hyperlink.
The href attribute specifies the URL of the page the link goes to:
    
    <a href="https://www.google.com">Visit please</a>

The src Attribute:-

The `<img>` tag is used to embed an image in an HTML page. 
The src attribute specifies the path to the image to be displayed:

    <img src="img_boy.jpg">   

The width and height Attributes:-

The `<img>` tag should also contain the width and height attributes, which specify the width and height of the image (in pixels):
       
       <img src="img_boy.jpg" width="500" height="600">

The alt Attribute:-

The required alt attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

     <img src="img_boy.jpg" alt="Boy with a jacket">

# HTML Headings
HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. 
`<h6>` defines the least important heading.

# Example:-
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>

# HTML Paragraphs:-
The HTML `<p>` element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.
     
# Example:-
`<p>`This is a paragraph.`</p>`
`<p>`This is another paragraph.`</p>`


