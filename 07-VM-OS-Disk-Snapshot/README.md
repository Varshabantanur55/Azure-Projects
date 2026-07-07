# Azure VM OS Disk Snapshot (Disaster Recovery)

## Objective
Create a snapshot of an Azure Virtual Machine OS disk to enable backup, recovery, and restoration in case of accidental data loss or system failure.

## Services Used
- Azure Virtual Machine
- Managed Disk
- Disk Snapshot
- Azure Portal
- Resource Group

## Prerequisites
- Active Azure Subscription
- Azure Portal Access
- Basic understanding of Azure Virtual Machines and Managed Disks

## Steps
1. Create a Resource Group.
2. Deploy a Windows Virtual Machine.
3. Stop (deallocate) the Virtual Machine.
4. Open the Virtual Machine and navigate to the OS Disk.
5. Create a snapshot of the OS Disk.
6. Configure the snapshot details and create it.
7. Verify that the snapshot is created successfully.
8. Restore the snapshot by creating a new managed disk.
9. Create a new Virtual Machine using the restored managed disk.
10. Verify that the restored Virtual Machine is functioning correctly.

## Outcome
Successfully created an OS disk snapshot of an Azure Virtual Machine and restored it to a new Virtual Machine, demonstrating an effective disaster recovery and backup solution.
