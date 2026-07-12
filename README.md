# Azure Bastion & Virtual Machine Project

## Overview
A hands-on project setting up secure remote access to an Azure VM using Azure Bastion, without exposing a public IP.

## Technologies Used
- Azure Virtual Machine (Windows Server 2022)
- Azure Bastion
- Azure Virtual Network (VNet)

## Build Process


### 1. Deployed a Windows Server Virtual Machine
![Create VM](<img width="1538" height="746" alt="images01-create-vm png" src="https://github.com/user-attachments/assets/129c5dce-214c-4042-b754-bea2e9c6d256" />
)
Created the VM using the Standard_D2s_v3 size.

### 2. IP Configurations
![IP Configurations](<img width="1442" height="861" alt="images02-ipconfiguration" src="https://github.com/user-attachments/assets/5a06a742-1f33-4dfb-8cda-cf7d5e1ef1c2" />
)
Set a static private IP for the domain controller in my lab environment.

### 3. Connect the Windows Server vm through Azure Bastion
![Bastion Setup](<img width="1920" height="775" alt="images03-bastion-setup" src="https://github.com/user-attachments/assets/c3dcf34d-7aba-4358-9f2a-5eb3ef18d4eb" />
)
Set up Azure Bastion to allow secure connection without exposing a public IP.

### 4. Install roles and features (adds)_Active Directory
![Adds roles and fearues](<img width="1711" height="773" alt="images04-adds" src="https://github.com/user-attachments/assets/d782f579-cd69-40e5-b3fd-b107672cd9bb" />
)

## What I Learned
- Learned how Bastion enables secure remote access without a public IP.
- Understood the importance of Network Security Group (NSG) configuration.
