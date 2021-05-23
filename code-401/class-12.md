# Socket.io

1. What is the benefit of transforming data into packets?
Packets are the basic units of communication over a TCP/IP network. Devices on a TCP/IP network divide data into small pieces, allowing the network to accommodate various bandwidths, to allow for multiple routes to a destination, and to retransmit the pieces of data which are interrupted or lost. Each piece is a packet, a term interchangeable with datagram.

2. UDP is often refereed to as a connectionless protocol. Why is this?It is known as a datagram protocol because it is analogous to sending a letter where you don't acknowledge receipt.

3. Can a socket server application have multiple socket connections?
A server socket listens on a single port. All established client connections on that server are associated with that same listening port on the server side of the connection. An established connection is uniquely identified by the combination of client-side and server-side IP/Port pairs. Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs, and the server would be able to handle as many clients as available system resources allow it to.

4. Can a socket connection application be connected to multiple socket servers?
A single client-side server should only connect to one socket server.

`Observer Pattern`  is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.
`Listener` a function that listens for an event to happened

`Event Handler` callback function run when event happened

`Event-Driven Programming` programming paradigm in which the flow of the program is determined by events such as user actions, message passing

`Event Loop` responsible for executing the code, collecting and processing events, and executing queued sub-tasks. This model is quite different from models in other languages like C and Java..

`database` is a collection of information that is organized so that it can be easily accessed, managed and updated.
