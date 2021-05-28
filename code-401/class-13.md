# Message Queues

1. What does it mean that web sockets are bidirectional? Why is this useful?  Data flows both ways (full-duplex), a web socket can both send and receive which is useful because it allows data to be sent and received on the same channel.

2. What happens when a client emits an event?The event will be sent to the server, which will be listening for the event if already connected

3. What happens when a server emits an event?client is listening for the event will respond.

`Socket`one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to.

`Web Socket` is an advanced technology that makes it possible to open a two-way interactive communication session between the user's browser and a server.

`Socket.io`is a library that enables real-time, bidirectional and event-based communication between the browser and the server

`Client`A system that uses remote services from a server.

`server`A system that provides services to other systems in its network.

`OSI Model` (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system.

`TCP Model`is a communications standard that enables application programs and computing devices to exchange messages over a network. It is designed to send packets across the internet and ensure the successful delivery of data and messages over networks.

`TCP`is one of the main protocols of the Internet protocol suite.

`UDP`The User Datagram Protocol, or UDP, is a communication protocol used across the Internet for especially time-sensitive transmissions such as video playback or DNS lookups. It speeds up communications by not formally establishing a connection before data is transferred.

`Packets`is a small segment of a larger message. Data sent over computer networks, such as the Internet, is divided into packets. These packets are then recombined by the computer or device that receives them.

## Socket.io Chat example

Sockets have traditionally been the solution around which most real-time chat systems are architected, providing a bi-directional communication channel between a client and a server
The server can push messages to clients
Whenever you write a chat message, the idea is that the server will get it and push it to all other connected clients

Rooms A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients.

    * can call join to subscribe the socket to a given channel
    * Default room : Each Socket in Socket IO is identified by a random, unguessable, unique identifier Socket#id. each socket automatically joins a room identified by its own id.
