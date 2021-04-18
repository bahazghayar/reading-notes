# AWS: Cloud Servers

#### Review, Research, and Discussion

* What’s the difference between a FIFO and a standard queue?
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.

* How can the server be assured a message was properly received?
When having an event in the client side to emit what received from the server.

* What classic design pattern is best represented by event driven programming?
The observer-pattern

* How do you test an event driven system?
write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a different part of your application.
Unit tests are the most basic tests you will write. The SUT in this case is typically an individual class.
Service tests, as the name suggests, treat the entire service as the SUT, and increasingly, in microservice architectures this is where the bulk of automated testing occurs.

#### Terms

* Server: a computer that serves information to other computers. These computers, called clients, can connect to a server through either a local area network or a wide area network, such as the internet. A server is a vital piece of your IT infrastructure.

* Pub/Sub: is a messaging pattern where senders of messages, called publishers, do not program the messages to be sent directly to specific receivers, called subscribers, but instead categorize published messages into classes without knowledge of which subscribers, if any, there may be. Similarly, subscribers express interest in one or more classes and only receive messages that are of interest, without knowledge of which publishers, if any, there are.

* WRRC: The request/response cycle traces how a user's request flows through the app. Understanding the request/response cycle is helpful to figure out which files to edit when developing an app (and where to look when things aren't working).

#### Preparation Materials

Virtual Machine Manager (VMM): Also called a “hypervisor,” this is one of many hardware virtualization techniques that allow multiple operating systems, termed guests, to run concurrently on a host computer. It is so named because it is conceptually one level higher than a supervisory program. The hypervisor presents to the guest operating systems a virtual operating platform and manages the execution of the guest operating systems. Multiple instances of a variety of operating systems may share the virtualized hardware resources.
Hypervisors are installed on server hardware whose only task is to run guest operating systems. Non-hypervisor virtualization systems are used for similar tasks on dedicated server hardware, but also commonly on desktop, portable, and even handheld computers. The term is often used to describe the interface provided by the specific cloud-computing functionality infrastructure as a service (IaaS).

Examples: 
* VirtualBox
* vmware

Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.


##### Resources:
1. www.infotech.co.uk
2. Wikipedia
3. www.codecademy.com
4. aws.amazon.com
5. medium.com
6. www.infoblox.com
