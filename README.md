# Link to Instructions
[Instructions](https://docs.google.com/document/d/1we9svtXa0xQZ3DKBp-ZcrtDgtGvlZaS6XrP6euIt1Gw/edit?usp=sharing)

# Overview 
The purpose of Active Directory in IT is to provide a centralized and organized directory service for managing network resources within a Windows domain environment. Active Directory (AD) is a Microsoft technology that primarily functions as a directory service for Windows-based networks.

- Functions of the Active Directory include:
- User and Group Management
- Authentication and Security
- Resource Management
- Policy Enforcement
- Domain Name System
- Replication and Fault Tolerance
- Directory-Enabled Applications

# Direction of the Project

In this Active Directory project, we will establish Virtual Machines within a Virtual Network. Both the domain controller and client will be equipped with a Network Interface Card (NIC) to obtain an IP address via a Dynamic Host Control Protocol server (DHCP). Additionally, a Domain Name System server (DNS) will be created. 

To ensure a consistent IP address for our Domain Controller and avoid changes from the DHCP server, we will switch the NIC configuration from dynamic to static IP addressing. 

Furthermore, we have configured the DNS settings to point to the Virtual Network's concealed DNS Server. We aim for our Client to utilize our Domain Controller as its designated DNS server. These project configurations will facilitate seamless communication between our virtual machines and enable streamlined interaction among them.

**Configured when we make our Virtual Machines**
![AD1 1](https://github.com/Michael-DTran/Active-Directory/assets/112426094/352bab3b-fe75-4980-a382-f421614df88b)

**After we make our necessary adjustments**
![AD2 1](https://github.com/Michael-DTran/Active-Directory/assets/112426094/4b7e63f4-986f-4fd1-a983-06ea24c73c2d)

# Environments and Technologies Used
- Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- Powershell

# Operating Systems Used
- Windows Server 2022
- Windows 10 (21H2)
  
