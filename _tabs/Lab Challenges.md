--- 
title: Lab Challenges
icon: fas fa-file-alt
order: 4
--- 

# Lab 1: Implementing Virtual Networking

# Problem Statement

Creating a secure Virtual Network using Microsoft Azure. The primary goal is to accommodate all existing resources while ensuring there is ample capacity for future growth, as the organization is currently in a growth phase.

The first subnet, CoreServicesVnet, is the virtual network with the largest number of resources. Given the anticipated growth, a spacious address range is crucial for this virtual network.

The second subnet, ManufacturingVnet, supports the systems used in the operations of the manufacturing facilities. The organization expects to connect a significant number of internal devices that will retrieve data from these systems.

# Approach

I followed 4 tasks as follows:  
	Task 1: Creating a virtual network with subnets using the Azure portal

	Task 2: Creating a virtual network and subnets using a template

	Task 3: Creating and configuring communication between an Application Security Group and a Network Security Group.

	Task 4: Configuring public and private Azure DNS zones.

# Tools used

	Microsoft Azure Portal
	Azure Template

# Screenshots

# Task 1: Creating a virtual network with subnets using the Azure portal


![image](https://github.com/user-attachments/assets/9a8dbe78-7c23-429b-9228-e9fae806c16d)

# Task 2: Creating a virtual network and subnets using a template

![image](https://github.com/user-attachments/assets/fa6beda9-32aa-4279-a55a-700daa24716a)

 ![image](https://github.com/user-attachments/assets/03335d58-0573-4042-a5d8-0ee3af931434)

# Key lessons learned

The lab taught me how to create virtual networks using the Azure portal and a template. I also learned how to implement Network Security Groups over the virtual networks and the Application Security Groups.

# Lab 2: Implement Intersite Connectivity 

# Problem Statement

Your organization separates core IT applications and services, such as DNS and security services, from other business areas, including the manufacturing department. However, there are situations where applications and services are utilized in the manufacturing area. In this lab, you will set up connectivity between these segmented areas. This scenario is common for separating production from development or for isolating one subsidiary from another.

# Approach

I solved this lab through tasks as follows: 

	Task 1: Creating a Virtual Machine in a Virtual Network

	Task 2: Creating a Virtual Machine in a different Virtual Network

	Task 3: Using Network Watcher to test the Connection between Virtual Machines

	Task 4: Configuring Virtual Network peerings between different Virtual Machines

	Task 5: Using Azure PowerShell to test the Connection between the virtual machines

	Task 6: Creating a Custom Route


# Tools used

	Microsoft Azure Portal

	Azure Virtual Machines

	Network Watcher

	Azure PowerShell

# Screenshots

Task 1: Creating a Virtual Machine in a Virtual Network
![image](https://github.com/user-attachments/assets/ddee6e29-83f2-48d4-8f1b-051a9c573c97)

Task 2: Creating a virtual machine in a different virtual network
![image](https://github.com/user-attachments/assets/9e2a6de2-43db-4296-b818-a1fadd7206a4)

Task 3: Using Network Watcher to test the Connection between Virtual Machines
![image](https://github.com/user-attachments/assets/b940e2fd-f987-4ae1-a510-e75c70692fba)

Task 4: Configuring Virtual Network peerings between different Virtual Machines
![image](https://github.com/user-attachments/assets/f374c12d-4f94-4d1b-9a88-b7ea5e2c127d)


Task 5: Using Azure PowerShell to test the Connection between the virtual Machine
![image](https://github.com/user-attachments/assets/d658492e-26a9-426d-aa4e-9f461b5fa143)

Task 6: Creating a Custom Route
![image](https://github.com/user-attachments/assets/1e72aee4-137b-4614-94a0-accb9faee0d1)


# Key lessons learned

I learned to implement inter-site connectivity between virtual networks. I explored virtual network peering and tested connections through Network Watcher. I used Azure PowerShell to test connections between virtual machines and created a custom route


# Lab 3: Implementing DHCP Configurations, OSPF protocol, SSH configuration, and DNS set up for a small business

# Problem Statement

After graduating with a degree in IT/cybersecurity, you've been applying for tech positions. Your efforts pay off when NGN (New Generation Network) invites you for an interview.
The interviewer warmly explains the test format: you will diagnose and resolve connectivity issues for a fictional company's network within a set time. The task has two sections: Section A (Yellow) for troubleshooting and Section B (Green) for configuration. Start with Section B, using the network addresses shown in the provided topology (with a Packet Tracer file)

![image](https://github.com/user-attachments/assets/9992e3fb-3f6d-440f-a9af-6bf368f8e414)

# Simulation Guidelines:

**1. Use the routing protocol specified in the network topology.**
   
**2. Rename routers according to the topology and add your initials (e.g., MayLC).**

**3. Configure routers and end devices using the provided network addresses.**

**4. Choose any valid IP address for individual device configuration.**

**5. Set up router IDs as shown in the topology.**
**6. For the router connected to the laptop, configure SSH access using a domain (e.g., firstname.com). Create a user with the username Cisco1plusyourinitials (e.g., Cisco1LC) and password Class1, alongside a secret password Class2025. Verify login from the laptop.**

**7. Set up a DHCP server to provide IP configuration for the network 192.168.20.0/24, and set up a DNS server with the URL www.June.com.**

**8. Ensure all devices can ping each other in the Green Area before troubleshooting.**
**Troubleshooting Section A:**
**- Identify and fix configuration issues in the section. Document the errors and solutions in a table.**

**Testing After Troubleshooting:**
1. Verify that the Green and Yellow sections function as one network with accessibility across all devices.
2. Ensure PCs in the network **192.168.20.0** receive IP configuration from the DHCP server in Green Section B.

# Approach

I handled this project by tackling Section B (Green). The tasks were as follows:
**1. Use the routing protocol specified in the network topology. (OSPF)**
   
**2. Rename routers according to the topology and add your initials (e.g., JulyKK).**

**3. Configure routers and end devices using the provided network addresses.**

**4. Choose any valid IP address for individual device configuration.**

**5. Set up router IDs as shown in the topology.**

**6. For the router connected to the laptop, configure SSH access using a domain (e.g., kk.com). Create a user with the username Cisco1KK and password Class1, alongside a secret password Class2025. Verify login from the laptop.**

**7. Set up a DHCP server to provide IP configuration for the network 192.168.20.0/24, and set up a DNS server with the URL www.June.com.**

**8. Ensure all devices can ping each other in the Green Area before troubleshooting.**

# Tools used:

**Cisco Packet Tracer**

# Screenshots

**Task 1: Use the routing protocol specified in the network topology. (OSPF)**
![image](https://github.com/user-attachments/assets/bbbda626-9871-420f-b4f5-64b2b7aa393f)

**Task 2: Rename routers according to the topology and add your initials (e.g., JulyKK)**
![image](https://github.com/user-attachments/assets/da6c61b1-b4ac-4947-bcfd-948b35f49e6f)

**Task 3: Choose any valid IP address for individual device configuration.**
![image](https://github.com/user-attachments/assets/fb9ef42f-f871-4f6d-a5e7-2dcb776cad64)

**Task 4: Set up router IDs as shown in the topology.**
![image](https://github.com/user-attachments/assets/60255007-8d8c-4a78-b70d-c2add495ae4d)

**Task 5: For the router connected to the laptop, configure SSH access using a domain (e.g., kk.com). Create a user with the username Cisco1KK and password Class1, alongside a secret password Class2025. Verify login from the laptop.**
![image](https://github.com/user-attachments/assets/5badb9a6-5dbf-4920-8464-38c9757c2569)

**Task 6: Set up a DHCP server to provide IP configuration for the network 192.168.20.0/24, and set up a DNS server with the URL www.June.com(218.80.80.2/24).**
![image](https://github.com/user-attachments/assets/7263b903-f321-49b8-88bf-846c6d8fe6f6)

**Task 7: Ensure all devices can ping each other in the Green Area before troubleshooting.**
![image](https://github.com/user-attachments/assets/45d8dad2-33dc-46c5-bbdf-9d324a5e42be)

**Task 8: Testing After Troubleshooting
Verify that the Green and Yellow sections function as one network with accessibility across all devices.**
![image](https://github.com/user-attachments/assets/de79e611-2ebd-4593-bf52-fc65cf9d5b67)

Ensure PCs in the network **192.168.20.0** receive IP configuration from the DHCP server in Green Section B
![image](https://github.com/user-attachments/assets/daa764c6-e745-4447-87b5-b8dcbe768890)

























 










 






