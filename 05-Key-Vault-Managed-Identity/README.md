# Azure Key Vault with Managed Identity

## Objective
Securely store and manage secrets, keys, and certificates in Azure Key Vault, and enable a Virtual Machine to access secrets securely using Managed Identity without storing credentials in the application.

## Services Used
- Azure Key Vault
- Managed Identity
- Azure Virtual Machine
- Azure Role-Based Access Control (RBAC)
- Resource Group

## Prerequisites
- Active Azure Subscription
- Azure Portal Access
- Basic understanding of Azure Security and Identity

## Steps
1. Create a Resource Group.
2. Create an Azure Key Vault.
3. Add a sample secret to the Key Vault.
4. Deploy a Virtual Machine.
5. Enable System-Assigned Managed Identity for the Virtual Machine.
6. Grant the Virtual Machine access to the Key Vault using Azure RBAC or Key Vault access policies.
7. Access the secret from the Virtual Machine using its Managed Identity.
8. Verify that the secret is retrieved successfully without using stored credentials.

## Outcome
Successfully secured sensitive information using Azure Key Vault and enabled secure access through Managed Identity, eliminating the need to store credentials within the application or Virtual Machine.
