# Reading: Context API - Behaviors

## When you have multiple contexts, what component type should you use (class/function) and why?

* The ContextType property on a class component can be assigned a Context object created by React. createContext() method. This property and consume the nearest current value of the context using this, but if there is more than one ContextType it will not work so we can use useContext Hook.

## What are some good use cases for using the Context API for global state?

* Context is primarily used when some data needs to be accessible by many components at different nesting levels, such as the current authenticated user, theme, or preferred language.

## How can you best test context?

* The best way to test Context is to make our tests unaware of its existence and avoiding mocks. We want to test our components in the same way that developers would use them (behavioral testing) and mimic the way they would run in our applications (integration testing).

## Document the following Vocabulary Terms

* context: is a way for a React app to effectively produce global variables that can be passed around.

* useContext(): is a hook used to create common data that can be accessed throughout the component hierarchy without passing the props down manually to each level.

* Static context: block belongs to the class and these will be loaded into the memory along with the class.
