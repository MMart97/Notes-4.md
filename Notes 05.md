## Keypoints:
  - A computer network is just two or more client machines that are connected together, using a network device, to share resources
  - There are also multiple devices or mediums which helps in the communication between two different devices which are known as Network devices (router, hub, bridge, wireless router, switch, wireless bridge)
  - The layout pattern using which devices are interconnected is called as network topology (star, mesh, ring, peer to peer, tree, etc.)
  - OSI stands for Open Systems Interconnection (It is a reference model that specifies standards for communications protocols and also the functionalities of each layer)
  - Protocol is the set of rules or algorithms which define the way how two entities can communicate across the network and there exists different protocol defined at each layer of OSI model
  - IP Address (Logical address) is the network address of the system across the network
  - Each device in the network is associated with a unique device name known as Hostname
  - A common method to describe networks is Classless Inter-Domain Routing (CIDR). IP address, (/), a number that tells you how many bits of the routing prefix must be fixed or allocated for the network identifier
  - A MAC adress is the unique identifier of each host and is associated with the NIC (Network Interface Card)
  - Port can be referred to as a logical channel through which data can be sent/received to an application
  - The unique combination of IP address and Port number together are termed as Socket
  - DNS stands for Domain Name System. DNS is basically a server which translates web addresses or URL (ex: www.google.com)Links to an external site. into their corresponding IP addresses
  - ARP stands for Address Resolution Protocol. It is used to convert the IP address to its corresponding Physical Address(i.e.MAC Address)
  - RARP stands for Reverse Address Resolution Protocol,  it provides the IP address of the device given a physical address as input. It is obsolete now. 
  - URI stands for ‘Uniform Resource Identifier’, it’s like an address providing a unique global identifier to a resource on the Web
  - An IP address is a 32-bit number that uniquely identifies a host (computer or other device, such as a printer or router) on a TCP/IP network
  - The subnet mask is used by the TCP/IP protocol to determine whether a host is on the local subnet or on a remote network
  - Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define
  - A route table contains a set of rules, called routes, that are used to determine where network traffic from your subnet or gateway is directed
  - An internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet
  - A transit gateway is a network transit hub that you can use to interconnect your virtual private clouds (VPC) and on-premises networks
  - A VPC endpoint enables you to privately connect your VPC to supported AWS services and VPC endpoint services powered by AWS PrivateLink without requiring an internet gateway, NAT device, VPN connection, or AWS Direct Connect connection. Instances in your VPC do not require public IP addresses to communicate with resources in the service
  - A security group acts as a virtual firewall for your instance to control inbound and outbound traffic
  - A network access control list (ACL) is an optional layer of security for your VPC that acts as a firewall for controlling traffic in and out of one or more subnets
  - DNS, or the Domain Name System, translates human readable domain names (for example, www.amazon.com) to machine readable IP addresses (for example, 192.0.2.44).
  - Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS)Links to an external site. web service.
  - Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment
  
  
  # Quote 1: "The layout pattern using which devices are interconnected is called as network topology"
    - It's interesting to see how different layouts of devices on networks can benefit different companies needs.
  # Quote 2: "When you create a custom security group, you can specify allow rules, but not deny rules"
    - I find this interesting because if one cannot deny rules, then who is allowed to change the rules?
    
    
 ## New Facts:
  - Almost all decimal subnet masks convert to binary numbers that are all ones on the left and all zeros on the right
  - Internet addresses are allocated by the InterNIC, the organization that administers the Internet
  - You should now be able to give IP addresses to 254 hosts
  - TCP/IP network problems are often caused by incorrect configuration of the three main entries in a computer's TCP/IP properties
  - A VPC spans all of the Availability Zones in the Region
  - If a subnet's traffic is routed to an internet gateway, the subnet is known as a public subnet
 
 
 ## Remaining questions:
  - How any IP addresses can we set to a VPC?
