# React and Components

### What is a component?

* A component is a **software object**, intended to interact with other **components**, 
encapsulating certain functionality or a set of functionalities and the component is  portable, replaceable, and reusable

* The software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only and can be deployed independently and is subject to composition by third parties.

* A component can have three different views − object-oriented view, conventional view, and process-related view.

### What are the charactistics of a component?

* **Reusability** to be reused in different situations in different applications.

* **Replaceable** Components may be freely substituted with other similar components.

* **Not context specific** Components are designed to operate in different environments and contexts.

* **Extensible** A component can be extended from existing components to provide new behavior.

* **Encapsulated** A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

* **Independent** Components are designed to have minimal dependencies on other components.

### What are the advantages of using component based architecture?

* **Ease of deployment** As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

* **Reduced cost** The use of third-party components allows you to spread the cost of development and maintenance.

* **Ease of development** Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

* **Reusable** Components can be used to spread the development and maintenance cost across several applications or systems.

* **Modification of technical complexity** A component modifies the complexity through the use of a component container and its services.

* **Reliability** The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

* **System maintenance and evolution** Easy to change and update the implementation without affecting the rest of the system.

* **Independent** Independency and flexible connectivity of components.

### What is props short for?

* **Props**  is a special keyword in React, which stands for properties and is being used for **passing data from one component to another**.

### How are props used in React?

> 1. Defining Attribute & Data : We can define our own attributes & assign values with interpolation { }:
>
> 2. Passing Data using Props : we pass props into a React component and props bring all the necessary data.
>
> 3. Rendering Props Data : we will render the props object by using string interpolation.

* Props returns back an object. In JavaScript, we can access to object elements with **dot(.) notation.**

### What is the flow of props?

* the data with props are being passed in a **uni-directional** flow. (one way from parent to child)

* props data is **read-only**, which means that data coming from the parent should not be changed by child components.

## Things I want to know more about

* learn more about React

* learn more about component

* learn more about Props
