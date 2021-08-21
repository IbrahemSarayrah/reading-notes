# Readings: Authentication

## Explain what a “Singleton” is (in Computer Science terms)

* A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance. It contains static variables that can accommodate unique and private instances of itself. It is used in scenarios when a user wants to restrict instantiation of a class to only one object. This is helpful usually when a single object is required to coordinate actions across a system.

* A single object used across systems remains constant and needs to be defined only once rather than many times.

## Explain how the Singleton pattern can be used with Node modules, specifically with classes

* By design, singletons create an instance of a class if it does not yet exist. Otherwise, they return the reference to an existing instance.

```
class Singleton {
  static instance;
  constructor() {
    // your logic here
  }
  static getInstance() {
    if (Singleton.instance) {
      return Singleton.instance;
    }
    Singleton.instance = new Singleton();
    return Singleton.instance;
  }
}

```

* every time we call  `Singleton.getInstance()`, we get the same object.

* By making the Singleton constructor private, we can only call it from within the  `getInstance` function.

## If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

* if we have third-party Middlewares

* Install the Node.js module for the required functionality, then load it in the app at the application level or at the router level

* Example: **body-parser**

* All middlewares will populate the `req.body` property with the parsed body when the `Content-Type` request header.

## Document the following Vocabulary Terms

* Router Middleware: Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express and load router-level middleware by using the router.use() and router.METHOD() functions.

* Dynamic Module Loading: is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory.

* Singleton Pattern:  is an object which can only be instantiated one time. Repeated calls to its constructor return the same instance and in this way one can ensure that they don't accidentally create, two Users in a single User application.

* CRUD -> REST Method Matches: CRUD stands for Create, Read, Update, and Delete, which are four primitive database operations, these operations map well to the HTTP verbs most frequently used in REST, POST,GET,PUT, PATCH and DELETE

* Mock Testing: is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules,In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.
