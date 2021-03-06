# Readings: Redux - Combined Reducers

* combineReducers is simply a utility function to simplify the most common use case when writing Redux reducers. You are not required to use it in your own application, and it does not handle every possible scenario. It is entirely possible to write reducer logic without using it, and it is quite common to need to write custom reducer logic for cases that combineReducer does not handle.

* While Redux itself is not opinionated about how your state is organized, combineReducers enforces several rules to help users avoid common errors.

* combineReducers takes an object full of slice reducer functions, and creates a function that outputs a corresponding state object with the same keys. This means that if no preloaded state is provided to createStore, the naming of the keys in the input slice reducer object will define the naming of the keys in the output state object. The correlation between these names is not always apparent, especially when using ES6 features such as default module exports and object literal shorthands.

## Why choose Redux instead of the Context API for global state?

* Redux works around the idea of having a central state called a store. To change the state, a component has to dispatch an action. The action is then passed on to the reducer, which changes the state of our application, and we use redux in complex apps.

## What is the purpose of a reducer?

* In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state.

## What does an action contain?

* Actions are the only source of information for the store in redux and It carries a payload of information from your application to store.

## Why do we need to copy the state in a reducer?

* redux only requires our reducers to stay pure. If the new state is different, the reducer must create new object, and making a copy is a way to describe the unchanged part.

## Document the following Vocabulary Terms

* immutable state: If an object is immutable, any changes that need to be made to it within a function must be made to a copy of the object.

* time travel in redux: is the ability to move back and forth among the previous states of an application and view the results in real time.

* action creator: is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store's dispatch() function.

* reducer: In Redux, a reducer is a pure function that takes an action and the previous state of the application and returns the new state.

* dispatch: dispatch is a function of the Redux store. You call store. dispatch to dispatch an action. This is the only way to trigger a state change. With React Redux, your components never access the store directly - connect does it for you.
