<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/2560px-Microsoft_Azure_Logo.svg.png" alt="Microsoft Azure Logo"/>
</p>

<h1>Deploying Virtual Machines Utilizing Microsoft Azure</h1>
This tutorial outlines the implementation of Azure Virtual Machines. And the real life technical implementations as a help desk technician.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
  
<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create a subscription to seperate resource costs.
- Create resource group to hold virtual machines. 
- Create and assign virtual machines (Windows & Linux) to the same virtual network.
- Log in via Remote Desktop and confirm connectivity.

<h2>Deployment and Configuration Steps</h2>

<h3>1. Create a Resource Group</h3>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
  In the Azure portal, create a new Resource Group to organize all related resources. This helps isolate different projects or environments, simplifying management and cost tracking. 
</p>
The virtual network and virtual machines will both be stored in this group.

<br />

<h3>2. Create a Virtual Network</h3>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  Next create a Virtual Network (Vnet). 
  This allows your VMs to:
  <ul>
    <li>Recieve private IP address via DHCP</li>
    <li>Communicate securely with each other</li>
    <li>Connect to the internet if needed</li>
  </ul>
 This setup simulates a real world IT network, where devices operate under the same local network.
</p>
<br />

<h3>3. Deploy Virtual Machines</h3>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 When creating the virual machines: 
</p>
     <ul>
       <li>Name each VM clearly (windows-vm or linux-vm0</li>
       <li>Assign both VMs to the same region of the Virtual Network.</li>
       <li>Choose the apporpriate operating system (Windows 10 & Ubuntu).</li>
       <li>Set up authentication to allow secure Remote Desktop access.</li>
     </ul>
     <p>
       Once both machines are deployed, connect to the Windows VM using Remote Desktop Protocol and confirm connectivity with the Linux VM via ping.
     </p>
    This confirms both VMs are active, networked, and communicating properly.
<br />
<h2>Real World Help Desk Application</h2>
 
 <h3>1. Simulating Real IT Environments</h3>
     Familiarity in VM environments allows for help desk technicians to be fimiliar with diagnosis of issues, test updates in a controlled environment and setting up networks and understanding how they work in a large scale.
 <h3>2. Understanding Networking & Connectivity</h3>
   Help desk technicians need to understand basic networking concepts such as IP addressing, DNS, and network connectivity to troubleshoot when users can't access network resources.
 <h3>3. Practicing Secure Access & Permissions</h3>
   Help desk technicians often assist with account creation, password resets, and remote access troubleshooting which are all essential for maintaining secrure and efficient operations.
 <h3>4. Efficient Resource Management</h3>
  Mirrors how IT departments segment resources, like users, servers, and devices, by departments or projects in order to track usage, cost, and configurations more efficiently. 
