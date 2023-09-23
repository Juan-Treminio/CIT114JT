CIT114-Juan Treminio 

# Notes 05 – Networking & Content Delivery 

## OSI 

OSI stands for Open Systems Interconnection. It is a reference model that specifies standards for communications protocols and the functionalities of each layer. 

### The OSI Model layers are as follows: 

#### Layer 7–Application: 
The application layer is the OSI layer closest to the end user, which means both the OSI application layer, and the user interact directly with the software application. 

#### Layer 6–Presentation: 
The presentation layer establishes context between application-layer entities, in which the application-layer entities may use different syntax and semantics if the presentation service provides a mapping between them. 

#### Layer 5–Session: 
The session layer controls the dialogues (connections) between computers. It establishes, manages and terminates the connections between the local and remote application. 

#### Layer 4–Transport: 
The transport layer provides the functional and procedural means of transferring variable-length data sequences from a source to a destination host, while maintaining the quality-of-service functions. 

#### Layer 3–Network: 
The network layer provides the functional and procedural means of transferring variable length data sequences (called packets) from one node to another connected in "different networks". 

#### Layer 2-Data Link: 
The data link layer provides node-to-node data transfer—a link between two directly connected nodes 

#### Layer 1–Physical: 
Responsible for the transmission and reception of unstructured raw data between a device and a physical transmission medium. 

### Internet Gateway:  

An internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet. An internet gateway serves two purposes: to provide a target in your VPC route tables for internet-routable traffic, and to perform network address translation (NAT) for instances that have been assigned public IPv4 addresses. An internet gateway supports IPv4 and IPv6 traffic. It does not cause availability risks or bandwidth constraints on your network traffic. 

# Quotes: 

“Many companies use this technology to connect separate locations in order to grant employees the ability to access company resources anywhere in the world.” I found the quote interesting because I work at a helpdesk, and we need to give employees this access so they can use VPN for remote work. 

“In reality the internet is tens of thousands of kilometers of fiber optic cable, hundreds of thousands to millions of kilometers of copper wire, and hardware and software connecting them all together in a redundant, fast, and self-sufficient network.”  I found this quote interesting because so much cable and wire that is used for the internet and no one sees that side of the internet. Everyone thinks the internet is just in space. 

# New Facts: 

## Network classes 

Internet addresses are allocated by the InterNIC, the organization that administers the Internet. These IP addresses are divided into classes. The most common of these are classes A, B, and C. Classes D and E exist, but are not generally used by end users. Each of the address classes has a different default subnet mask. You can identify the class of an IP address by looking at its first octet. Following are the ranges of Class A, B, and C Internet addresses, each with an example address: 

Class A networks use a default subnet mask of 255.0.0.0 and have 0-127 as their first octet. The address 10.52.36.11 is a class A address. Its first octet is 10, which is between 1 and 126, inclusive. 

Class B networks use a default subnet mask of 255.255.0.0 and have 128-191 as their first octet. The address 172.16.52.63 is a class B address. Its first octet is 172, which is between 128 and 191, inclusive. 

Class C networks use a default subnet mask of 255.255.255.0 and have 192-223 as their first octet. The address 192.168.123.132 is a class C address. Its first octet is 192, which is between 192 and 223, inclusive. 
