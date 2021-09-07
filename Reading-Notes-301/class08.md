# read 8
# API Design Best Practices

* ## What does REST stand for?

>Ans: Representational State Transfer.

* ## REST APIs are designed around a ____.

>Ans1: REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client.

>Ans2: A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

* ## What is an identifer of a resource? Give an example.

![rest](https://networkinterview.com/wp-content/uploads/2021/06/REST-DP.jpg)

The Roy Fielding State Transfer (REST) is an architectural approach for designing web services. It is based on building distributed systems which are based on hypermedia & REST is an independent protocol which is not tied with HTTP. The main purpose of REST is to use open standards without implementing API to which the client applications are looking for any specific implementation.

### What are the most common HTTP verbs?
HTTP defines a set of request methods to indicate the desired action to be performed for a given resource. Although they can also be nouns, these request methods are sometimes referred to as HTTP verbs.
### What status code does a successful GET request return?
201 Created
The request has succeeded and a new resource has been created as a result. This is typically the response sent after POST requests, or some PUT requests. 
### What status code does an unsuccessful GET request return? 
A 404 status code does not indicate whether the resource is temporarily or permanently missing. But if a resource is permanently removed, a 410 (Gone) should be used instead of a 404 status. 

* GET - The GET method is based on requesting the resource's representation in which it can only receive the data. For a successful GET method, it returns HTTP status code 200 which indicate that the server received the data successfully, but if the resource is not found, then it would return 404 which is not found.

* POST - THe POST method is based on submitting an entity to the resource which can have side effects on the server sometimes. Like the GET method, the POST method can be successful if it does processing that returns HTTP status code 200 which include the result of the operation response body, but if its not successful, it will return HTTP status code 204 which indicates that it has no content.

* PUT - The PUT method replaces the representations of the resources with a request payload. The PUT method can be successful if it creates a new resource which returns HTTP code status 201, but if the method updates the resource, it will either return 200 (OK) or 204 (No content).

* DELETE - The DELETE method is based on adeleting the resources & for it to be successful, the web server must respond with HTTP status code 204 (No content) which means that the process is successsful, but if its not handled not only the body contains no details, but the resource will not exist which indicates that the web server returns HTTP 404 (Not found)

![regExr](https://regexr.com/assets/card.png

### What status code does a successful DELETE request return?
Responses. If a DELETE method is successfully applied, there are several response status codes possible: A 202 ( Accepted ) status code if the action will likely succeed but has not yet been enacted. A 204 ( No Content ) status code if the action has been enacted and no further information is to be supplied.

![1](https://www.programmableweb.com/sites/default/files/Five-Best-Practices-for-Building-an-Effective-API-Marketplace-Figure-1-Key-components-of-an-API-Marketplace.png)