<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
  
<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Subcription to seperate resource cost
- Create Resource Group to hold virtual machines 
- Create and assign virtual machines (windows & linux) to same virtual network
- Log in via Remote Desktop and confirm connectivity

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  In azure portal create a new resource group to organize everything seperately based on resource use. This is where the virtual network and virtual machines will be stored in.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  The next step is to create a virtual network, the purpose is to have a network that the vms will be able to connect to; the ability to recieve IP adresses, communicate with devices across the network, and have access to the internet. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  To create the virtual machines certain assignments need to be reach, name each vm respectively 
    - Assign to same region
    - Apply to same network 
    - Assign corresponding operating system for Windows and Linux VM
    - Create user name and password to be able to access with Remote Desktop
    - 
</p>
<br />
