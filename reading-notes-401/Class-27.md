# Reading: useState() Hook

* Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don't work inside classes — they let you use React without classes.

* The useState function is a built in hook that can be imported from the react package. It allows you to add state to your functional components. Using the useState hook inside a function component, you can create a piece of state without switching to class components.

## How does React differ from vanilla JS/HTML/CSS?

* React is a Javascript library used for building user interfaces. It allows us to make complex UIs from isolated pieces of code called "components".

* React comes in with a great feature i.e its own virtual DOM. The virtual DOM is a shortcut to bypass the manual work. It is a lightweight copy of the actual DOM.

* React use JSX, and JSX stands for JavaScript XML. It is simply a syntax extension of JavaScript. It allows us to directly write HTML in React

## What is the primary difference between a function component and a class component?

* function component:

1. A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element.
2. There is no render method used in functional components.
3. Also known as Stateless components as they simply accept data and display them in some form, that they are mainly responsible for rendering UI.
4. React lifecycle methods (for example, componentDidMount) cannot be used in functional components.

* class component

1. A class component requires you to extend from React. Component and create a render function which returns a React element.
2. It must have the render() method returning HTML
3. Also known as Stateful components because they implement logic and state.
4. React lifecycle methods can be used inside class components (for example, componentDidMount).

## Document the following Vocabulary Terms

* Functional Components: a function that takes props and returns JSX. They do not have state or lifecycle methods. Functional components are easier to read, debug, and test. They offer performance benefits, decreased coupling, and greater reusability.

* Children / Child Components: Children allow to pass components as data to other components
