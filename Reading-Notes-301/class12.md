# Read12 Summary



`100` =These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client. Like using a different protocol or telling the client that its request will fail before they start sending the body.


`200` =These are the success codes. They tell the client that its request was accepted.  

`300` =These are redirection codes. They tell the client that the resource they are requesting isnâ€™t available at the expected location anymore   

`400` =These are the client error codes. They are all about invalid requests a client sent to a server.  

`500` =These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server

![CRUD](https://www.dorusomcutean.com/wp-content/uploads/2020/03/crud.jpg)

### What is the â€˜Forbiddenâ€™ status code?


The HTTP 403 Forbidden client error status response code indicates that the server understood the request but refuses to authorize it. This status is similar to 401 , but in this case, re-authenticating will make no difference.

--------------------------------------------------------------------------------

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

To become dynamic and change when you upload it online

### What is middleware?

A middleware is basically a function that will the receive the Request and Response objects, just like your route Handlers do. As a third argument you have another function which you should call once your middleware code completed

### What does app.use(express.json()) do?

express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app

### What does the /:id mean in a route?

And the root that the router will return to if pressed

### What is the difference beween PUT and PATCH?

![CRUD](https://codeteddycom.files.wordpress.com/2017/06/statuscode.png)

The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

### How do you make a defalut value in a schema?

Defaults. Each SchemaType that you define (you can read more about them in the model definition chapter ) can have a default value. Default values

express.json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object. This method is called as a middleware in your application using the code: app.use(express.json()).

![500 error](https://linuxhint.com/wp-content/uploads/2020/11/internal_Server_Error_500-01.png)

500 Internal Server Error is based on an HTTP status code which indicate that the server contains errors internally. The 500 error code is a generic message that appears when something unexpected happened on the web server & the server canâ€™t offer more specific information. However, there are  ways to quickly get around the problem because this error message is often temporary & the website may quickly fix itself.