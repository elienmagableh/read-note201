# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

**Introduction**
Web applications are getting more advanced each day, with more elaborate uses of JavaScript as well as upcoming standards and technologies. We increasingly rely on these applications, many of them becoming a part of our daily lives. One area in which Web application development has been lacking is the ability to store data on the client-side. That is, until now.

Web Storage is a W3C specification that provides functionality for storing data on the client side until the end of a session (Session Storage), or beyond (Local Storage). It is much more powerful than traditional cookies, and easier to work with. In this article we will look at why this is, and how to use it.

The current problem: cookies can crumble
Before we go on further, let’s take a very brief look on why the current way of storing data on the client-side — cookies — is a problem:

Low size: Cookies generally have a maximum size of around 4 KB, which is not much good for storing any kind of complex data
It’s difficult for cookies to keep track of two or more transactions on the same site, which might be happening in two or more different tabs
Cookies can be exploited using techniques such as cross site scripting, resulting in security breaches
Other (less popular) alternatives to cookies include techniques involving query strings, hidden form fields, flash based local shared objects, etc. Each with their own set of problems related to security, ease of use, size restrictions etc. So up until now we have been using pretty bad ways of storing data on the user’s end. We need a better way, which is where Web Storage comes in.

**Web Storage**
The W3C Web Storage specification was designed as a better way of storing data on the client-side. It has two different types of storage: Session Storage and Local Storage.

Both Session and Local Storage will typically be able to store around 5 MB of data per domain, which is significantly more than cookies. As we’ll read on, we’ll find out more about them, and what makes Web Storage a better storage mechanism.

**Session Storage**
Session Storage has one purpose: to remember all the data in your session, and forget it as soon you close the tab (or window) you are working in.

**Setting and retrieving data**
To set a key value pair in Session Storage, you just need to write a line like this:

	sessionStorage.setItem(yourkey, yourvalue);
To retrieve the data again, you would write:

	var item = sessionStorage.getItem(yourkey);
To store the value This is a sample sentence in the Session Storage, you could write:

	sessionStorage.setItem(1, 'This is a sample sentence');

    Like other JavaScript objects, you can treat the localStorage object as an associative array. Instead of using the getItem() and setItem() methods, you can simply use square brackets. For example, this snippet of code:

var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);
…could be rewritten to use square bracket syntax instead:

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;
There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};

**Web Storage concepts and usage**

The two mechanisms within Web Storage are as follows:

- sessionStorage maintains a separate storage area for each given origin that's available for the duration of the page session (as long as the browser is open, including page reloads and restores)
1. Stores data only for a session, meaning that the data is stored until the browser (or tab) is closed.
2. Data is never transferred to the server.
3. Storage limit is larger than a cookie (at most 5MB).
- localStorage does the same thing, but persists even when the browser is closed and reopened.
1. Stores data with no expiration date, and gets cleared only through JavaScript, or clearing the Browser cache / Locally Stored Data.
2. Storage limit is the maximum amongst the three.