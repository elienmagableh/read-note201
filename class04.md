# chapter 4
## link
* Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.
You will commonly come across the following types of links: *
- Links from one website to another
- Links from one page to another on the same website
- Links from one part of a web page to another part of the 
  same page
- Links that open in a new browser window
- Links that start up your email program and address a new 
  email to someone

HTML links are hyperlinks.You can click on a link and jump to another document.When you move the mouse over a link, the mouse arrow will turn into a little hand.

Note: A link does not have to be text. A link can be an image or any other HTML element!

With HTML, easily add hyperlinks to any HTML page. Link team page, about page, or even a test by creating it a hyperlink. You can also create a hyperlink for an external website. To make a hyperlink in an HTML page, use the <a> and </a> tags, which are the tags used to define the links.

The <a> tag indicates where the hyperlink starts and the </a> tag indicates where it ends. Whatever text gets added inside these tags, will work as a hyperlink. Add the URL for the link in the <a href=” ”>. Just keep in mind that you should use the <a>…</a> tags inside <body>…</body> tags.



![link](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/06/Links-in-HTML.jpg)

and the syntax of hyperlink be 
![img](https://www.computerhope.com/jargon/h/html-tag.gif)

[example of hyperlink](http://shell.cas.usf.edu/mccook/uwy/hyperlinks.html)
<h2>Absolute URLs</h2>
<p><a href="https://www.w3.org/">W3C</a></p>
<p><a href="https://www.google.com/">Google</a></p>

<h2>Relative URLs</h2>
<p><a href="html_images.asp">HTML Images</a></p>
<p><a href="/css/default.asp">CSS Tutorial</a></p>
  
# chapter 15
## layout 
Page layout is the part of graphic design that deals with the arrangement of visual elements on a page. Page layout is used to make the web pages look better. It establishes the overall appearance, relative importance, and relationships between the graphic elements to achieve a smooth flow of information and eye movement for maximum effectiveness or impact.

page layout

Page Layout Information:

Header: The part of a front end which is used at the top of the page. <header> tag is used to add header section in web pages.
Navigation bar: The navigation bar is same as menu list. It is used to display the content information using hyperlink.
Index / Sidebar: It holds additional information or advertisements and is not always necessary to be added into the page.
Content Section: The content section is the main part where content is displayed.
Footer: The footer section contains the contact information and other query related to web pages. The footer section always put on the bottom of the web pages. The <footer> tag is used to set the footer in web pages.
Example:


<!DOCTYPE html> 
<html> 
<head> 
    <title>Page Layout</title> 
    <style> 
        .head1 { 
            font-size:40px; 
            color:#009900; 
            font-weight:bold; 
        } 
        .head2 { 
            font-size:17px; 
            margin-left:10px; 
            margin-bottom:15px; 
        } 
        body { 
            margin: 0 auto; 
            background-position:center; 
            background-size: contain; 
        } 
      
        .menu {    
            position: sticky; 
            top: 0; 
            background-color: #009900; 
            padding:10px 0px 10px 0px; 
            color:white; 
            margin: 0 auto; 
            overflow: hidden; 
        } 
        .menu a { 
            float: left; 
            color: white; 
            text-align: center; 
            padding: 14px 16px; 
            text-decoration: none; 
            font-size: 20px; 
        } 
        .menu-log { 
            right: auto; 
            float: right; 
        } 
        footer { 
            width: 100%; 
            bottom: 0px; 
            background-color: #000; 
            color: #fff; 
            position: absolute; 
            padding-top:20px; 
            padding-bottom:50px; 
            text-align:center; 
            font-size:30px; 
            font-weight:bold; 
        } 
        .body_sec { 
            margin-left:20px; 
        } 
    </style> 
</head> 
  
<body> 
      
    <!-- Header Section -->
    <header> 
        <div class="head1">GeeksforGeeks</div> 
        <div class="head2">A computer science portal for geeks</div> 
    </header> 
      
    <!-- Menu Navigation Bar -->
    <div class="menu"> 
        <a href="#home">HOME</a> 
        <a href="#news">NEWS</a> 
        <a href="#notification">NOTIFICATIONS</a> 
        <div class="menu-log"> 
            <a href="#login">LOGIN</a> 
        </div> 
    </div> 
      
    <!-- Body section -->
    <div class = "body_sec"> 
        <section id="Content"> 
            <h3>Content section</h3> 
        </section> 
    </div> 
      
    <!-- Footer Section -->
    <footer>Footer Section</footer> 
</body> 
</html>                   

# chapter 3 in js
In JavaScript, an object is data, with properties and methods.
When you declare a JavaScript variable like this:
var message="Hello World!";
You create a JavaScript String object.
The String object has a built-in property called length. For the string above, length has the value 12.
The String object also have several built-in methods.

![object](https://miro.medium.com/max/2056/1*SPZnQAWqfvZSCz4Y4rzyzg.png)