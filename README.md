<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Set up a new forest/domain 
- Create a Domain Admin & Organizational Units
- Log in to the domain as the Admin and as a User

<h2>Deployment and Configuration Steps</h2>
<h3>Install Active Directory & add a new forest/domain</h3>
<p>
<img src="https://i.imgur.com/GMgA4lS.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<img src="https://i.imgur.com/0sx8FuG.png" alt="Disk Sanitization Steps" width="70%"/>

</p>
<p>
<h3>Create The Organizational Units "Employees" and "Admins" </h3>
<img src="https://i.imgur.com/HvokojN.png height= alt="Disk Sanitization Steps" width="70%"/>
<p></p>

<h3>Create the Domain Admin "Jane Doe" </h3>
<p></p>
<img src="https://i.imgur.com/pvozL2p.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<img src="https://i.imgur.com/mkRP7qS.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<h3> Drag Client-1 into the _Clients folder</h3>
<p></p>
<img src="https://i.imgur.com/GYf7Xn7.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<h3>Log in to Client-1 Virtual Machine and join the domain created prior</h3>
<p></p>
<img src="https://i.imgur.com/CV47waW.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<h3>Log in to Client-1 as a non-administrative user "Jim Scott"</h3>
<p></p>
<img src="https://i.imgur.com/juVh9JY.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<img src="https://i.imgur.com//Dp34yFf.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<img src="https://i.imgur.com/5mT4twt.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>
<img src="https://i.imgur.com/EBvT7Ij.png" alt="Disk Sanitization Steps" width="70%"/>
<p></p>

<h2>The End of The Lab, Check Out The Other Labs</h2>
Network Security Groups (NSGs) and Inspecting Network Protocols:
(https://github.com/JHeard0/azure-network-protocols)
<p></p>
osTicket: Ticket Lifecycle Examples:
(https://github.com/JHeard0/ticket-lifecycle)
