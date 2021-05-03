### Name 3 real world use cases where you’d want to change the request with custom middleware
- Authentication 
- Web server
- api 

###  True or false: The route handler is middleware?
true

### In what ways can a middleware function end the process and send data to the browser?
using next function without arrgs inside of it 

### At what point in the request lifecycle can you “inject” middleware?
between the rout and function

### What can cause express to error with “Request headers sent twice, cannot start a second response”

When a server tries to send several responses for one request

## middleware
 is software that provides common services and capabilities to applications outside of what's offered by the operating system.

## request object
 allows you to submit a POST or GET request to an URL. Essentially it provides a way to make REST API requests to another URL

 ## Response object
  It is the object which communicates between the server and the output which is sent to the client

 ## rout middleware   
  middleware that works on rout level
  ## application middleware
   middleware that works on application level



## Test-driven development
 is a process of modifying the code in order to pass a test designed previously

## Behavioural Testing
 is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.



- Routing
Routing refers to how an application’s endpoints (URIs) respond to client requests

- Route methods
A route method is derived from one of the HTTP methods, and is attached to an instance of the express class.

 - Route paths
Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.


- Route parameters
Route parameters are named URL segments that are used to capture the values specified at their position in the URL. The captured values are populated in the req.params object, with the name of the route parameter specified in the path as their respective keys.





