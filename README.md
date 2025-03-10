# Azure VM Assignment

# Project Overview
This project demonstrates the process of setting up a basic Azure infrastructure, utilizing key components such as a Virtual Machine (VM), Public IP Address for Remote Desktop Protocol (RDP) access, Virtual Network, and an Azure Disk attached to the VM.

*Key Components:*
- **Azure Virtual Machine (Windows Server)**
- **Public IP Address for RDP access**
- **Virtual Network with a default subnet**
- **Azure Disk attached to the Virtual Machine**

The goal of this assignment is to create a fully functional Azure environment and connect to the virtual machine via RDP.

# Steps Completed:

## 1. Resource Group Created
A Resource Group was created in Azure to organize the resources efficiently.

## 2. Virtual Network Set Up
A Virtual Network (VNet) was created with a default subnet (10.0.0.0/16) to ensure secure communication between resources.

## 3. Windows Virtual Machine Deployed
A free-tier eligible Windows Server VM was deployed within the created VNet. A public IP address was assigned for RDP access.

## 4. Azure Disk Attached to the VM
An Azure Disk was attached to the virtual machine for additional storage capacity and configuration.

## 5. VM Connected Using RDP
RDP was used to connect to the VM using its assigned public IP address.

### 1. Screenshot of Resource Group Creation
![Resource Group](https://github.com/ilafurt/azure-vm-assignment/blob/main/resourcegroups.PNG)

### 2. Screenshot of Virtual Network and Subnet Setup
![Virtual Network](https://github.com/ilafurt/azure-vm-assignment/blob/main/virtualnetwork.PNG)

### 3. Screenshot of the Virtual Machine with Public IP
![Virtual Machine](https://github.com/ilafurt/azure-vm-assignment/blob/main/virtualmachine.PNG)

### 4. Screenshot Showing the Azure Disk Attached to the VM
![Azure Disk](https://github.com/ilafurt/azure-vm-assignment/blob/main/azuredisk.PNG)

### 5. Screenshot of the Desktop Connection (RDP)
![Desktop Connection](https://github.com/ilafurt/azure-vm-assignment/blob/main/desktop.PNG)


## Conclusion
This project successfully demonstrates the setup of a basic Azure environment, including a Virtual Machine, Public IP, Virtual Network, and Azure Disk. By following the above steps, a similar infrastructure was created in Azure, which can be applied for various use cases.
