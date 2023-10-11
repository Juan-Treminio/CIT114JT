CIT114-Juan Treminio 
# Final Reading Notes 
## 1. Cloud Concepts Overview 

### Infrastructure as a Service (IaaS) 
It is an instant computing infrastructure, provisioned and managed over the Internet. 
Quickly scale up and down with demand and pay only for what you use. 

### Platform as a Service (PaaS) 
is a complete development and deployment environment in the cloud, with resources that enable you to deliver everything from simple cloud-based apps to sophisticated, cloud-enabled enterprise applications. You purchase the resources you need from a cloud service provider on a pay-as-you-go basis and access them over a secure Internet connection. 

### Software as a Service (SaaS) 
allows users to connect to and use cloud-based apps over the Internet.  
Common examples are email, calendaring, and office tools (such as Microsoft Office 365). 

### Business Drivers: 
#### 1. Capacity Planning - 
the process of determining and fulfilling future demands of an organization's IT resources, products, and services. 

#### 2. Cost Reduction – 
no need for investment to be funneled into infrastructure expansion. 

#### 3. Organizational Agility - 
the measure of an organization's responsiveness to change. 

### Risk and Challenges: 
#### 1. Increased Security Vulnerabilities - 
The moving of business data to the cloud means that the responsibility over data security becomes shared with the cloud provider. 

#### 2. Reduced Operational Governance Control - 
Cloud consumers are usually allotted a level of governance control that is lower than that over on-premises IT resources. 

####  3. Limited Portability Between Cloud Providers - 
It can be challenging to move from one cloud provider to another. 

#### 4. Multi-Regional Regulatory and Legal Issues 

 

 

## 2. Cloud Economics, Billing & Support 

#### Pay-as-you-go 
With AWS you only pay for what use, helping your organization remain agile, responsive and always able to meet scale demands. 

#### Pay less by using more 
With AWS, you can get volume based discounts and realize important savings as your usage increases. For services such as S3 and data transfer OUT from EC2, pricing is tiered, meaning the more you use, the less you pay per GB. 

### There are three fundamental drivers of cost with AWS: 
* Compute 
* Storage 
* Outbound data transfer 

Use the right pricing model for the job 

### AWS offers several pricing models depending on the product. These include: 

#### On Demand: 
means you pay for compute or database capacity with no long-term commitments or upfront payments. 

#### Dedicated Instances: 
run in a virtual private cloud (VPC) on hardware that’s dedicated to a single customer. 

#### Spot Instances: 
are an Amazon EC2 pricing mechanism that lets you purchase spare computing capacity with no upfront commitment at discounted hourly rates. 

#### Reservations: 
provide you with the ability to receive a greater discount, up to 75 percent, by paying for capacity ahead of time 

### Types of IT infrastructure 

#### 1)      Traditional infrastructure 
With a traditional infrastructure, the components—like datacenters, data storage, and other equipment—are all managed and owned by the business within their own facilities. Traditional infrastructure is often thought of as expensive to run and requires large amounts of hardware, like servers, as well as power and physical space. 

#### 2)      Cloud infrastructure 
Cloud infrastructure describes the components and resources needed for cloud computing. You can create a private cloud by building it yourself using resources dedicated solely to you. Or you can use a public cloud by renting cloud infrastructure from a cloud provider like Alibaba, Amazon, Google, IBM, or Microsoft. And by incorporating some degree of workload portability, orchestration, and management across multiple clouds you can create a hybrid cloud. 

 

## 3. Cloud Global Infrastructure 

### AWS Infrastructure Features 
* First, AWS Infrastructure is elastic and scalable. This means resources can dynamically adjust to increases or decreases in capacity requirements. It can also rapidly adjust to accommodate growth. 
* Second, this infrastructure is fault tolerant, which means it has built-in component redundancy which enables it to continue operations despite a failed component. 
* Finally, it requires minimal to no human intervention, while providing high availability with minimal down time. 

### AWS Foundational Services 
#### Compute: 
services help you make the most of your data. They support research and big data processing. AWS compute services cover virtual machines, containers, serverless computing, and more. 
#### Storage: 
AWS storage solutions provide reliable, scalable, and secure storage for backup, disaster recovery, and business continuity. 
#### Databases: 
are built for different data models and use cases and offer speed, reliability, availability, and security. 
#### Networking: 
AWS networking and content delivery are designed to ensure that AWS has the networking capabilities required to run any workload in the cloud with security, availability, performance, global coverage, and manageability 

 

