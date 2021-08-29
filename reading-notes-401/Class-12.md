# Readings: Socket.io

* WebSocket is the communication Protocol that provides bidirectional communication between the Client and the Server over a TCP connection; WebSocket remains open all the time, so they allow real-time data transfer. When clients trigger the request to the server, it does not close the connection on receiving the response; it rather persists and waits for the Client or server to terminate the request.

* Socket.IO enables real-time bidirectional event-based communication. It works on every platform, browser or device, focusing equally on reliability and speed. Socket.IO is built on top of the WebSockets API (Client side) and Node.js. It is one of the most depended upon library on npm (Node Package Manager).

## What is the benefit of transforming data into packets?

* The main purpose of networking is to share data between computers. A file has to be broken up into small chunks of data known as data packets in order to be transmitted over a network.

## UDP is often refereed to as a connectionless protocol. Why is this?

* A connectionless network protocol is an alternative type of data transmission in which a network endpoint sends an IT signal automatically, without determining whether a receiver exists or stands ready to receive it.

* UDP is a connectionless protocol. No connection needs to be established between the source and destination before you transmit data.

## Can a socket server application have multiple socket connections?

* Yes. Multiple listening TCP sockets, all bound to the same port, can co-exist, provided they are all bound to different local IP addresses. Clients can connect to whichever one they need to.

## Can a socket connection application be connected to multiple socket servers?

* A server socket listens on a single port. ... Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

## Can an application be both a socket server and a socket connection?

* You can not combine server and client sockets into one, because a TCP/IP connection goes from a source port to a destination port, with each having unique port numbers.

## Document the following Vocabulary Terms

* Observer Pattern: is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

* Listener: is a function that is invoked when a particular event occurs, typically with an event object containing information about the event.

* Event Handler: is a callback routine that operates asynchronously and handles inputs received into a program (events)

* Event Driven Programming:  is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.

* Event Loop: is a programming construct or design pattern that waits for and dispatches events or messages in a program.

* Event Queue: is a repository where events from an application are held prior to being processed by a receiving program or system.

* Call Stack: The call stack is a LIFO (Last In, First Out) stack. The event loop continuously checks the call stack to see if there's any function that needs to run. While doing so, it adds any function call it finds to the call stack and executes each one in order.

* Emit/Raise/Trigger: The emit() function raises the specified event. First parameter is name of the event as a string and then arguments. An event can be emitted with zero or more arguments.

* database: is an organized collection of structured information, or data, typically stored electronically in a computer system.
