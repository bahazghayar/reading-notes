# Message Queues


### Review, Research, and Discussion

What does it mean that web sockets are bidirectional? Why is this useful?
Bidirectional is a communications mode that is capable of transmitting data in both directions (send and receive), but not at the same time.
It is useful because it's allows to send and receive data on the same channel.

Does socket.io use HTTP? Why?
Yes, the initial connection setup it done over HTTP. Also, a socket.io server will attach to an HTTP server so it can serve its own client code through socket.io.

What happens when a client emits an event?

What happens when a server emits an event?

What happens if a client “misses” an event?

How can we mitigate this?


### Term

**Socket**: is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to. An endpoint is a combination of an IP address and a port number.

**Web Socket**: is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

**Socket.io**: is a JavaScript library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for node.js. Both components have an identical API.

**Client**: is a piece of computer hardware or software that accesses a service made available by a server as part of the client–server model of computer networks. The server is often (but not always) on another computer system, in which case the client accesses the service by way of a network.

**Server**: is a computer that serves information to other computers. These computers, called clients, can connect to a server through either a local area network or a wide area network, such as the internet. A server is a vital piece of your IT infrastructure.

**OSI Model**: (Open Systems Interconnection Model) is a conceptual framework used to describe the functions of a networking system. The OSI model characterizes computing functions into a universal set of rules and requirements in order to support interoperability between different products and software. In the OSI reference model, the communications between a computing system are split into seven different abstraction layers: Physical, Data Link, Network, Transport, Session, Presentation, and Application.

**TCP Model**: is not exactly similar to the OSI model. The TCP/IP model consists of five layers: the application layer, transport layer, network layer, data link layer and physical layer. ... TCP/IP is a hierarchical protocol made up of interactive modules, and each of them provides specific functionality.

**TCP**: Transmission Control Protocol

**UDP**: User Datagram Protocol is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network. Prior communications are not required in order to set up communication channels or data paths.

**Packets**: is a small amount of data sent over a network, such as a LAN or the Internet. Similar to a real-life package, each packet includes a source and destination as well as the content (or data) being transferred.







### Resources: 
1. docs.oracle.com
2. Wikipedia
3. www.infotech.co.uk
4. www.forcepoint.com
5. www.javatpoint.com
6. techterms.com
7. www.computerhope.com
8. www.stackoverflow.com