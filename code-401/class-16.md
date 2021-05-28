# AWS: Cloud Servers

1. Describe the Web-Request-Response-Cycle

   1. A user opens his browser, types in a URL, and presses Enter.
   2. When a user presses Enter, the browser makes a request for that URL.
   3. The request hits the Rails router (config/routes.rb). The router maps the URL to the correct controller and action to handle the request.
   4. The action receives the request and passes it on to the view.
   5. The view renders the page as HTML.
   6. The controller sends the HTML back to the browser. The page loads and the user sees it.

   ![request-response-cycle](img-class-16/request-response-cycle.PNG)

2. Explain what a “server” is, as it relates to the WRRC
is a computer or system that provides resources, data, services, or programs to other computers

3. What does it mean to “deploy” an application?

putting it on a Web server so that it can be used either through the Internet or an intranet. This Web server might be your local UNIX system, while you develop and debug your application to check that the application is performing as you expect, or a different UNIX system for users of your application.

`Server`is a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients".

`Pub/Sub` Publish/subscribe messaging, or pub/sub messaging, is a form of asynchronous service-to-service communication used in serverless and microservices architectures. In a pub/sub model, any message published to a topic is immediately received by all of the subscribers to the topic.

Virtual Machines what is a virtual machine manager? also called a hypervisor it's a type of software that allows us to run an operating system within another operating system inception

example :

* virtual box

* vm ware

* Virtualization : uses software to create an abstraction layer over computer hardware that allows the hardware elements of a single computer—processors, memory, storage and more—to be divided into multiple virtual computers, commonly called virtual machines (VMs). Each VM runs its own operating system (OS) and behaves like an independent computer, even though it is running on just a portion of the actual underlying computer hardware.

* cloud is a metaphor for a global network of remote servers that operates as a single ecosystem, commonly associated with the Internet.

  * Cloud computing is the on-demand availability of computer system resources, especially data storage (cloud storage) and computing power, without direct active management by the user. The term is generally used to describe data centers available to many users over the Internet.

* AWS

Cloud computing gives you access to servers, storage, databases, and a broad set of application services over the Internet. A cloud services provider such as Amazon Web Services, owns and maintains the network-connected hardware required for these application services, while you provision and use what you need via a web application.

Types of Cloud Computing. Cloud computing has three main types that are commonly referred to as Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). .

Amazon Web Services (AWS), Google Cloud Platform (GCP), and Microsoft Azure are among the best players in the cloud computing world.
