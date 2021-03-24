# chapter 10
## Error Handling & Debugging

When you develop any application that’s more than a trivial example, errors are inevitable. A JSP-based application is no exception. There are many types of errors you will deal with. Simple syntax errors in the JSP pages are almost a given during the development phase. And even after you have fixed all the syntax errors, you may still have to figure out why the application doesn’t work as you intended due to design mistakes. The application must also be designed to deal with problems that can occur when it’s deployed for production use. Users can enter invalid values and try to use the application in ways you never imagined. External systems, such as databases, can fail or become unavailable due to network problems.

Since a web application is the face of a company, making sure it behaves well, even when the users misbehave and the world around it falls apart, is extremely important for a positive customer perception. Proper design and testing is the only way to accomplish this goal. Unfortunately, many developers seem to forget the hard-learned lessons from traditional application development when designing web applications. For instance, a survey of 100 e-commerce managers, conducted by InternetWeek magazine (April 3, 2000 issue), shows that 50% of all web site problems were caused by application coding errors. That’s the highest ranking reason in the survey, ahead of poor server performance (38%), poor service provider performance (35%)

![handeerror](https://www.manishsanger.com/wp-content/uploads/2018/03/Exception-Hierarchy.png)

![handel](https://i.stack.imgur.com/cf2t7.png)

** HOW TO DEAL WITH ERRORS ** 
Now that you know what an error is and how the browser treats them, 
there are two things you can do with the errors. 
1. DEBUG THE SCRIPT TO FIX ERRORS 
If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it. 

You will find that the developer tools available in every major modern browser will help you with this task. In this chapter, you will learn about the developer tools in Chrome and Firefox. (The tools in Chrome are identical to those in Opera.) IE and Safari also have their own tools (but there is not space to cover them all). 

2. HANDLE ERRORS GRACEFULLY 
You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements. Sometimes, an error may occur in the script for a 
reason beyond your control. For example, you might request data from a third party, and their server may not respond. In such cases, it is particularly important to write error-handling code. In the latter part of the chapter, you will learn how to gracefully check whether something will work, and offer an alternative option if it fails. 