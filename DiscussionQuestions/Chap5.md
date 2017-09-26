


ASP.Net MVC
Discussion Questions Chapter 5, Pages: 109 — 136 

1. What elements does an HTML form contain?
HTML form contains two attributes
ACTION/ METHOD
 2. What attributes does the HTML form element take? 
HTML form takes proper names and values for model binding.  And elements that display the 
Appropriate errors when model binding fails.
3. What does HTTP GET do? When is it used? 
HTTP GET request takes input names and values inside the form and puts them in a query string.  GET requests do not change the state of the server and can be sent multiple times with no ill effects. Sends browser to the URL.  Get request is a read-only operation.
4. What does HTTP POST do? When is it used?
HTTP POST request gives METHOD attribute the value “post”.  Browser does not place the input values into the query string. Places them , the values, inside the body of the HTTP request instead.
 5. How does an ASP.NET action method know what the query parameters are? How does it know what the parameter values are? 
Using the Controller Class 
6. How does the dynamic calculation of the route path work in the HTML helper BeginForm? 
The BeginForm method uses the GetVirtualPath on the “routes” property exposed by the “RouteTables”.  Where web applications register all its “routes” in  “global.asax”
7. What is HTNL encoding? How dies it work? Why is it necessary?
HTML encoding  is  useful as a quick method of encoding form data and other client request data before using it in your Web application. Encoding data converts potentially unsafe characters to their HTML-encoded equivalent.



 8. What is URL encoding? How dies it work? Why is it necessary?
URL Encoding is the process of converting string into valid URL format.  Valid URL format means that the URL contains only what is termed "alpha | digit | safe | extra | escape" characters
 9. What is JavaScript encoding? How dies it work? Why is it necessary? 
The encodeURI() function encodes a Uniform Resource Identifier (URI) by replacing each instance of certain characters by one, two, three, or four escape sequences representing the UTF-8 encoding of the character (will only be four escape sequences for characters composed of two "surrogate" characters).
10. (Not in book) What is the JavaScript library jQuery? What does it contain, and why do we use it? 
jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers. With a combination of versatility and extensibility, jQuery has changed the way that millions of people write JavaScript
11. (Not in book) What is the JavaScript library jQueryUI ? What does it contain, and why do we use it? 
jQuery UI is a curated set of user interface interactions, effects, widgets, and themes built on top of the jQuery JavaScript Library. Whether you're building highly interactive web applications or you just need to add a date picker to a form control, jQuery UI is the perfect choice.
12. (Not in book) What is the JavaScript library AngularJS? What does it contain, and why do we use it? 
AngularJS is a JavaScript Framework. AngularJS is a JavaScript framework. It is a library written in JavaScript. AngularJS is distributed as a JavaScript file, and can be added to a web page with a script tag: <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.4/angular.min.js"></script>
13. In this chapter, it will be necessary to delve deeper into the HTML form element. ASP.NET provides numerous HTML helpers to assist in writing HTML. Unfortunately, these aren’t much help unless you already know HTML. In this lesson, we will focus primarily on the HTML form tag, and see how the HTML helpers help to automate writing HTML forms. If you have time, it will be helpful to review the HTML form tag using online tutorials.
