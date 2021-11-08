Javascript in Browser - Common Web APIs (Module 3 - Fundamentals)

I made a To Do List the stores the infromation in the user's browser using Local Storage API.

To Do List:
  * The Date is at the top of the list.  new Date ()

  * Add a new item to the list at the bottom of the form. The item will be stored in the browser, even if the browser is refreshed. It is stored using localStorage API, which stores the infromation in the user's browser.

  * Click the circle icon for the item that you have finished and the circle will get a green check mark but the item will not disappear from the list

  * Removing the item from the list you can click on the trash can icon and then it will disappear from the list aswell as from Local Storage.
  
  * To refresh the whole list you can click the arrow-circle icon in the right top corner. Then all the iteams will disappear from Local Storage and you can make a new list.
---------------------------------------------------

APIs

What is a Web API?  
  * A web API is an application programming interface for either a web server or a web browser.

How to get information about Web APIs?
  * Many APIs are publicly available but there are also so-called internal APIs, wich are created and used by developers thet need APIs for private applications.
  * When it comes to web and moblie applications, there is a process to follow in order to determine what API the website uses. In some cases, you can also use the internal API without interacting with the website (that is programmatically, by issuing requests directly from the code).

How websites use APIs:
  * There are two main says in which websites use APIs. -> Backend-tied method and Frontend-tied method

 <-- The BACKEND-TIED approach is the method where the application makes requwsts to the API on the server's side. --> 
  1. The user wants to visit a page of the website. They use a browser to send an HTTP request to the server where the site is hosted.
  2. To provide a response the user, the server needs to use an API.
  3. the server sends the request to the API and processes the response of the API. The response to the user is prepared using the response of the API.
  4. the server sends the prepared response (most often it is the HTML page) to the user.
  5. The user's browser renders the response and shows the result to the user.

<-- The FRONTEND-TIED approach. -->
  * Is the most modern web frameworks use client-side rendering. They send a blank HTML file to the browser along with JavaScript that fills it with data. In this case, it takes data from the internal API. This is handy for us beacause if it is dine with our browser we can find it.


