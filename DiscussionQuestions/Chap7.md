ASP.NET Discussion Questions
Chapter 7/2nd Term


1. What is the difference between authorization and authentication?
The difference between authorization and authentication is verifying the user can do what they need to
Do with respect to your site, using some type of role-based or claim-based system.
While Authentication is verifying that users are who they say they are, using some form of login mechanism (username/password, OpenID, OAuth and so on).
 
 2. What three conditions does the OAuthorization method check?
Client Id, secret and application registration
 
 3. How do you register the AuthorizeAttribute as a global filter?
You register the AuthorizeAttribute as a global filter by adding it to the global filters collection in the 
RegisterGlobalFilters method located in \App_Start\FilterConfig.cs.
 4. How do you activate the authorization filter in ASP.NET MVC 5?
You activate the Authorization filter by applying to the controller or a specific method within a controller.
 5. What is the difference between OAUTH and OPENID? Explain.
The difference between OAuth an OpenID  where they are both used by different providers to allow a user to  login using existing accounts on other trusted sites called providers;  OAuth is used by Facebook, Twitter, and Microsoft and requires application registration and is issued a client id and a secret. While OpenID is used by Google and Yahoo and does not require you to register an application and you won’t need a client id or secret.
 6. How are authorization providers configured? 
Authorization providers are explicitly enabled for login , this task  is configured in App_Start\Starti[/Auth.cs,  upon startup all authentication providers in Startup.Auth.cs are commented out and appear under public partial class Startup.  The OAuth sites will require the application to be register and issue a client Id and a secret while the OpenID sites will not require registration or issue a client Id or a secret.

7. How do you prevent user log in information from being intercepted during log in? 
To prevent user log in information from being intercepted during log in, you must enforce transmitting this information over HTTPs to prevent interception.  
8. How do you carry out an attack by XSS?
XSS attack is a direct attack by a user sending in malicious information that is immediately shown on the page and is not stored in the database.  
 9. How do you carry out an attack by CSRF/XSRF? 
You carry out an Cross-Site Request Forgery attack by fooling a computer program into allowing you to use its authority.  Prompting a type of privileged escalation plus the introduction of malicious information as in the XSS.
10. How do you carry out an attack by cookie stealing? 
You carry out an attack by cookie stealing by stealing a user’s “persistent cookies” and impersonating that user and assuming their identity and carry out all the actions that they are capable of.  It also requires a bit of a XSS attack because malicious script may be introduced as well.
11. How do you carry out an attack by over posting? 
You carry out an attack by over posting by meddling with the form post using any number of web developer tools, adding “Approved=true” to the query string or form post data.  The model binder has no idea what fields were included on the form and will happily set the Approved property to true.  The hacker can try posting values in field with names such as Product.Price, potentially altering values in a table that was never intended for end users to edit.
12. How do you carry out an attack by open redirection?
You carry out an attack by open redirection by hijacking the redirection URL.  The user can then be redirected to malicious websites, instead of the intended destination.  Intended to trick the user.