## 4. Cloud Security 

Hacker, attacker, or intruder – These terms are applied to the people who seek to exploit weaknesses in software and computer systems for their own gain.  

Malicious code – Malicious code (also called malware) is unwanted files or programs that can cause harm to a computer or compromise data stored on a computer. Malicious code may have the following characteristics: 
* It might require you to do something before it infects your computer.  
* Some forms of malware propagate without user intervention and typically start by exploiting a software vulnerability.  
* Some malware claims to be one thing, while in fact doing something different behind the scenes.  

Vulnerabilities – are flaws in software, firmware, or hardware that can be exploited by an attacker to perform unauthorized actions in a system. 

#### Basic cybersecurity best practices: 

1) Keep software up to date. Install software patches so that attackers cannot take advantage of known problems or vulnerabilities. 

2) Run up-to-date antivirus software. A reputable antivirus software application is an important protective measure against known malicious threats. It can automatically detect, quarantine, and remove various types of malware.  

3) Use strong passwords. Select passwords that will be difficult for attackers to guess, and use different passwords for different programs and devices.  

4) Implement multi-factor authentication (MFA). Authentication is a process used to validate a user’s identity. Attackers commonly exploit weak authentication processes. 

5) Install a firewall. Firewalls may be able to prevent some types of attack vectors by blocking malicious traffic before it can enter a computer system, and by restricting unnecessary outbound communications. 

6) Be suspicious of unexpected emails. Phishing emails are currently one of the most prevalent risks to the average user. 

 

## 5. Networking & Content Delivery 

### Network classes 

Internet addresses are allocated by the InterNIC, the organization that administers the Internet. These IP addresses are divided into classes. The most common of these are classes A, B, and C. Classes D and E exist, but are not generally used by end users. Each of the address classes has a different default subnet mask. You can identify the class of an IP address by looking at its first octet. Following are the ranges of Class A, B, and C Internet addresses, each with an example address: 

* Class A networks use a default subnet mask of 255.0.0.0 and have 0-127 as their first octet. The address 10.52.36.11 is a class A address. Its first octet is 10, which is between 1 and 126, inclusive. 

* Class B networks use a default subnet mask of 255.255.0.0 and have 128-191 as their first octet. The address 172.16.52.63 is a class B address. Its first octet is 172, which is between 128 and 191, inclusive. 

* Class C networks use a default subnet mask of 255.255.255.0 and have 192-223 as their first octet. The address 192.168.123.132 is a class C address. Its first octet is 192, which is between 192 and 223, inclusive. 

### OSI 

OSI stands for Open Systems Interconnection. It is a reference model that specifies standards for communications protocols and the functionalities of each layer. 

The OSI Model layers are as follows: 

* Layer 7–Application: The application layer is the OSI layer closest to the end user, which means both the OSI application layer, and the user interact directly with the software application. 

* Layer 6–Presentation: The presentation layer establishes context between application-layer entities, in which the application-layer entities may use different syntax and semantics if the presentation service provides a mapping between them. 

* Layer 5–Session: The session layer controls the dialogues (connections) between computers. It establishes, manages and terminates the connections between the local and remote application. 

* Layer 4–Transport: The transport layer provides the functional and procedural means of transferring variable-length data sequences from a source to a destination host, while maintaining the quality-of-service functions. 

* Layer 3–Network: The network layer provides the functional and procedural means of transferring variable length data sequences (called packets) from one node to another connected in "different networks". 

* Layer 2-Data Link: The data link layer provides node-to-node data transfer—a link between two directly connected nodes 

* Layer 1–Physical: Responsible for the transmission and reception of unstructured raw data between a device and a physical transmission medium. 

 

## 6. Compute 

### In AWS, compute is available in three forms: instances, containers, and functions: 

Instances:   
are virtualized servers, allowing you to change their capabilities with a button or an API call. Because resource decisions in the cloud aren’t ﬁxed, you can experiment with different server types. At AWS, these virtual server instances come in different families and sizes, and they offer a wide variety of capabilities, including solid-state drives (SSDs) and graphics processing units (GPUs). 

