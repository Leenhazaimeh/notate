# CRUD
1. In your own words, describe what each group of status code represents:

100’s = tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
200’s = the success codes. They tell the client that its request was accepted.
300’s = These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore.
400’s = These are the client error codes. They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc.
500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies.
2.  What is a status code 202? 202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.

3. What is a status code 308? 308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. It’s helpful when we have multiple endpoints for one resource, but don’t want to implement reading from all of them.

4. What code would you use if an update didn’t return data to a client? 204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.

5. What code would you use if a resource used to exist but no longer does? **410 Gone**

What is the ‘Forbidden’ status code? 403 Forbidden

Build A REST API With Node.js, Express, & MongoDB - Quick
6. Why do we need to pull our MongoDB database string out of our server and put it into our .env? to be able to change it when we use something not our local host

7. What is middleware? Middleware is software that provides common services and capabilities to applications outside of what's offered by the operating system.

8. What does app.use(express.json()) do? express. json() is a method inbuilt in express to recognize the incoming Request Object as a JSON Object.

9. What does the /:id mean in a route? Route parameters are named URL segments that are used to capture the values specified at their position in the URL. The captured values are populated in the req.params object, with the name of the route parameter specified in the path as their respective keys.

10. What is the difference beween PUT and PATCH? The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

11. How do you make a defalut value in a schema? Declaring Defaults in Your Schema. Your schemas can define default values for certain paths. If you create a new document without that path set

12. What does a 500 error status code mean? The HyperText Transfer Protocol (HTTP) 500 Internal Server Error server error response code indicates that the server encountered an unexpected condition that prevented it from fulfilling the request. This error response is a generic "catch-all" response.

13. What is the difference between a status 200 and a status 201? The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created (for example a new page).