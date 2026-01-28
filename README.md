# configure-ad
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
- Windows 11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Install Active Directory 
- Create a Domain Admin user within the domain
- Join VM to the domain
- Set up Remote Desktop for non-admin users on VM
- Create additional users with PowerShell 

<h2>Deployment and Configuration Steps</h2>
</p>
</p>
<p>
Install Active Directory Services on Virtual Machine 1
</p>
</p><img width="783" height="556" alt="Screenshot 2026-01-27 184016" src="https://github.com/user-attachments/assets/50a72dd3-3d35-4fba-90ff-ac511e7f14ff" />
</p>
<br />
</p>
<p>
Create an admin account
</p>
<p>
<img width="461" height="217" alt="Screenshot 2026-01-28 031341" src="https://github.com/user-attachments/assets/fb98086e-3be9-4a9c-9802-a1a7b767c831" />

<p>
Create a new Organizational Unit (OU) in Active Directory and Computers (ADUC)
</p>
<br />

<img width="1102" height="834" alt="Screenshot 2026-01-28 045822" src="https://github.com/user-attachments/assets/82c139a6-cedd-4f71-928b-a1a333b95b50" />


<p>
Create users with PowerShell
</p>
</p><img width="1641" height="958" alt="Screenshot 2026-01-28 050157" src="https://github.com/user-attachments/assets/e34b3b99-c9d4-434e-b595-2a93ef5b7ad4" />
</p>
<br />
