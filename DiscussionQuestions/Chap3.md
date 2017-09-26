

Discussion Questions
ASP.NET MVC Professional
Chapter 3


1. What is a view? 
The view is the face of your application.  It is responsible for providing the user interface (UI) to the user
Class that renders the HTML to browser.
2. What is the similarity between view names and controller names?
The names of the view should closely match the name of the action method within the controller.
View names and controller names are dynamic.
 What is the difference between the two? 
The view name matches the action method it falls under.
3. Where in the directory structure of an ASP.NET MVC application do views live? 
Each controller folder contains a view file for each action method, and the file is named the same as the action method.
4. What is a ViewBag object? What does it do? 
A ViewBag object is a dynamic wrapper around ViewData that is used to pass data from the controller to the view.
5. What does the at symbol (@) do? Can you escape it? If so, how?
The @ symbol is a character used to tell the Razor View Engine  to transition from code to Markup.  The character can be escaped by using a double @@ operator.
 6. What are view conventions and how do they work? 
A view convention is the default format in which the view file, by default is located within each action method of a Controller.  Each view file is named the same as the action method it represents, IOT associate the correct view with the correct action method.  
7. What is a ActionResult object? How do these objects interact with views?
The ActionResult object is an instance of a class that allows the view convention to be overridden, returns actionresult object to the view which is translated to HTML and sent to the browser. 
 8. What are strongly typed views?
Strongly typed views are views that allow you to set a model type for the view. Allows you to pass a model object from the controller to the view that is strongly typed on both ends.  The benefit is the use of IntelliSense, Compiler Checking and so on.
 9. How does Razor combine HTML and C# code? 
Razor combines HTML and C# code with the use of the @ character to transition back and forth between Markup and code. Transitioning between code expressions and code blocks.
Variable Interpellation.  
10. Where do layouts live in the directory structure of an ASP.NET MVC application?
Layouts live in the view and is defined by the layout property in the view.
 11. What are the differences between a partial view and a “full view?”
Partial view does not specify a layout. If the layout is specified by a _ViewStart.cshtml page and not directly within the view, the layout will not be rendered. Does not have HTML tags, the <header> or <body> tags.
