# chapter 15
## layout 

Page layout is the part of graphic design that deals with the arrangement of visual elements on a page. Page layout is used to make the web pages look better. It establishes the overall appearance, relative importance, and relationships between the graphic elements to achieve a smooth flow of information and eye movement for maximum effectiveness or impact.

** HTML Layout Elements **
HTML has several semantic elements that define the different parts of a web page:
- <header> - Defines a header for a document or a section
- <nav> - Defines a set of navigation links
- <section> - Defines a section in a document
- <article> - Defines an independent, self-contained content
- <aside> - Defines content aside from the content (like a sidebar)
- <footer> - Defines a footer for a document or a section
- <details> - Defines additional details that the user can open and close on demand
- <summary> - Defines a heading for the <details> element

![layout](https://3.bp.blogspot.com/-DaJcbXSYGHg/XBk2Sh0FEtI/AAAAAAAAAWA/7cQ1sw7rvSwXNX7Y-OWiDo7fEoGbnlrGgCLcBGAs/s1600/images%2B%252830%2529.jpeg)

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

the output will be 
![result](https://media.geeksforgeeks.org/wp-content/uploads/layout1.png)

HTML Layout Techniques
There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:

1. CSS framework
2. CSS float property
3. CSS flexbox
4. CSS grid

* CSS Frameworks *
If you want to create your layout fast, you can use a CSS framework, like W3.CSS or Bootstrap.

* CSS Float Layout *
It is common to do entire web layouts using the CSS float property. Float is easy to learn - you just need to remember how the float and clear properties work. Disadvantages: Floating elements are tied to the document flow, which may harm the flexibility.

* CSS Flexbox Layout *
Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices.

![lay](https://mobile.htmlgoodies.com/imagesvr_ce/2127/Example%201.png)

