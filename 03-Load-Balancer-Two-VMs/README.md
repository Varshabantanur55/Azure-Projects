# Azure Load Balancer with Two Virtual Machines

## Objective
Configure an Azure Load Balancer to distribute incoming network traffic across two Virtual Machines, ensuring high availability and improved application performance.

## Services Used
- Azure Load Balancer
- Azure Virtual Machine
- Virtual Network (VNet)
- Backend Pool
- Health Probe
- Network Security Group (NSG)
- Public IP Address
- Resource Group

## Prerequisites
- Active Azure Subscription
- Azure Portal Access
- Basic understanding of Azure Networking

## Steps
1. Create a Resource Group.
2. Create a Virtual Network and Subnet.
3. Deploy two Windows Virtual Machines in the same Virtual Network.
4. Create an Azure Load Balancer with a Public IP Address.
5. Configure the Frontend IP.
6. Create a Backend Pool and add both Virtual Machines.
7. Configure a Health Probe.
8. Create a Load Balancing Rule.
9. Install IIS on both Virtual Machines.
10. Verify traffic distribution by accessing the Load Balancer's Public IP address.

## Outcome
Successfully configured an Azure Load Balancer to distribute incoming traffic across two Virtual Machines, improving application availability, scalability, and reliability.
