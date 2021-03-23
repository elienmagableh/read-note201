# chapter 7
## forms 
** form **
A webform, web form or HTML form on a web page allows a user to enter data that is sent to a server for processing. Forms can resemble paper or database forms because web users fill out the forms using checkboxes, radio buttons, or text fields. For example, forms can be used to enter shipping or credit card data to order a product

Forms are enclosed in the HTML <form> element. This element specifies the communication endpoint the data entered into the form should be submitted to, and the method of submitting the data

![form](https://i2.wp.com/www.tutorialbrain.com/wp-content/uploads/2019/01/HTML-Form.jpg?fit=1920%2C1080&ssl=1)

** element **
* Forms can be made up of standard graphical user interface elements: *

- <text> — a simple text box that allows input of a single line of     text.
- <email> - a type of <text> that requires a partially validated email address
- <number> - a type of <text> that requires a number
- <password> — similar to <text>, it is used for security purposes, in which the characters typed in are invisible or replaced by symbols such as *)
- <radio> — a radio button
- <file> — a file select control for uploading a file
- <reset> — a reset button that, when activated, tells the browser to restore the values to their initial values.
- <submit> — a button that tells the browser to take action on the form (typically to send it to a server)
- <textarea> — much like the <text> input field except a <textarea> allows for multiple rows of data to be shown and entered
- <select> — a drop-down list that displays a list of items a user can select from
![imgform](https://www.htmlgoodies.com/img/2010/06/HTML-Forms-From-Basics-to-Style-Layouts-Figure1.gif)

Radio Buttons
The <input type="radio"> defines a radio button.

Radio buttons let a user select ONE of a limited number of choices.

Example
A form with radio buttons:

<form>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label><br>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br>
  <input type="radio" id="other" name="gender" value="other">
  <label for="other">Other</label>
</form>

# chapter 14 
# Lists, Tables and forms

There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

so we will learn how to:
- Specify the type of bullet point or numbering on lists
- Add borders and backgrounds to table cells
- Control the appearance of form controls

HTML tables
Tables can be a useful way of organising content on a web page, particularly text.

1. A table is defined with the <table> tag.
2. Each row in the table is defined with the <tr> tag.
3. A table heading is defined with the <th> tag. (Headings are bold  and centred by default.)
4. Each cell of data in the table is defined with the <td> tag.

Basic table: Set up a table with three headings to your page, by adding the following code to your document under the “ordered list” code. This is a real-life example that lists a weekly class schedule. The <th> tags will form the columns in this table, and the <td> tags will form the rows.

<table style="width:100%">
 <tr>
   <th>Monday</th>
   <th>Tuesday</th>
   <th>Wednesday</th>
 </tr>
 <tr>
   <td>9AM Lecture</td>
   <td>12PM Lecture</td>
   <td>Study Break</td>
 </tr>
  <tr>
   <td>10AM Lecture</td>
   <td>Study Break</td>
   <td>2PM Lecture</td>
  </tr>
</table>

![form](https://blog.hyperiondev.com/wp-content/uploads/2018/11/HTML-Tut-3-1-Basic-Table-1.jpg)

When you refresh your page, the table will appear as follows:

![result](https://blog.hyperiondev.com/wp-content/uploads/2018/11/HTML-Tut-3-2-Basic-Table-2.jpg)

# chapter 6 
## event 
 What is an Event ?
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.

When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

Developers can use these events to execute JavaScript coded responses, which cause buttons to close windows, messages to be displayed to users, data to be validated, and virtually any other type of response imaginable.

Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.
![img](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events.png)

Please go through this small tutorial for a better understanding HTML Event Reference. Here we will see a few examples to understand a relation between Event and JavaScript −

onclick Event Type
This is the most frequently used event type which occurs when a user clicks the left button of his mouse. You can put your validation, warning etc., against this event type.

Example
Try the following example.

Live Demo
<html>
   <head>   
      <script type = "text/javascript">
         <!--
            function sayHello() {
               alert("Hello World")
            }
         //-->
      </script>      
   </head>
   
   <body>
      <p>Click the following button and see result</p>      
      <form>
         <input type = "button" onclick = "sayHello()" value = "Say Hello" />
      </form>      
   </body>
</html>