# Readings: Express

## What’s the difference between PUT and PATCH?

* PUT is a method of modifying resource where the client sends data that updates the entire resource.

* PATCH is used when you want to apply a partial update to the resource.

## Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

1. Nock

2. Postman Mock Server

3. Stoplight

## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

* apiDocjs: Inline Documentation for RESTful web APIs, It creates a documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page

* Swagger: It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation.

* HTTP Status Codes

```
      responses:
        200:
          description: OK
        400:
          description: Bad request. User ID must be an integer and bigger than 0.
        401:
          description: Authorization information is missing or invalid.
        404:
          description: A user with the specified ID was not found.

```

## Compare and contrast SOAP and ReST

* SOAP stands for Simple Object Access Protocol whereas REST stands for Representational State Transfer.

* SOAP is a protocol whereas REST is an architectural pattern.

* SOAP uses service interfaces to expose its functionality to client applications while REST uses Uniform Service locators to access to the components on the hardware device.

* SOAP needs more bandwidth for its usage whereas REST doesn’t need much bandwidth.

* Comparing SOAP vs REST API, SOAP only works with XML formats whereas REST work with plain text, XML, HTML and JSON.

* SOAP cannot make use of REST whereas REST can make use of SOAP.

## Document the following Vocabulary Terms

* Web Server :

1. On the hardware side, a web server is a computer that stores web server software and a website's component files. (for example, HTML documents, images, CSS stylesheets, and JavaScript files) A web server connects to the Internet and supports physical data interchange with other devices connected to the web.

2. On the software side, a web server includes several parts that control how web users access hosted files. At a minimum, this is an HTTP server. An HTTP server is software that understands URLs (web addresses) and HTTP (the protocol your browser uses to view webpages). An HTTP server can be accessed through the domain names of the websites it stores, and it delivers the content of these hosted websites to the end user's device.

* Express : Express.js is a free and open-source web application framework for Node.js. It is used for designing and building web applications, Express.js is lightweight and helps to organize web applications on the server-side into a more organized MVC architecture.

* Routing : refers to how an application’s endpoints (URIs) respond to client requests, and define routing using methods of the Express app object that correspond to HTTP methods
