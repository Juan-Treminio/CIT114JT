CIT114-Juan Treminio 

# Notes 10: Automatic Scaling & Monitoring 

Autoscaling is a cloud computing feature that enables organizations to scale cloud services such as server capacities or virtual machines up or down automatically, based on defined situations such as traffic or utilization levels. 

An instance is a single server or machine that is subject to auto scaling rules created for a group of machines. The group itself is an auto scaling group, with each instance in the group subject to those auto scaling policies. 

# Quotes: 

“Elastic Load Balancing automatically distributes your incoming traffic across multiple targets, such as EC2 instances, containers, and IP addresses, in one or more Availability Zones.” I found this quote interesting because these services are just making businesses have less things to worry about. 

“Failover occurs when a given server is not functioning and a load balancer distributes its normal processes to a secondary server or group of servers. Server failover is crucial for reliability: if there is no backup in place, a server crash could bring down a website or application.” I found this quote interesting because it illustrates how every service intertwines with each other to work efficiently. 

# New Facts: 

### What is IT monitoring? 

The purpose of IT monitoring is to determine how well your IT infrastructure and the underlying components perform in real time. IT monitoring lets users identify IT issues in real-time to make well-informed decisions for resource provisioning, IT security, or to evaluate usage trends. 

#### IT monitoring technologies often have three major components: 

* Sensors that generate raw data from network nodes 

* Analytics solutions that process this data into information 

* UI interfaces that visualize intuitive and insightful reports 

### Auto scaling provides several advantages: 

#### Cost: 

When loads are low, auto scaling allows companies to manage both their own infrastructure and 	businesses that rely on cloud infrastructure to send some servers to sleep. This reduces 		electricity costs and water costs where water is used in cooling. Cloud auto scaling also means 	paying for total usage instead of maximum capacity. 

#### Security: 

Auto scaling also protects against application, hardware, and network failures by detecting and 	replacing unhealthy instances while still providing application resiliency and availability. 

#### Availability: 

Auto scaling improves availability and uptime, especially when production workloads are less 	predictable. 

 
