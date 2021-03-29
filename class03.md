# Name 3 real world use cases where you’d want to change the request with custom middleware
* ## Authentication
* ## Error handling
* ## Validation

# True or false: The route handler is middleware?
### False

# In what ways can a middleware function end the process and send data to the browser?
### If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.
from (stackoverflow.com)

# At what point in the request lifecycle can you “inject” middleware?
### between the request and the response.


# What can cause express to error with “Request headers sent twice, cannot start a second response”
### When a POST request is sent to /api/route1 it will run every line in the callback. A Can't set headers after they are sent error message will be thrown because res.json() is called twice, meaning two responses are sent.
### Only one response can be sent per request!
from (stackoverflow.com)

<br>

# Document the following Vocabulary Terms

* ### Middleware:
#### functions are functions that have access to the request object (req), the response object (res), and the next function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.
from (expressjs.com)

* ### Request Object:
#### The req object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on. 
from (expressjs.com)

* ### Response Object:
#### The res object represents the HTTP response that an Express app sends when it gets an HTTP request.
from (expressjs.com)

* ### Application Middleware:
#### Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions, where METHOD is the HTTP method of the request that the middleware function handles (such as GET, PUT, or POST) in lowercase.
from (expressjs.com)

* ### Routing Middleware:
#### Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router().
from (expressjs.com)

* ### Test Driven Development:
#### is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. This is opposed to software being developed first and test cases created later.
from (Wikipedia)

* ### Behavioral Testing:
#### Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.
from (www.tutorialspoint.com)