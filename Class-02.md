# React lifecycle

* React define components as classes or functions, the methods that you are able to use on these are called lifecycle events.

![React Lifecycle Events](https://miro.medium.com/max/2800/0*0saPKFiTUk6W3FYp)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

* render happens first

2. What is the very first thing to happen in the lifecycle of React?

* The constructor for a React component is called before it is mounted

3. The Order in React Lifecycle Events :

> 1. constructor
> 2. render
> 3. React Updates
> 4. componentDidMount
> 5. componentWillUnmount

4. What does componentDidMount do? 

* This method is invoked immediately after a component is mounted, its load anything using a network request or initialize the DOM

## Props and State

#### What types of things can you pass in the props?

* **Props** are arguments passed into React components like an arguments paased to a function.

#### What is the big difference between props and state?

* **Props** are passed into components and handle outside the components and updated outside the components.
* **State** are handle inside the components and updated inside components.

#### When do we re-render our application?

* When we change the state inside the application it will re-render the section of the application

#### What are some examples of things that we could store in state?

* inside a **form** that get updated by the user we store the value and store the value when changed.

* we can update a counter based in a user input we store it inside the state.

## Things I want to know more about :

* learn more about state and props.