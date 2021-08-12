# Thinking in React

## How would you break a mock into a component heirarchy?

1. draw boxes around every component (and subcomponent) in the mock and give them all names

2. and give the layer names and may end up being the names of the React components

## What is the single responsibility principle and how does it apply to components?

* every module, class or function in a computer program should have responsibility over a single part of that program's functionality

* the component should ideally only do one thing. and if it ends up growing should be decomposed into smaller subcomponents.

## What does it mean to build a ‘static’ version of your application?

* to build components that reuse other components and pass data using props. 

* props are a way of passing data from parent to child and State is reserved only for interactivity.

## Once you have a static application, what do you need to add?

* build top-down or bottom-up, we can either start with building the components higher up in the hierarchy, on larger projects, it’s easier to go bottom-up

* we will have a library of reusable components that render the data model, and The components will only have render() methods

## What are the three questions you can ask to determine if something is state?

1. Is it passed in from a parent via props? If so, it probably isn’t state.

2. Does it remain unchanged over time? If so, it probably isn’t state.

3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

* Identify every component that renders something based on that state.

* Find a common owner component (a single component above all the components that need the state in the hierarchy).

* Either the common owner or another component higher up in the hierarchy should own the state.

* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component
