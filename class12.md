# Review, Research, and Discussion

#### What is the benefit of transforming data into packets?
##### Packets are intended to transfer data reliably and efficiently. Instead of transferring a large file as a single block of data, sending smaller packets helps ensure each section is transmitted successfully. If a packet is not received or is "dropped," only the dropped packet needs to be resent.

#### UDP is often refereed to as a connectionless protocol. Why is this?
##### No connection needs to be established between the source and destination before you transmit data.

#### Can a socket server application have multiple socket connections?
##### Yes

#### Can a socket connection application be connected to multiple socket servers?
##### No


#### Can an application be both a socket server and a socket connection?
##### Yes

### Term

##### Observer Pattern:is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

##### Listener: is a procedure or function in a computer program that waits for an event to occur. The listener is programmed to react to an input or signal by calling the event's handler. The term event listener is often specific to Java and JavaScript.

##### Event Handler: is a callback routine that operates asynchronously and handles inputs received into a program.

##### Event Driven Programming: is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads.

##### Event Loop: is a programming construct or design pattern that waits for and dispatches events or messages in a program. The event loop works by making a request to some internal or external "event provider" (that generally blocks the request until an event has arrived), then calls the relevant event handler ("dispatches the event"). The event loop is also sometimes referred to as the message dispatcher, message loop, message pump, or run loop.

##### Event Queue: is a repository where events from an application are held prior to being processed by a receiving program or system. Event queues are often used in the context of an enterprise messaging system.

##### Call Stack: is a stack data structure that stores information about the active subroutines of a computer program. This kind of stack is also known as an execution stack, program stack, control stack, run-time stack, or machine stack, and is often shortened to just "the stack"

##### Emit/Raise/Trigger: 
* ###### An event can be "emitted" (or in other words, the corresponding callback be called) multiple times or you can choose to only listen for the first time it is emitted.
* ###### The Raise Event operation is a request by the developer to execute handlers that are defined for an event at a given time. The handler can either be user-defined or a uniPaaS built-in handler. Invoking an Internal Handler.
* ###### Triggering event is a tangible or intangible barrier or occurrence which, once breached or met, causes another event to occur. Triggering events include job loss, retirement, or death, and are typical for many types of contracts.

##### Subscribe: is an option offered by product vendors or service providers that allows customers to gain access to products or services. Most subscription-based models are paid services, which require a customer to pay a subscription fee to access and use a particular product or service.

##### database: is an organized collection of data, generally stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques.
<br>

## Socket.io
### Preview

#### WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

#### Socket.IO is a JavaScript library for real-time web applications. It enables real-time, bi-directional communication between web clients and servers. It has two parts: a client-side library that runs in the browser, and a server-side library for node.js. Both components have an identical API.

#### Why Socket.IO?
##### to use open connections to facilitate realtime communication, still a relatively new phenomenon at the time. Socket.IO allows bi-directional communication between client and server.

#### Real-time applications
1. ##### Instant messengers
2. ##### Push Notifications
3. ##### Collaboration Applications 
4. ##### Online Gaming 



##### Resources:
1. Wikipedia
2. www.computerhope.com
3. searchapparchitecture.techtarget.com
4. www.techopedia.com
5. www.investopedia.com
6. stackoverflow.com
7. techterms.com
8. www.sciencedirect.com
9. socket.io
10. www.tutorialspoint.com