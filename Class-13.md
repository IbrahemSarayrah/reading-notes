# Status Codes

#### In your own words, describe what each group of status code represents:

* 100’s = These are informational status codes, and inform the client that  part of the request has been received and the server will try to comply with a transmission demand of the client.

* 200’s = These are the success codes, They tell the client that its request was accepted

* 300’s = These are redirection codes, They tell the client that the resource they are requesting isn’t available at the expected location anymore.

* 400’s = These are the client error codes. They are all about invalid requests a client sent to a server.

* 500’s = These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies.

#### What is a status code 202?

* This code tells the client that the request was valid, but its processing will finish sometime in the future, and often used for asynchronous processing

#### What is a status code 308?

* This tells the client to use another URL to access the resource and not use the current URL anymore.

#### What code would you use if an update didn’t return data to a client?

* 204 No Content - A proper code for updates that don’t return data to the client

#### What code would you use if a resource used to exist but no longer does?

* 410 Gone - This is like 404 but we know that the resource existed in the past, but it got deleted or somehow moved, and we don’t know where.

#### What is the ‘Forbidden’ status code?

* 403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

#### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

* because we are working locally and when we want to deploy the database we will save it in environment variable, and also will add more security.

#### What is middleware?

* middleware are functions that execute during the lifecycle of a request to the Express server

#### What does app.use(express.json()) do?

* let the server accept json files

#### What does the /:id mean in a route?

* we can access is using **`req.params.id`** and we will give access to what ever pass after the **/**

#### What is the difference beween PUT and PATCH?

* PATCH will update what the user enter PUT will update all the information

#### How do you make a defalut value in a schema?

* the schema will have object that have keys for all the different properties and define the type of all the properties.

#### What does a 500 error status code mean?

* there is an error in the server

#### What is the difference between a status 200 and a status 201?

* 201 is more specific for example the 201 code will give to the user successfully created an object , and 200 will give that everything was successful