Containers:   
are a method of operating system virtualization that allows you to run an application and its dependencies in resource-isolated processes. AWS Fargate is serverless compute for containers or Amazon EC2 can be used if you need control over the installation, configuration, and management of your compute environment. You can also choose from multiple container orchestration platforms: Amazon Elastic Container Service (ECS) or Amazon Elastic Kubernetes Service (EKS). 

 

## 7. Storage 

Volatile Memory:  
is a type of storage whose contents are erased when the system's power is turned off or interrupted. For example, RAM is volatile. 

Non-Volatile Memory: 
is a term used to describe any memory or storage that is saved regardless of the power to the computer is on or off. An example of non-volatile memory and storage is a computer hard drive, flash memory, and ROM. 

Redundant Array of Independent Disks (RAID): 
Depending on the level you use, you can lose a drive and keep all your data safe. Computers and servers can use a RAID to replicate data across multiple redundant drives in order to ensure data is available. 

Network Attached Storage (NAS): 
A NAS device is any storage device that is connected to a network and provides a network with additional storage. 

 

## 8. Databases 

Database: 
is a shared collection of related data used to support the activities of a particular organization. A database can be viewed as a repository of data that is defined once and then accessed by various users. 

Database management system (DBMS): 
is a collection of programs that enables users to create and maintain databases and control all access to them. The primary goal of a DBMS is to provide an environment that is both convenient and efficient for users to retrieve and store information. 

The following are the basic DynamoDB components: 

Tables: 

Similar to other database systems, DynamoDB stores data in tables. A table is a collection of data. People could use it to store personal contact information about friends, family, or anyone else of interest. You could also have a Cars table to store information about vehicles that people drive. 

Items: 

Each table contains zero or more items. An item is a group of attributes that is uniquely identifiable among all of the other items. In a People table, each item represents a person. For a Cars table, each item represents one vehicle. 

Attributes: 

Each item is composed of one or more attributes. An attribute is a fundamental data element, something that does not need to be broken down any further. For example, an item in a People table contains attributes called PersonID, LastName, FirstName, and so on. For a Department table, an item might have attributes such as DepartmentID, Name, Manager, and so on. Attributes in DynamoDB are similar in many ways to fields or columns in other database systems. 

 

## 9. Cloud Architecture 

Another metric is the mean time to failure (MTTF) which is the length of time a system is available until it fails. Once it does fail, you need to repair and bring the system back online. The mean time to repair (MTTR) is the amount of time taken to repair a system. The MTBF can be expanded to equal MTTF + MTTR divided by the number of failures. 

This creates a failure-repair-restore cycle that: 

* A system is brought online and is available 
* A system component then fails, we can now calculate the MTBF 
* A system component is repaired, we can now calculate the MTTR 
* A system is brought back online after repair, we can now calculate the MTBF 

  

Factors that influence availability include: 

Fault Tolerance: built in redundancy of a system or application so it can remain operational 

Scalability: ability to accommodate increase or decrease in capacity usage without changing the design 

Recoverability: process, policies, and procedures related to restoring a system after system failure 

 

## 10. Automatic Scaling & Monitoring 

Autoscaling is a cloud computing feature that enables organizations to scale cloud services such as server capacities or virtual machines up or down automatically, based on defined situations such as traffic or utilization levels. 

An instance is a single server or machine that is subject to auto scaling rules created for a group of machines. The group itself is an auto scaling group, with each instance in the group subject to those auto scaling policies. 

#### What is IT monitoring? 

The purpose of IT monitoring is to determine how well your IT infrastructure and the underlying components perform in real time. IT monitoring lets users identify IT issues in real-time to make well-informed decisions for resource provisioning, IT security, or to evaluate usage trends. 

IT monitoring technologies often have three major components: 

* Sensors that generate raw data from network nodes 
* Analytics solutions that process this data into information 
* UI interfaces that visualize intuitive and insightful reports 

### Auto scaling provides several advantages: 

Cost: 
When loads are low, auto scaling allows companies to manage both their own infrastructure and 	businesses that rely on cloud infrastructure to send some servers to sleep. This reduces 		electricity costs and water costs where water is used in cooling. Cloud auto scaling also means 	paying for total usage instead of maximum capacity. 

Security: 
Auto scaling also protects against application, hardware, and network failures by detecting and 	replacing unhealthy instances while still providing application resiliency and availability. 

Availability: 
Auto scaling improves availability and uptime, especially when production workloads are less 	predictable. 
