# Azure Bastion & Virtual Machine Project

## Overview
A hands-on project setting up secure remote access to an Azure VM using Azure Bastion, without exposing a public IP.

## Technologies Used
- Azure Virtual Machine (Windows Server 2022)
- Azure Bastion
- Azure Virtual Network (VNet)

## Build Process


### 1. Deployed a Windows Server Virtual Machine
![Create VM](<img width="947" height="698" alt="image" src="https://github.com/user-attachments/assets/7ce222f2-701d-41a5-801a-1095e5cabfff" />
)
Created the VM using the Standard_D2s_v3 size.

### 2. IP Configurations
![IP Configurations](<img width="1442" height="861" alt="images02-ipconfiguration" src="https://github.com/user-attachments/assets/cdc7bc2f-643b-4275-85a5-563fdf231f66" />
)
Set a static private IP for the domain controller in my lab environment.

### 3. Connect the Windows Server vm through Azure Bastion
![Bastion Setup](<img width="1920" height="775" alt="images03-bastion-setup" src="https://github.com/user-attachments/assets/133d826f-3528-478a-95e0-f74b1fa7192f" />
)
Set up Azure Bastion to allow secure connection without exposing a public IP.

### 4. Install roles and features (adds)_Active Directory
![Adds roles and fearues](<img width="1711" height="773" alt="images04-adds" src="https://github.com/user-attachments/assets/11ec27fd-068e-4303-ad38-07a257399ca2" />
)

## What I Learned
- Learned how Bastion enables secure remote access without a public IP.
- Understood the importance of Network Security Group (NSG) configuration.
