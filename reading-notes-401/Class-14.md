# Readings: Event Driven Architecture

* Event-driven architecture (EDA) is a software architecture paradigm promoting the production, detection, consumption of, and reaction to events.

* An event can be defined as "a significant change in state".[1] For example, when a consumer purchases a car, the car's state changes from "for sale" to "sold". A car dealer's system architecture may treat this state change as an event whose occurrence can be made known to other applications within the architecture. From a formal perspective, what is produced, published, propagated, detected or consumed is a (typically asynchronous) message called the event notification, and not the event itself, which is the state change that triggered the message emission. Events do not travel, they just occur. However, the term event is often used metonymically to denote the notification message itself, which may lead to some confusion. This is due to Event-Driven architectures often being designed atop message-driven architectures, where such communication pattern requires one of the inputs to be text-only, the message, to differentiate how each communication should be handled.

## What’s the difference between a FIFO and a standard queue?

* Standard queues guarantee that a message is delivered at least once and duplicates can be introduced into the queue. FIFO queues ensure a message is delivered exactly once and remains available until a consumer processes and deletes it

## How can the server be assured a message was properly received?

* to get a response from the client that the message was received

## What classic design pattern is best represented by event driven programming?

* The Observer Pattern is an appropriate design pattern to apply in any situation

## How do you test an event driven system?

* Effective logging in the event driven system and use unit test

## Document the following Vocabulary Terms

* FIFO Queue: are designed to enhance messaging between applications when the order of operations and events is critical, or where duplicates can't be tolerated.

* Pub/Sub: is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic. Pub/sub messaging can be used to enable event-driven architectures, or to decouple applications in order to increase performance, reliability and scalability.
