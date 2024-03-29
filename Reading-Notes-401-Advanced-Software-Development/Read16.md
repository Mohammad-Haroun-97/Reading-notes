# Read - 16 :  AWS: Cloud Servers

## Describe the Web-Request-Response-Cycle

As we start to build out web applications, it is important to be able to visualize the way information flows through the system; typically called the Request/Response Cycle.
First a user gives a client a URL, the client builds a request for information (or resources) to be generated by a server. When the server receives that request, it uses the information included in the request to build a response that contains the requested information. Once built, that response is sent back to the client in the requested format, to be rendered to the user.
It is our job as web developers to build out and maintain servers that can successfully build responses based on standardized requests that will be received. But, what does a standard request look like? We need to know that before we can start building servers that will respond successfully.
The standard, or protocol we use is HTTP.

* HTTP Requests and Responses
The HyperText Transfer Protocol gives us rules about how messages should be sent around the Internet. The system that initiates a connection sends a “request”, and the system the answers sends a “response”.

## Explain what a “server” is, as it relates to the WRRC

On the opposite side of the communication channel, is the server, which serves the document as requested by the client. A server appears as only a single machine virtually: this is because it may actually be a collection of servers, sharing the load (load balancing) or a complex piece of software interrogating other computers (like cache, a DB server, or e-commerce servers), totally or partially generating the document on demand.

## What does it mean to “deploy” an application?

Deploying your application means putting it on a Web server so that it can be used either through the Internet or an intranet. ... To deploy your application onto a production Web server, you need to check: Server Web share paths and application URLs.

## Preparation Materials


### - Virtual Machines

Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps.<br>

Virtual machines (VMs) allow a business to run an operating system that behaves like a completely separate computer in an app window on a desktop. VMs may be deployed to accommodate different levels of processing power needs, to run software that requires a different operating system, or to test applications in a safe, sandboxed environment. <br>

The two types of virtual machines 
Users can choose from two different types of virtual machines—process VMs and system VMs:  <br>

A process virtual machine allows a single process to run as an application on a host machine, providing a platform-independent programming environment by masking the information of the underlying hardware or operating system. An example of a process VM is the Java Virtual Machine, which enables any operating system to run Java applications as if they were native to that system.   <br>

A system virtual machine is fully virtualized to substitute for a physical machine. A system platform supports the sharing of a host computer’s physical resources between multiple virtual machines, each running its own copy of the operating system. This virtualization process relies on a hypervisor, which can run on bare hardware, such as VMware ESXi, or on top of an operating system. <br>

### Amazon Elastic Compute Cloud

Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.

Amazon EC2 offers the broadest and deepest compute platform with choice of processor, storage, networking, operating system, and purchase model. We offer the fastest processors in the cloud and we are the only cloud with 400 Gbps ethernet networking. We have the most powerful GPU instances for machine learning training and graphics workloads, as well as the lowest cost-per-inference instances in the cloud. More SAP, HPC, Machine Learning, and Windows workloads run on AWS than any other cloud. Click here to learn What's New with Amazon EC2.

### AWS Elastic Beanstalk

AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed with Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.<br>

You can simply upload your code and Elastic Beanstalk automatically handles the deployment, from capacity provisioning, load balancing, auto-scaling to application health monitoring. At the same time, you retain full control over the AWS resources powering your application and can access the underlying resources at any time.<br>

There is no additional charge for Elastic Beanstalk - you pay only for the AWS resources needed to store and run your applications.<br>

