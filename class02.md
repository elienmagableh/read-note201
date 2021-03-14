# class02
## chapter 2
** HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER **
 - html files This is where the content of the page lives. The HTML gives the page structure and adds 
   semantics.
 - css file The CSS enhances the HTML page with rules that state how the HTML content is presented 
   (backgrounds, borders, box dimensions, colors, fonts, etc.).
 - js files This is where we can change how the page behaves, adding interactivity. We will aim to keep 
   as much of our JavaScript as possible in separate files. 
   ![ch2](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTyKnfEuUR_twjyJYWvvMcxRlHvH36mqXWutA&usqp=CAU)

**  window that the page is being shown in. **
1. WINDOW OBJECT 
  On the right-hand page you can see a model of a computer with a browser open on the screen. 
The browser represents each window or tab using a window object. The location property of the 
window object will tell you the URL of the current page. 
2. DOCUMENT OBJECT 
  The current web page loaded into each window is modelled using a document object. 
The title property of the document object tells you what is between the opening 
<t; t le> and closing </title> tag for that web page, and the astModi fi ed property
of the document object tells you the date this page was last updated. 

** How do computers fit in with the world around them?**

 - Computers create models of the world using data.
 -  The models use objects to represent physical things.
    Objects can have properties that tell us about
    the object methods that perform tasks using the
    properties of that object, events which are triggered
    when a user interacts with the computer,
 - Programmers can write code to say "When this event
    OCcurs, run that code."
 - Web browsers use HTML markup to create a model
  of the web page Each element creates its own node (which is a kind of object).
 - To make web pages interactive, you write code that
   uses the browser's model of the web page.

[example ](https://www.w3schools.com/html/html_examples.asp)

** ADDING AN ELEMENT TO THE DOM TREE **
* createEl ement () creates an element that can be added to the 
DOM tree, in this case an empty <l i >element for the list This 
new element is stored inside a variable called newEl until it is attached to the DOM tree later on.
createTextNode() allows you to create a new text node to attach 
to an element. It is stored in a variable called newText. *

## document.write() 
The document object's write () method is a simple 
way to add content that was not in the original 
source code to the page, but its use is rarely advised. 
ADVANTAGES 
- It is a quick and easy way to show beginners how 
content can be added to a page. 
DISADVANTAGES 
- It only works when the page initially loads. 
- If you use it after the page has loaded it can: 
1. Overwrite the whole page 
2. Not add the content to the page 
3. Create a new page 
• It can cause problems with XHTML pages that 
are strictly validated. 
• This method is very rarely used by programmers 
these days and is generally frowned upon. 
![print](https://cf.ppt-online.org/files/slide/p/Pik63WUtAOSQ4D8EmwelpgI0vGa1xCF5KJNTXH/slide-33.jpg)  