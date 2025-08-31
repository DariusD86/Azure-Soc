<p align="center">
<<img width="1994" height="1126" alt="image" src="https://github.com/user-attachments/assets/c046c1e3-0596-4967-bcbd-e6e57e45b152" />

</p>

<h1>Microsoft Azure Honeypot - Introduction</h1>
In this project, I will develop a basic home soc utilizing Microsoft Azure. The project involves creating a virtual machine (VM), exposing it to the internet as a honeypot, and forwarding logs to a centralized repository. Subsequently, we will integrate Microsoft Sentinel to analyze real-world attack data.
 .<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Microsoft Sentinel
- remote desktop

<h2>Operating Systems Used </h2>

- Windows 10 pro</b> 

<h2>What we will cover in this project</h2>

- Creating an Azure subscription and setting up a VM
- Configuring Log Analytics Workspace
- Forwarding logs and integrating with Sentinel
- Querying failed login attempts and visualizing attack sources
- Building an attack map to track real-time hacker activity

<h2><h2>Building the architect</h2></h2>

<p>
<<img width="701" height="387" alt="image" src="https://github.com/user-attachments/assets/5554502a-a926-443d-95d2-e47733db2833" />
 
</p>
<p>
To begin, I provisioned a Resource Group, assigning it a designated name and selecting "East US 2" as the deployment region. Subsequently, I established a Virtual Network (VNet), ensuring it resided within the same region and associating it with the previously created Resource Group. The VNet was configured with a specific name for easy identification.

Moving forward, I deployed a Virtual Machine (VM), naming it appropriately and linking it to the existing Resource Group to maintain regional consistency. The operating system selected was Windows 10 Pro. During the VM setup, I configured administrative credentials, specifying a unique username and a secure password. Additionally, I selected the preferred disk type and enabled the necessary options for optimal performance.

In the networking configuration phase, I modified the Network Security Group (NSG) settings to allow all inbound traffic, facilitating external connectivity to the VM. Post-deployment, I accessed the VM using Remote Desktop Protocol (RDP) and disabled the Windows Firewall to prevent any potential connection restrictions.

Finally, I executed a network diagnostic by pinging the Virtual Machine to verify its availability and confirm that it was accessible within the network environment.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
