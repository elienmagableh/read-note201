# chapter 6
## tables 

** whats the table **
A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

There are several types of information that need to be displayed in a grid or table. For example: sports results, stock reports, train timetables.
When representing information in a table, you need to think 
in terms of a grid made up of rows and columns (a bit like a 
spreadsheet). we will learn how to:
- Use the four key elements for creating tables
- Represent complex data using tables
- Add captions to tables
The HTML tables allow web authors to arrange data like text, images, links, other tables, etc. into rows and columns of cells.

The HTML tables are created using the <table> tag in which the <tr> tag is used to create table rows and <td> tag is used to create data cells. The elements under <td> are regular and left aligned by default
![table](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRqjsSx0M7JXTVf-K-YKloLNQfie8c_mN3bhw&usqp=CAU)

<table>
The <table> element is used to create a table. The contents 
of the table are written out row by row.
<tr>
You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.) It is followed by one or more 
<td> elements (one for each cell in that row). At the end of the row you use a closing </tr> tag.
<td>
Each cell of a table is represented using a <td> element. (The td stands for table data.) At the end of each cell you use a closing </td> tag.

Some browsers automatically draw lines around the table and/or the individual cells. You will learn how to control the borders of tables using CSS 

** for example **
<!DOCTYPE html>
<html>

   <head>
      <title>HTML Tables</title>
   </head>
	
   <body>
      <table border = "1">
         <tr>
            <td>Row 1, Column 1</td>
            <td>Row 1, Column 2</td>
         </tr>
         
         <tr>
            <td>Row 2, Column 1</td>
            <td>Row 2, Column 2</td>
         </tr>
      </table>
      
   </body>
</html>

![table](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSdyDuc_s04HpvreLzXxLESmJFGW7X5C6IHg&usqp=CAU)

# chapter 3
## Functions, Methods, and Objects
** WHAT IS AN OBJECT? **
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 

In JavaScript, functions are objects. You can work with functions as if they were objects. For example, you can assign functions to variables, to array elements, and to other objects. They can also be passed around as arguments to other functions or be returned from those functions.

Let's first run a small test and confirm that a function is indeed an object instance:

function message() {
    alert("Greetings Linda!");
}
alert(typeof message);                   // => function
alert(message instanceof Object);        // => true

In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

![object](https://codebridgeplus.com/wp-content/uploads/Java_ObjectsClasses.jpg)

* An object has three characteristics: *
1. State: represents the data (value) of an object.
2. Behavior: represents the behavior (functionality) of an object such as deposit, withdraw, etc.
3. Identity: An object identity is typically implemented via a unique ID. The value of the ID is not visible to the external user. However, it is used internally by the JVM to identify each object uniquely.

Creating an Object
As mentioned previously, a class provides the blueprints for objects. So basically, an object is created from a class. In Java, the new keyword is used to create new objects.

** There are three steps when creating an object from a class **

Declaration − A variable declaration with a variable name with an object type.

Instantiation − The 'new' keyword is used to create the object.

Initialization − The 'new' keyword is followed by a call to a constructor. This call initializes the new object.

Following is an example of creating an object −

Example
Live Demo
public class Puppy {
   public Puppy(String name) {
      // This constructor has one parameter, name.
      System.out.println("Passed Name is :" + name );
   }

   public static void main(String []args) {
      // Following statement would create an object myPuppy
      Puppy myPuppy = new Puppy( "tommy" );
   }
}
![obj]()