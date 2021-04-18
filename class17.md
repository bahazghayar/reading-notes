# AWS: S3 and Lambda

### Review, Research, and Discussion

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

### Terms

Server Instances: is a collection of SQL Server databases which are run by a solitary SQL Server service or instance. The details of each server instance can be viewed on the service console which can be web-based or command-line based.

Containers: is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. ... Available for both Linux and Windows-based applications, containerized software will always run the same, regardless of the infrastructure.

Cloud Services: refers to a wide range of services delivered on demand to companies and customers over the internet.

Cloud Architecture: refers to the various components in terms of databases, software capabilities, applications, etc. engineered to leverage the power of cloud resources to solve business problems. Cloud architecture defines the components as well as the relationships between them.

AWS: Amazon Web Services is the world’s most comprehensive and broadly adopted cloud platform, offering over 200 fully featured services from data centers globally. Millions of customers—including the fastest-growing startups, largest enterprises, and leading government agencies—are using AWS to lower costs, become more agile, and innovate faster.


EC2/Beanstalk vs Heroku:
Heroku: is a platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.
EC2/Beanstalk: is an easy-to-use service for deploying and scaling web applications and services developed with Java, . NET, PHP, Node. ... At the same time, you retain full control over the AWS resources powering your application and can access the underlying resources at any time.

### Preparation Materials

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as data lakes, websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics. Amazon S3 provides easy-to-use management features so you can organize your data and configure finely-tuned access controls to meet your specific business, organizational, and compliance requirements. Amazon S3 is designed for 99.999999999% (11 9's) of durability, and stores data for millions of applications for companies all around the world.

Benefits:
* Industry-leading performance, scalability, availability, and durability.
* Wide range of cost-effective storage classes.
* Unmatched security, compliance, and audit capabilities.
* Easily manage data and access controls.
* Query-in-place and process on-request.
* Most supported cloud storage service.

AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.

Benefits:
* No servers to manage
* Continuous scaling
* Cost optimized with millisecond metering
* Consistent performance at any scale

Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast delivery of Internet content. A CDN allows for the fast transfer of data needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos.

#### Resources:
1. www.techopedia.com
2. www.docker.com
3. www.citrix.com
4. www.hcltech.com
5. aws.amazon.com
6. www.heroku.com
