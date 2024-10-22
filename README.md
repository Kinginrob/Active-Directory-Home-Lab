# **Active-Directory-Home-Lab**
This repository details my home lab setup using Oracle VirtualBox and Windows Server 2019 for managing an Active Directory environment. It includes steps for setting up a virtual network, installing software, and configuring AD services to mimic enterprise network management, showcasing my skills in system administration and network security.

## Project Files

- **1_CREATE_USERS.ps1:** PowerShell script to generate user accounts in Active Directory.
- **Generate-Names-Create-Users.ps1:** PowerShell script that combines name generation and user creation in one process.
- **names.txt:** Contains pre-generated names that can be used directly to create user accounts.

## Network Setup

*This network diagram illustrates the structure of my virtual network setup, including IP addressing and connectivity across different components such as Domain Controller and Windows 10 client within the network environment.*

![image](https://github.com/user-attachments/assets/42f0555d-9a88-4aeb-9a42-55d5588baa99)
## Steps: 

### Prepare the Environment:

1. Install Oracle VirtualBox and ensure you have the Windows Server 2019 and Windows 10 ISO files.
2. Set up a virtual machine (VM) for Windows Server 2019 and configure it as your Domain Controller.
   
### Configure the Network:

3. Refer to the network diagram above to setup DHCP settings and internal networking between the VMs.

### Active Directory Setup:

4. Install Active Directory Domain Services on the Windows Server VM.
5. Configure the AD environment using the FQDN mydomain.com.

### Script Usage:

6. Run Generate-Names-Create-Users.ps1 if you wish to generate new names and create user accounts.
If you prefer to use pre-existing names, execute 1_CREATE_USERS.ps1 with names.txt.

## Purpose of the Lab

This lab serves as a practical application of system administration skills, focusing on network security and Active Directory management. It provides hands-on experience with real-world tasks that are crucial in enterprise network environments.

## Technologies Used
- Oracle VirtualBox
- Windows Server 2019
- Windows 10
- PowerShell
  
>[!NOTE]
*Make sure to adjust the script paths and environment settings based on your local setup to ensure everything functions correctly.*
*Feel free to clone this repository and adapt the scripts and setups as needed for your learning or testing purposes.*

