# Reading: Context API

* Context
>
> In a typical React application, data is passed top-down (parent to child) via props, but such usage can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.
>

* Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

## Describe use cases useState() vs useReducer()

* useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.

* useState does not automatically merge update objects, Another option is useReducer , which is more suited for managing state objects that contain multiple sub-values.

## Why do custom hooks need the use prefix?

* This is mainly to have an extra option for sharing state and logic between components, Custom hooks are normal JS functions, named with the prefix 'use', that can use hooks inside of it and contain a common stateful logic to be reused in other components.

## What do custom hooks usually do?

* Custom hooks allow us to have cleaner functional components, remove logic from the UI layer, and prevent code duplication by bringing common use cases to reusable hooks.

* Custom hooks are a handy way to encapsulate hook-related logic that can be re-used across components

## Using any list of custom hooks, research and name one that you think will be useful in your applications

* useRequireAuth,  is a way to redirect the user if they are signed out and trying to view a page that should require them to be authenticated.

## Describe how a hook that fetches API data might work

* The most accessible way to fetch data with React is using the Fetch API.

* To make a simple GET request with fetch we just need to include the URL endpoint to which we want to make our request. We want to make this request once our React component has mounted.

* we make our request within the useEffect hook, and we make sure to provide an empty dependencies array as the second argument, so that our request is only made once.

* The useEffect hook gets invoked as soon as the component is mounted. If we need the hook to rerun based on some prop or state changes, we’ll need to pass them to the dependency array (which is the second argument of the useEffect hook).

## Document the following Vocabulary Terms

* reducer: a reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer's job to return the new state based on that action.
