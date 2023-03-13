<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

 Create a Domain controller (DC-1) running Windows Server22 and a Virtual Machine (Client-1) running Windows 10 inside if Microsoft Azure.
 
 Login to DC-1 and install Active Directory Domain Services.

 Join Client-1 to the created domain. (mydomain.com)

 Open Powershell_ISE as an administrator. Create a new file and paste the contents of the employee name population script into it. Create a buncn of additional users   and attempt to login to Client-1 as one of the users.
 
 Sharing out resources over the network by creating sample file shares with various permissions.

Set the following permissions (share the folder) for the “Domain Users” group:

Folder: “read-access”, Group: “Domain Users”, Permission: “Read”

Folder: “write-access”, Group: “Domain Users”, Permissions: “Read/Write”

Folder: “no-access”, Group: “Domain Admins”, “Permissions: “Read/Write

Normal domain users are granted permission to only read from the "read-access" group, read and write in the "write-acces" group, and not access the "no-access" group at all. Admin only are allowed permission to access the "no access" group.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/HBDt4Md.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a domain controller named DC-1 and a virtual Machine named Client-1 inside of a Micrsoft Azure resource group.
</p>
<br />

<p>
<img src="https://i.imgur.com/yN3fIDd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Install Active Directory Domain Services on Domain Controller DC-1.
</p>
<br />

<p>
<img src="https://i.imgur.com/rhP1rSn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Join Client-1 to the created domain name for the domain controller DC-1. (mydomain.com)
</p>
<br />

 
<p>
<img src="https://i.imgur.com/tNFMxRP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open Powershell_ISE as an administrator.
</p>
<br />

<p>
<img src="https://i.imgur.com/4SHVgrG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a new file and paste the contents of the employee name population script into it. Create a buncn of additional users. 
</p>
<br />

<p>
<img src="https://i.imgur.com/rb4ieTw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/EQXNfOj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Attempt to login to Client-1 as one of the users. In this case, the user name chosen from the random list generated in Powershell_ISE in the previous section was Falojo.Kugori.
</p>
<br />

<p>
<img src="https://i.imgur.com/EQXNfOj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Attempt to login to Client-1 as one of the users. In this case, the user name chosen from the random list generated in Powershell_ISE in the previous section was Falojo.Kugori.
</p>
<br />

<p>
<img src="https://i.imgur.com/EQXNfOj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Attempt to login to Client-1 as one of the users. In this case, the user name chosen from the random list generated in Powershell_ISE in the previous section was Falojo.Kugori.
</p>
<br />

<p>
<img src="https://i.imgur.com/EQXNfOj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Attempt to login to Client-1 as one of the users. In this case, the user name chosen from the random list generated in Powershell_ISE in the previous section was Falojo.Kugori.
</p>
<br />
