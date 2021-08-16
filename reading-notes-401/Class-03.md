# Readings: Express REST API

## Name 3 real world use cases where you’d want to change the request with custom middleware

1. Accumulating Data

2. Error Handling

3. API Security

## True or false: The route handler is middleware?

* False

## In what ways can a middleware function end the process and send data to the browser?

* If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. and at the last middleware function if there is no error the function will send the data.

## At what point in the request lifecycle can you “inject” middleware?

* when the middleware has access to  the request

## What can cause express to error with “Request headers sent twice, cannot start a second response”

* when a server tries to send more than one response to a client. What this means is that for a given client request the server previously sent a response (either a success responsei with the resource requested or error response for a bad request) back to the client and now is unexpectedly trying to send another response.

## Document the following Vocabulary Terms

* Middleware : Functions that have access to the request object, the response object, and the next function in the application's request-response cycle.

* Request Object : he main entry point for an application to issue a request to the Library - all operations on a URL must use a Request object. The request object is application independent in that both servers and clients use the same Request class.

* Response Object: the object which communicates between the server and the output which is sent to the client.

* Application Middleware: Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions, where METHOD is the HTTP method of the request that the middleware function handles (such as GET, PUT, or POST)

* Routing Middleware: Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router()

* Test Driven Development : is a software development process relying on software requirements being converted to test cases before software is fully developed

* Behavioral Testing : is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.
