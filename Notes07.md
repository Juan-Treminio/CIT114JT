CIT114-Juan Treminio 

# Notes 07: Storage 

### Volatile Memory:  

is a type of storage whose contents are erased when the system's power is turned off or interrupted. For example, RAM is volatile. 

### Non-Volatile Memory: 

is a term used to describe any memory or storage that is saved regardless of the power to the computer is on or off. An example of non-volatile memory and storage is a computer hard drive, flash memory, and ROM. 

### Redundant Array of Independent Disks (RAID): 

Depending on the level you use, you can lose a drive and keep all your data safe. Computers and servers can use a RAID to replicate data across multiple redundant drives in order to ensure data is available. 

### Network Attached Storage (NAS): 

A NAS device is any storage device that is connected to a network and provides a network with additional storage. 

# Quotes: 

“One of the things IT professionals must think about is how can we protect data from being compromised both at rest and in transit. Encryption is a method securing data by taking data and making it unreadable without the right decryption information.” I found this quote interesting because businesses that are worried about data being compromised just need to take the correct steps to make sure their data is encrypted. 

“All EBS volume types offer durable snapshot capabilities to S3 and are designed for 99.999% availability.” I found this quote interesting because the durability's of EBS are much lower than EFS and Glacier which offer 11 9’s of durability. 

# New Facts: 

### Types of Cloud Storage: 

There are three types of cloud data storage:  

#### Object Storage:  

Applications developed in the cloud often take advantage of object storage's vast scalability and metadata characteristics. Object storage solutions are ideal for building modern applications from scratch that require scale and flexibility and can also be used to import existing data stores for analytics, backup, or archive. 

#### File Storage: 

Some applications need to access shared files and require a file system. This type of storage is often supported with a Network Attached Storage (NAS) server. File storage solutions are ideal for use cases like large content repositories, development environments, media stores, or user home directories. 

#### Block Storage:  

Other enterprise applications like databases or ERP systems often require dedicated, low latency storage for each host. This is analogous to direct-attached storage (DAS) or a Storage Area Network (SAN). Block-based cloud storage solutions are provisioned with each virtual server and offer the ultra-low latency required for high performance workloads. 
