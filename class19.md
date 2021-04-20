# AWS: Events

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

Serverless API: is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers. A serverless application runs in stateless compute containers that are event-triggered, ephemeral (may last for one invocation), and fully managed by the cloud provider.

Triggers: are procedures that are stored in the database and are implicitly run, or fired, when something happens. Traditionally, triggers supported the execution of a PL/SQL block when an INSERT , UPDATE , or DELETE occurred on a table or view. Triggers support system and other data events on DATABASE and SCHEMA .

Dynamo vs Mongo
Dynamo: is a visual programming tool used to define relationships and create algorithms that then can be used to generate geometry in 3D space and to process data.
MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas.

Dynamoose vs Mongoose
Dynamoose: is an open-source modeling tool for Amazon's DynamoDB.
Mongoose:  is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB

### Preparation Materials

Amazon Simple Queue Service (Amazon SQS) is a pay-per-use web service for storing messages in transit between computers. Developers use SQS to build distributed applications with decoupled components without having to deal with the overhead of creating and maintaining message queues.

Amazon Simple Notification Service (Amazon SNS) is a managed service that provides message delivery from publishers to subscribers (also known as producers and consumers). Publishers communicate asynchronously with subscribers by sending messages to a topic, which is a logical access point and communication channel. Clients can subscribe to the SNS topic and receive published messages using a supported endpoint type, such as Amazon Kinesis Data Firehose, Amazon SQS, AWS Lambda, HTTP, email, mobile push notifications, and mobile text messages (SMS).

#### Resources:
1. hackernoon.com
2. docs.oracle.com
3. Wikipedia
4. medium.com
5. searchaws.techtarget.com
6. docs.aws.amazon.com