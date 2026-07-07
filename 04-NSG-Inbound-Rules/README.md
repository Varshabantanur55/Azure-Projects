# Azure Network Security Group (NSG) Inbound Rules

## Objective
Configure Network Security Group (NSG) inbound rules to secure Azure Virtual Machines by allowing only the required network traffic.

## Services Used
- Azure Network Security Group (NSG)
- Azure Virtual Machine
- Azure Virtual Network (VNet)
- Public IP Address
- Resource Group

## Prerequisites
- Active Azure Subscription
- Azure Portal Access
- Basic understanding of Azure Networking

## Steps
1. Create a Resource Group.
2. Create a Virtual Network and Subnet.
3. Deploy a Windows Virtual Machine.
4. Create a Network Security Group (NSG).
5. Configure inbound security rules to allow RDP (Port 3389) and HTTP (Port 80).
6. Associate the NSG with the Virtual Machine or Subnet.
7. Verify that only the configured inbound traffic is allowed.
8. Test remote connectivity to the Virtual Machine.

## Outcome
Successfully configured Network Security Group inbound rules to secure the Virtual Machine by allowing only authorized network traffic while blocking unauthorized access.
