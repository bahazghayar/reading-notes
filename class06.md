# Authentication

### Singleton
#### A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.

#### A singleton is intended to provide only one instance of itself while facilitating a global point of access. Implementing a singleton pattern involves creating a class with a method that creates a new instance of the class. In order to implement a singleton pattern, principles of single instance and global access must be satisfied. The singleton class is like a global repository for an instance of itself, making the constructor private. Therefore, an instance outside the class cannot be created at all, and a singleton can contain only one instance. A singleton class instantiates itself and maintains that instance across systems.
from  (www.techopedia.com)
<br>

### How the Singleton pattern can be used with Node modules, specifically with classes:

#### Use it when you need application-wide, stateless objects for your application, such as helper functions.
#### You will need to write a bunch of helper functions that are stateless during a development project. These helper functions can usually be very decoupled from any object and are thus highly-reusable. I believe these scenarios are perfect for the singleton pattern, as there is no need to develop classes with class methods for them. Also, they can be reused application-wide, and usually one object for the whole app works well, thus being more memory efficient.
from (medium.com)

#### To create the singleton class, we need to have static member of class, private constructor and static factory method.
* ##### Static member: It gets memory only once because of static, itcontains the instance of the Singleton class.
* ##### Private constructor: It will prevent to instantiate the Singleton class from outside the class.
* ##### Static factory method: This provides the global point of access to the Singleton object and returns the instance to the caller.
from (www.javatpoint.com)
<br>

### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

#### Example: 
                    var express = require('express')
                    var app = express()

                    var myLogger = function (req, res, next) {
                    console.log('LOGGED')
                    next()
                    }

                    app.use(myLogger)

                    app.get('/', function (req, res) {
                    res.send('Hello World!')
                    })

                    app.listen(3000)
#### To load the middleware function, call app.use(), specifying the middleware function. For example, the following code loads the myLogger middleware function before the route to the root path (/).
#### Every time the app receives a request, it prints the message “LOGGED” to the terminal.
#### The order of middleware loading is important: middleware functions that are loaded first are also executed first.
#### If myLogger is loaded after the route to the root path, the request never reaches it and the app doesn’t print “LOGGED”, because the route handler of the root path terminates the request-response cycle.
#### The middleware function myLogger simply prints a message, then passes on the request to the next middleware function in the stack by calling the next() function.
from (expressjs.com)
<br>

## Terms: 

### Router Middleware: Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle.
from (stackoverflow.com) 

### Dynamic Module Loading: a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.
from (Wikipedia)

### Singleton Pattern: a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. The term comes from the mathematical concept of a singleton.
from(Wikipedia)

### CRUD -> REST Method Matches: It is an acronym for C - create, R - read/retrieve, U -update, D - delete- the four basic functions that are implemented in any relational DB applications. Each of it can map to a standard SQL statement, HTTP protocol method or Data Distribution Service (DDS). One can think of REST as the “CRUD for HTTP resources & more”- as long as one understands the difference between http resources and db records. REST is an API architecture which interacts with complex system whereas CRUD is a set of primitive operations which mostly manipulates data. In this blog we will be covering the different http verbs and how they map with CRUD operations.
form (medium.com)

### Mock Testing: an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.
from (devopedia.org)