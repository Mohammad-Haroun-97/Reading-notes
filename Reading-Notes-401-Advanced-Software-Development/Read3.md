# Express REST API  :

1. Name 3 real world use cases where youâ€™d want to change the request with custom middleware:
    * Auth middleware
    * Logging Middleware
    * Robot Middleware
2. True or false: The route handler is middleware?
* true: Middleware can be added to route handlers or other functions
3. In what ways can a middleware function end the process and send data to the browser?
    * using error handlers 
    * using next method ();

4. At what point in the request lifecycle can you â€œinjectâ€ middleware?

  * by throw errors
5. What can cause express to error with â€œRequest headers sent twice, cannot start a second responseâ€
* since we dont use next () or there are more than requests.
![img](./pic/c03-01.png)

## Documentation:

 * *Term*
    - Middleware=Middleware is a type of computer software that provides services to software applications beyond those available from the operating system. ... Middleware makes it easier for software developers to implement communication and input/output, so they can focus on the specific purpose of their application.
    - Request Object= The req object is an enhanced version of Node's own request object and supports all built-in fields and methods. 
    - Response Object=The res object represents the HTTP response that an Express app sends when it gets an HTTP reques
    - Routing Middleware= Routing defines the way in which the client requests are handled by the application endpoints. And when you make some routers in separate file, you can use them by using middleware.
    - Test Driven Development= n a real project from beginning to the end Â· Learn the test runner, Jest and understand how to structure test modules 
    - Behavioral Testing= Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing