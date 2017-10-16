1. What is the function of the following technologies in your assignment:
   1. HTML
    - HTML (Hypertext Markup Language) provides the structure and content, and displays the web.
   2. CSS
    - CSS can describe how HTML elements are to be displayed.
   3. JavaScript
    - JavaScript tells the browser how to handle events that happens and how to handle logical flow.
   4. Python
    - The backend used to to power server
   5. Flask
    - Framework that let web server response to HTTP request
   6. HTTP
    - Hypertext Transfer Protocol (HTTP) defines how messages are formatted and transmitted. It is designed to enable communications between clients and servers.
   7. GET and POST requests
    - GET - request data from a specified resource
    - POST - submit data to be processed to a specified resource
2. How does HTML, CSS, and JavaScript work together in the browser for this assignment?
  - The HTML provides the structure and content of the page. CSS file provides the style and makes the web look better. JavaScript implements the validation check function and helps display the weather. It can also dynamically change the HTML.

3. How does Python and Flask work together in the server for this assignment?
  - Python is the backend used to power the server and Flask is a Python Framework that handles the GET and POST requests.

4. List all of the possible GET and POST requests that your server returns a response for and describes what happens for each GET and POST request
  - "GET / HTTP/1.1" 200
  - "GET /static/css/style.css HTTP/1.1" 200
  - "GET /static/css/bg_2.jpeg HTTP/1.1" 200
  - "GET /index HTTP/1.1" 200
  - "GET /about HTTP/1.1" 200
  - "GET /static/js/script.js HTTP/1.1" 200
  - "GET /static/css/bg_1.jpeg HTTP/1.1" 200
  - "GET /blog/8-experiments-in-motivation HTTP/1.1" 200
  - "GET /blog/a-mindful-shift-of-focus HTTP/1.1" 200
  - "GET /blog/how-to-develop-an-awesome-sense-of-direction HTTP/1.1" 200
  - "GET /blog/training-to-be-a-good-writer HTTP/1.1" 200
  - "GET /blog/what-productivity-systems-wont-solve HTTP/1.1" 200
  - "POST /contact HTTP/1.1" 200
