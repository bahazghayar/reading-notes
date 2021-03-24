# What’s the difference between PUT and PATCH?

### The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource. If the PATCH document is larger than the size of the new version of the resource sent by the PUT method then the PUT method is preferred. 
from (Wikipedia) 

<br>

# Provide links to 3 services or tools that allow you to “mock” an API for development like json-server.

### 1. MongoDB
`https://www.mongodb.com/cloud/atlas/lp/try2?utm_source=google&utm_campaign=gs_footprint_row_search_core_brand_atlas_desktop&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=12212624584&gclid=CjwKCAjwxuuCBhATEiwAIIIz0R2LTbhDW-5gE78OjVV-E7xDKabj6WlccjY2GdbrUElhANn06l2ifxoCdnEQAvD_BwE`

### 2. Firebase
`https://firebase.google.com/`

### 3. Postman
`https://www.postman.com/`

<br>

# Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

### Under responses, each response definition starts with a status code, such as 200 or 404. An operation typically returns one successful status code and one or more error statuses. Each response status requires a description. For example, you can describe the conditions for error responses.
#### responses:
            200:
            description: OK
            400:
            description: Bad request. User ID must be an integer and bigger than 0.
            401:
            description: Authorization information is missing or invalid.
            404:
            description: A user with the specified ID was not found.
from(swagger.io) 

<br>

# SOAP vs ReST 

### * SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State Transfer.
### * SOAP is a protocol whereas REST is an architectural pattern.
### * SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.
### * SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.
### * SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.
### * SOAP cannot make use of REST whereas REST can make use of SOAP.
from (www.guru99.com)

<br>

## Web server: is a computer that runs websites. It's a computer program that distributes web pages as they are requisitioned. The basic objective of the web server is to store, process and deliver web pages to the users. This intercommunication is done using Hypertext Transfer Protocol (HTTP)
from (economictimes.indiatimes.com)

## Express: is a back end web application framework for Node. js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.
from (Wikipedia)

## Routing: is the process of finding the fastest or shortest routes between start and end locations considering a series of different constraints. Using routing software you can optimize the order of stops, specify stop time windows and avoid congestion or roadworks.
from (carto.com)

## WRRC (web request response cycle): The request/response cycle traces how a user's request flows through the app. Understanding the request/response cycle is helpful to figure out which files to edit when developing an app (and where to look when things aren't working).
from (codeacademy.com)