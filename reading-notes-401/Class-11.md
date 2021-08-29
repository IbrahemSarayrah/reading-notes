# Readings: Event Driven Applications

## Event Driven Applications

* Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.

* Every time you interact with a webpage through it’s user interface, an event is happening. When you `click` a button a click event is triggered. When you press a key a `keydown` event is triggered. These events have associated functions that, when triggered, are executed to make a change to the user interface in some way.

* Event-Driven Programming makes use of the following concepts:

>
> An Event Handler is a callback function that will be called when an event is triggered.
>
> A Main Loop listens for event triggers and calls the associated event handler for that event.
>

* EventEmitter :

>
> Node.js natively provides us with a useful module called EventEmitter that allows us to get started incorporating Event-Driven Programming
>
> We access the EventEmitter class through the `events` module. Once imported we’ll need to create a new object from the class to start using it.
>

```
const EventEmitter = require('events').EventEmitter;
const myEventEmitter = new EventEmitter;
```

## Why is access control important?

* Access controls limit access to information and information processing systems. When implemented effectively, they mitigate the risk of information being accessed without the appropriate authorisation, unlawfully and the risk of a data breach.

## Describe an application that would need access control

* Role Based Access Control grants access based on a user’s role and implements key security principles, such as “least privilege” and “separation of privilege.” Thus, someone attempting to access information can only access data that’s deemed necessary for their role.

## What is a role used for?

* The roles  refer to the levels of access that employees have to the network, Employees are only allowed to access the information necessary to effectively perform their job duties. Access can be based on several factors, such as authority, responsibility, and job competency. In addition, access to computer resources can be limited to specific tasks such as the ability to view, create, or modify a file.

## Why is role based access control more scalable than discretionary or mandatory access control?

* The main advantage of role-based access control is that it’s been widely adopted and allows small- to medium-sized organizations to eliminate implementing access controls on an individual basis.

* can assign a single user to multiple roles

## Document the following Vocabulary Terms

* Authorization: a security mechanism to determine access levels or user/client privileges related to system resources

* Role Based Access Control: s a security paradigm whereby users are granted access to resources based on their role in the company.

* Capabilities: is a fundamentally better approach to Identity and access management today’s ACL framework for creating secure Identity and Access Management system.
