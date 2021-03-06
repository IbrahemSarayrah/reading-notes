# Reading: Bearer Authorization

## Write the following steps in the correct order

1. Register your application to get a client_id and client_secret

2. Ask the client if they want to sign in via a third party

3. Make a request to a third-party API endpoint

4. Redirect to a third party authentication endpoint

5. Make a request to the access token endpoint

6. Receive access token

7. Receive authorization code

## What can you do with an authorization code?

* An authorization code is an alphanumeric password that authorizes its user to purchase, sell or transfer items, or to enter information into a security-protected space.

## What can you do with an access token?

* Access tokens are the thing that applications use to make API requests on behalf of a user,The access token represents the authorization of a specific application to access specific parts of a user's data.

## What’s a benefit of using OAuth instead of your own basic authentication?

* It enables apps to obtain limited access (scopes) to a user’s data without giving away a user’s password. It decouples authentication from authorization and supports multiple use cases addressing different device capabilities. It supports server-to-server apps, browser-based apps, mobile/native apps, and consoles/TVs.

* It is easy to implement and provides strong authentication.

* This flexible protocol relies on SSL (Secure Sockets Layer) to ensure data between the web server and browsers remain private.

## Document the following Vocabulary Terms

* Client ID :  is a unique eight-digit number generated by the depository participants to easily identify their clients.

* Client Secret: is a secret known only to the application and the authorization server.

* Authentication Endpoint: is a security mechanism designed to ensure that only authorized devices can connect to a given network, site or service.

* Access Token Endpoint: The token endpoint is where apps make a request to get an access token for a user.

* API Endpoint: is a point at which an application program interface (API) -- the code that allows two software programs to communicate with each other -- connects with the software program. APIs work by sending requests for information from a web application or web server and receiving a response.

* Authorization Code: is a temporary code that the client will exchange for an access token.

* Access Token: is an object encapsulating the security identity of a process or thread. A token is used to make security decisions and to store tamper-proof information about some system entity.
