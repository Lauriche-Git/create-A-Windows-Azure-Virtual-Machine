# Create-A-Windows-Azure-Virtual-Machine
A hands-on lab demonstrating how to create, configure, and validate a Windows Server Virtual Machine using the Microsoft Azure Portal.


## 🎬 Watch Me Build This Lab!
This video walks through the entire VM creation process step by step.
https://www.loom.com/share/ccb531b20153476585cd2b9cf220c01c

 ## 🏹 Objective
 The goal of this lab is to deploy a Windows Server 2022 virtual machine in Microsoft Azure and ensure it is properly configured, accessible, and operational.
This lab helps build foundational cloud infrastructure skills commonly used in real-world IT and cloud environments.
 
 ## 🤹 Skills Practiced
 #### Azure Portal navigation
 #### Resource Group creation and management
 ##### Virtual Machine configuration
##### Operating System selection (Windows Server 2022)
##### Administrator account creation
##### Networking and inbound port configuration
#### VM validation and deployment

## 🪚  Tools & Technologies Used
1. Microsoft Azure Portal
2. Windows Server 2022
3. Azure Virtual Machines
4. Azure Networking (VNet, Subnet, Inbound Rules)

## 📋 Prerequisites
1. An active Microsoft Azure account
2. Basic understanding of virtual machines
3.  Internet connection and modern web browser

## 🚶‍♂️‍➡️  Steps Performed
### 1️⃣ Log in to Azure Portal
1.  Sign in to the Azure Portal
2. Click Create a resource
3. Select Azure Virtual Machine
 <img width="686" height="524" alt="1" src="https://github.com/user-attachments/assets/d34f2e7d-256a-4631-9022-84ffa7cecb1b" /> 

### 2️⃣ Create a Resource Group

1.  Created a new resource group to logically organize the VM and related resources
2.   Resource groups help with management, monitoring, and cleanup
  <img width="539" height="400" alt="2" src="https://github.com/user-attachments/assets/df368c75-20e9-4597-9d01-b99ffcfd5b55" />


### 3️⃣ Create the Virtual Machine
1.  Virtual Machine Name: Lauriche-VM
2.  Selected appropriate subscription and resource group
   <img width="700" height="329" alt="3" src="https://github.com/user-attachments/assets/aca853aa-19ea-42ec-bf0e-8f9a8270a8a6" />

### 4️⃣ Configure Basic Settings
Configured the following VM settings:
1.  Region (Azure data center location)
2.  Availability options
3.  Security type
4.  Image: Windows Server 2022
5.  VM architecture
6.  VM size (based on performance needs)
    <img width="783" height="245" alt="4" src="https://github.com/user-attachments/assets/8add266b-4260-4c3e-a49c-03c7352ca068" />

### 5️⃣ Administrator Account & Networking Configuration    
1. Created an administrator username and password
2. Configured inbound port rules (RDP – Port 3389)
3. Set up: OS disk ,  Virtual network ,  Subnet

### 6️⃣ Validation & Deployment
1. Reviewed all configurations
2. Clicked Validate + Create
3. Successfully deployed the virtual machine

## 🍃  Outcome
- Successfully deployed a Windows Server 2022 Azure Virtual Machine
- Verified the VM status as running
- Confirmed remote access via RDP
- Gained hands-on experience with Azure VM provisioning

 
