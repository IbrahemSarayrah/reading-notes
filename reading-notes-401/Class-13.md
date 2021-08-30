# Readings: Message Queues

* A message queue is a form of asynchronous service-to-service communication used in serverless and microservices architectures. Messages are stored on the queue until they are processed and deleted. Each message is processed only once, by a single consumer. Message queues can be used to decouple heavyweight processing, to buffer or batch work, and to smooth spiky workloads.

## What does it mean that web sockets are bidirectional? Why is this useful?

* Bidirectional means the data incoming and outgoing data flows over the same channel (sockets), this enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.

## Does socket.io use HTTP? Why?

* a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js.

## What happens when a client emits an event?

* The event gets passed to the server through websockets. Its a TCP connection from the browser to the server,the server can send real time data to the client.

## What happens when a server emits an event?

* The event gets passed from the server to the client.

## What happens if a client “misses” an event?

* Unhandled events will be ignored

## How can we mitigate this?

* we could avoid missing events by always having the handlers installed and then deciding in the handlers (based on other state) whether to do anything with the event or not.

## Document the following Vocabulary Terms

* Socket:  is one endpoint of a two way communication link between two programs running on the network. The socket mechanism provides a means of inter-process communication (IPC) by establishing named contact points between which the communication take place.

* Web Socket: is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

* Socket.io: is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

* Client: is the software that runs on a user's web browser.

* Server: a computer or system that provides resources, data, services, or programs to other computers, known as clients, over a network. In theory, whenever computers share resources with client machines they are considered servers.

* OSI Model: The OSI Model (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system.

* TCP Model: defines how devices should transmit data between them and enables communication over networks and large distances.

* TCP: stands for Transmission Control Protocol a communications standard that enables application programs and computing devices to exchange messages over a network. It is designed to send packets across the internet and ensure the successful delivery of data and messages over networks.

* UDP: The User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups. It speeds up communications by not formally establishing a connection before data is transferred.

* Packets: In networking, a packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.
