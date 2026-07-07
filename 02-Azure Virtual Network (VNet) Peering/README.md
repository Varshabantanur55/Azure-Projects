# Azure Virtual Network (VNet) Peering

## Objective
Establish secure and private communication between two Azure Virtual Networks using VNet Peering.

## Services Used
- Azure Virtual Network (VNet)
- Virtual Network Peering
- Azure Virtual Machine
- Network Security Group (NSG)
- Resource Group

## Steps
1. Create a Resource Group.
2. Create VNet-1 with address space 10.0.0.0/16.
3. Create VNet-2 with address space 10.1.0.0/16.
4. Create one subnet in each Virtual Network.
5. Deploy one Virtual Machine in each VNet.
6. Configure Network Security Group (NSG) rules.
7. Configure VNet Peering between VNet-1 and VNet-2.
8. Verify the peering status as Connected.
9. Test connectivity between the Virtual Machines using their private IP addresses.

## Outcome
Successfully established private communication between two Azure Virtual Networks using VNet Peering and verified connectivity between Virtual Machines.
