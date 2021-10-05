# Readings: Redux - Additional Topics

* The Redux Toolkit package is intended to be the standard way to write Redux logic. It was originally created to help address three common concerns about Redux:

>Configuring a Redux store is too complicated
>
>I have to add a lot of packages to get Redux to do anything useful
>
>Redux requires too much boilerplate code

## What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

* The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method of a Higher Order Component that wraps your app.

## When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

* Redux store doesn't know anything about async logic. It only knows how to synchronously dispatch actions, update the state by calling the root reducer function, and notify the UI that something has changed. Any asynchronicity has to happen outside the store, and we export the action creators that return a function(thunk) which takes the store's dispatch method

## Document the following Vocabulary Terms

* middleware: are functions that have access to the request object ( req ), the response object ( res ), and the next function in the application's request-response cycle.

* thunk: is a middleware that allows you to call the action creators that return a function(thunk) which takes the store's dispatch method as the argument and which is afterwards used to dispatch the synchronous action after the API or side effects has been finished.
