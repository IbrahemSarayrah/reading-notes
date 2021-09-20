# Reading: Component Lifecycle / useEffect() Hook

* lifecycle of a component can be defined as the series of methods that are invoked in different stages of the component's existence.

* What does useEffect do? By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.

* Does useEffect run after every render? Yes! By default, it runs both after the first render and after every update.

## Why do we not need more .html pages in a multi-page React app?

* Because React is not designed to develop multi-page websites. So, we need to create multiple routes to handle multiple views.

## If we wanted a component to show up on every page, where would we put it and why?

* Inside a `<Route />` and the React Router, is dynamic and client-side routing, allows us to build a single-page web application with navigation without the page refreshing as the user navigates, and we can  render component in every page.

## What does routing do with the components that were rendered when a new route is requested

* React Router uses component structure to call components, which display the appropriate information,
every time a route is requested we call the components and render it

## What does props.children contain?

* use props.children on components that represent ‘generic boxes’ and that ‘don’t know their children ahead of time’, and it is used to display whatever that include between the opening and closing tags when invoking a component.

## How do useState() and this.setState() differ?

* The setState function is used to handle the state object in a React class and `this.setState()` this is how we are setting the state in a class component, and Using state in a class component requires the building of a state object. This state object is then modified by calling this.setState("new state").

* useState() is aFunctional Component, With a functional component, we can use React hooks, specifically the `useState()` hook. This simplifies the creation of a state component and the function that updates it.

## Document the following Vocabulary Terms

* State Hook: Hook state is the new way of declaring a state in React app. Hook uses useState() functional component for setting and retrieving state.

* Mounting and Un-Mounting:
>
> Mounting is the process of outputting the virtual representation of a component into the final UI representation (e.g. DOM or Native Components).
>
> Un-Mounting is the last function to be called immediately before the component is removed from the DOM.
>