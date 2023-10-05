CIT114-Juan Treminio 

# Notes 09: Cloud Architecture 

One of the best practices that is identified in the AWS Well-Architected Framework is to plan for failure (or application or workload downtime). One way to do that is to architect your applications and workloads to withstand failure. 

### Reliability: 

is the measure of your system’s ability to perform its intended function correctly and consistently when it’s expected to. This means the system is available for use and able to operate the workload throughout its total lifecycle. All aspects of the system must be considered including hardware, firmware, and software. Failure of any one of these impacts the reliability of the system. 

 

### Availability: 

 is defined as the percentage of time that a workload is available for use. Available for use means that it performs its agreed function when required. 

Availability = "Available for Use Time" / "Total Time" 

# Quotes: 

“The AWS Well-Architected Tool helps you review the state of your workloads and compares them to the latest AWS architectural best practices. The tool is based on the AWS Well-Architected Framework, developed to help cloud architects build secure, high-performing, resilient, and efficient application infrastructure.” I found this quote interesting because these are free tools that a company can use to be more efficient and find better use of the services. 

 

“AWS Trusted Advisor is an online tool that provides you with real time guidance to help you provision your resources following AWS best practices. Trusted Advisor checks help optimize your AWS infrastructure, increase security and performance, reduce your overall costs, and monitor service limits.” I found this quote interesting because it seems like there are so many tools that will help you manage your business. It basically does maintenance on its own and tells you where you're not using the correct service. 

 

# New Facts: 

Another metric is the mean time to failure (MTTF) which is the length of time a system is available until it fails. Once it does fail, you need to repair and bring the system back online. The mean time to repair (MTTR) is the amount of time taken to repair a system. The MTBF can be expanded to equal MTTF + MTTR divided by the number of failures. 

### This creates a failure-repair-restore cycle that: 

1. A system is brought online and is available 

2. A system component then fails, we can now calculate the MTBF 

3. A system component is repaired, we can now calculate the MTTR 

4. A system is brought back online after repair, we can now calculate the MTBF 

 

### Factors that influence availability include: 

* Fault Tolerance: built in redundancy of a system or application so it can remain operational 

* Scalability: ability to accommodate increase or decrease in capacity usage without changing the design 

* Recoverability: process, policies, and procedures related to restoring a system after system failure 

 
