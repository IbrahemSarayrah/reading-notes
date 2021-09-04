# Readings: AWS: Cloud Servers

* AWS (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings. AWS services can offer an organization tools such as compute power, database storage and content delivery services.

## Describe the Web-Request-Response-Cycle

* ![Request-Response-Cycle](https://bytesofgigabytes.com/IMAGES/Networking/HTTPcommuncation/http%20communication.png)

* HTTP communication involves two important terms and those are Client and Server.
>
> Client: Client is the one who makes the HTTP request. For example Browser is the client.
>
>Server: The server is the one who receives the request and sends the response. Basically server is the piece of code that is responsible for accepting the request and sending the response back. usually, the computer on which server code runs is called server.
>

* Whenever the client or user makes a request using URL then the domain name of the website is responsible for taking requests to the server and then request is forward to a particular web page

## Explain what a “server” is, as it relates to the WRRC

* All resources are hosted on a server. The server’s location on the web can be identified by its IP address, Once the client’s request has reached the server, the server will search for and return the information the client is requesting. Often times, this means querying a database, loading the information into an html page, and returning the HTML text to the user in the body of the HTTP response.

## What does it mean to “deploy” an application?

* Deploying your application means putting it on a Web server so that it can be used either through the Internet or an intranet.

## Document the following Vocabulary Terms

* Server:  a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network. In theory, whenever computers share resources with client machines they are considered servers.

* Pub/Sub: is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic. Pub/sub messaging can be used to enable event-driven architectures, or to decouple applications in order to increase performance, reliability and scalability.

* WRRC: A cycle of requests and responses that allow the internet to exist. Clients send requests to servers and servers send responses.
