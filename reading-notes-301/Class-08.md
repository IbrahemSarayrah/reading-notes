# RESTful web API design

#### What does REST stand for?

* Representational State Transfer

#### REST APIs are designed around

* In 2000, Roy Fielding proposed Representational State Transfer (REST) as an architectural approach to designing web services.

#### What is an identifer of a resource? Give an example

* is a URI that uniquely identifies that resource, For example, the URI for a particular customer order might be:

`https://adventure-works.com/orders/1`

#### What are the most common HTTP verbs?

* The most common operations are GET, POST, PUT, PATCH, and DELETE.

#### What should the URIs be based on?

* URIs should be based on nouns (the resource) and not verbs (the operations on the resource)

#### Give an example of a good URI

`https://adventure-works.com/orders`

#### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

* avoid "chatty" web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires, that will impose a load on the web server.

#### What status code does a successful GET request return?

* A successful GET method returns HTTP status code 200 (OK).

#### What status code does an unsuccessful GET request return?

* unsuccessful GET request return 404 (Not Found).

#### What status code does a successful POST request return?

* it returns HTTP status code 201 (Created).

#### What status code does a successful DELETE request return?

* the web server respond with HTTP status code 204
