# APIs
## API Design Best Practices
### What does REST stand for? REST is an architectural style for building distributed systems based on hypermedia. REST is independent of any underlying protocol and is not necessarily tied to HTTP.

REST APIs are designed around a resources.__.

What is an identifer of a resource? Give an example. A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: https://adventure-works.com/orders/1

What are the most common HTTP verbs? GET, POST, PUT, PATCH, and DELETE.

What should the URIs be based on? *URI*s should be based on nouns (the resource) and not verbs (the operations on the resource).*

## Give an example of a good URI.

What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing? is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation. its poor quality.

What status code does a successful GET request return?

This means the server successfully processed the request, but is not returning any content.

What status code does an unsuccessful GET request return?

What status code does a successful POST request return? The origin server MUST create the resource before returning the 201 status code.

What status code does a successful DELETE request return? If the delete operation is successful, the web server should respond with HTTP status code 204