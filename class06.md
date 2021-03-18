# chapter 
## object literals

** Object Literal **
A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.

The following demonstrates an example object literal:

var myObject = {
    sProp: 'some string value',
    numProp: 2,
    bProp: false
};
Object literal property values can be of any data type, including array literals, functions, and nested object literals. Here is another object literal example with these property types:

var Swapper = {
    // an array literal
    images: ["smile.gif", "grim.gif", "frown.gif", "bomb.gif"],
    pos: { // nested object literal
        x: 40,
        y: 300
    },
    onSwap: function() { // function
        // code here
    }
};

** Object Literal Syntax **
Object literals are defined using the following syntax rules:

1. A colon separates property name[1] from value.
2. A comma separates each name-value pair from the next.
3. A comma after the last name-value pair is optional.

If any of the syntax rules are broken, such as a missing comma or colon or curly brace, a JavaScript error will be triggered. Browser error messages are helpful in pointing out the general location of object literal syntax errors, but they will not necessarily be completely accurate in pointing out the nature of the error.

** Why and How We Use Object Literals **
* Several JavaScripts from dyn-web use object literals for setup purposes. Object literals enable us to write code that supports lots of features yet still provide a relatively straightforward process for implementers of our code. No need to invoke constructors directly or maintain the correct order of arguments passed to functions. Object literals are also useful for unobtrusive event handling; they can hold the data that would otherwise be passed in function calls from HTML event handler attributes.

There is one drawback: if you are unfamiliar with the syntax, it can be very easy to introduce errors which cause the code to stop working. *
![object](https://image.slidesharecdn.com/javascript-110725163050-phpapp01/95/javascript-literacy-2-728.jpg?cb=1311612096)

# chapter 5
## Document Object Model

When a web page is loaded, the browser creates a Document Object Model of the page.

The HTML DOM model is constructed as a tree of Objects:
![DOM](https://1.bp.blogspot.com/-Z0QnE9eWAnM/XWj6B0TmfmI/AAAAAAAAZps/aRfAU517hg0ovfzgLUTZkmjHD3SXZCoWACLcBGAs/s640/DOM.PNG)

** What is the DOM? **
The DOM is a W3C (World Wide Web Consortium) standard.
The DOM defines a standard for accessing documents:

"The W3C Document Object Model (DOM) is a platform and language-neutral interface that allows programs and scripts to dynamically access and update the content, structure, and style of a document."

The W3C DOM standard is separated into 3 different parts:

1. Core DOM - standard model for all document types
2. XML DOM - standard model for XML documents
3. HTML DOM - standard model for HTML documents

With the object model, JavaScript gets all the power it needs to create dynamic HTML:

- JavaScript can change all the HTML elements in the page
- JavaScript can change all the HTML attributes in the page
- JavaScript can change all the CSS styles in the page
- JavaScript can remove existing HTML elements and attributes
- JavaScript can add new HTML elements and attributes
- JavaScript can react to all existing HTML events in the page
- JavaScript can create new HTML events in the page

![image](https://devopedia.org/images/article/282/9041.1597665465.jpg)