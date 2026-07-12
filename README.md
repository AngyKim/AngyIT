# Azure Bastion & Virtual Machine Project

## Overview
A hands-on project setting up secure remote access to an Azure VM using Azure Bastion, without exposing a public IP.

## Technologies Used
- Azure Virtual Machine (Windows Server 2022)
- Azure Bastion
- Azure Virtual Network (VNet)

## Build Process

### 1. Creating the Virtual Machine
![Create VM](<img width="1538" height="746" alt="images01-create-vm png" src="https://github.com/user-attachments/assets/19c520de-51ab-4d40-b6e2-b3439f9cebb4" />
)
Created the VM using the Standard_D2s_v3 size.

### 2. Configuring Bastion
![Bastion Setup](images/02-bastion-setup.png)
Set up Azure Bastion to allow secure connection without exposing a public IP.

### 3. Successful Connection
![Connection Success](images/03-connection-success.png)

## What I Learned
- Learned how Bastion enables secure remote access without a public IP.
- Understood the importance of Network Security Group (NSG) configuration.
