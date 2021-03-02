# Sending form data

- ## When the user submits a form, What happens exactly?
- ## Where does the data go?
- ## What do we do with this data?

## The web browser sends a request using the HTTP protocol to the server, then the server gets the request.

## We use **forms** in order to deliver the data by the HTTP request to the server.

<br>

## The `action` attribute defines where the data will send.

### Example:

           <form action="https://example.com">

<br>

## The method attribute defines how the data will send.

### Example:

           <form action="http://www.foo.com" method="GET">

### or ..

            <form action="http://www.foo.com" method="POST">
