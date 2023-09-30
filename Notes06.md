CIT114-Juan Treminio 

# Notes 06: Compute 

An operating system is the most important software that runs on a computer. It manages the computer's memory and processes, as well as all its software and hardware. It also allows you to communicate with the computer without knowing how to speak the computer's language. Without an operating system, a computer is useless. 

### In AWS, compute is available in three forms: instances, containers, and functions: 

#### Instances:   

are virtualized servers, allowing you to change their capabilities with a button or an API call. Because resource decisions in the cloud aren’t ﬁxed, you can experiment with different server types. At AWS, these virtual server instances come in different families and sizes, and they offer a wide variety of capabilities, including solid-state drives (SSDs) and graphics processing units (GPUs). 

 

#### Containers:   

are a method of operating system virtualization that allows you to run an application and its dependencies in resource-isolated processes. AWS Fargate is serverless compute for containers or Amazon EC2 can be used if you need control over the installation, configuration, and management of your compute environment. You can also choose from multiple container orchestration platforms: Amazon Elastic Container Service (ECS) or Amazon Elastic Kubernetes Service (EKS). 

 

#### Functions:   

abstract the execution environment from the code you want to execute. For example, AWS Lambda allows you to execute code without running an instance. 

 

# Quotes: 

“EC2 encourages scalable deployment of applications by providing a web service through which a user can boot an Amazon Machine Image (AMI) to configure a virtual machine, which Amazon calls an instance, containing any software desired.” I found this quote interesting because of how versatile EC2 is. 

“Just create a Lambda function, upload your code, and then set the Lambda function to be triggered, either on a scheduled basis or in response to an event. Lambda takes care of everything required to run your code when triggered and scale your code with high availability.” I found this quote interesting because with lambda it seems that it gives you more power of how you want things to run, even given you the choice of having a schedule. 

# New Factor: 

A Container in cloud computing is an approach to operating system virtualization. By this, the user can work with a program and its dependencies using resource procedures that are isolated. The code of the application can be bundled with configurations and dependencies in a systematic manner. 
