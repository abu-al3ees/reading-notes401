 
## What’s the difference between PUT and PATCH

The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.


### Provide links to 3 services or tools that allow you to “mock” an API for development
- [mockoon](https://mockoon.com/)
- [stoplight](https://stoplight.io/mocking/)
- [ Mockserver](https://www.npmjs.com/package/mockserver)
 
 
 ### Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

 ### APIDoc
200(ok),
,400(Bad Request)
,401(4Not Authenticated)
,404(Not found)
,4xx (errors)

### Swagger
200(ok),
,400(Bad Request)
,401(Authorization information is invalid)
,404(Not found)


### Compare and contrast SOAP and ReST
SOAP is a standardized protocol that sends messages using other protocols such as HTTP .

As opposed to SOAP, REST is not a protocol but an architectural style. The REST architecture lays down a set of guidelines you need to follow if you want to provide a RESTful web service.

As SOAP is an official protocol, it comes with strict rules and advanced security features such as built-in ACID compliance and authorization.


 ## Node.js 
 is an open-source, cross-platform runtime environment that allows developers to create all kinds of server-side tools and applications in JavaScript. The runtime is intended for use outside of a browser context (i.e. running directly on a computer or server OS).


 Express is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks. It provides mechanisms to:

- Write handlers for requests with different HTTP verbs at different URL paths (routes).
- Integrate with "view" rendering engines in order to generate responses by inserting data into templates.
- Set common web application settings like the port to use for connecting, and the location of templates that are used for rendering the response.
- Add additional request processing "middleware" at any point within the request handling pipeline.

While Express itself is fairly minimalist, developers have created compatible middleware packages to address almost any web development problem