# Reading: `<Login />` and `<Auth />`

* Role-based access control (RBAC) restricts network access based on a person's role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

## Why is the Context API useful?

* The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application, and Context API is a way to enable components to share some data without explicitly passing via each component manually.

## Can a component outside of a provider get its context?

* To access a React context outside of the render function, we can use the useContext hook. We create the UserContext by calling the React. createContext method with a default context value. Then in the Users component, we call the useContext hook with UserContext to accxess the current value of UserContext.

## What are some common use cases for using the Context API?

* Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.

## Describe “Context Hell”

* Like the callback hell, usual when jQuery was used for everything, the React Context hell is the nasty code you get taking advantage of the React Context API.

## Document the following Vocabulary Terms

* global state: is the data that is shared between all the components

* global context: share data that can be considered “global” for a tree of React components

* provider: Provider React component that allows consuming components to subscribe to context changes.

* consumer: A React component that subscribes to context changes.
