<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Create Domain Controller VM (Windows Server 2022) and Client VM (Windows 10) in Azure portal.
- Step 2: Check Connectivity between the client and domain controller. 
- Step 3: Install AD Services on DC VM. Setup new forest ex. mydomain.com.
- Step 4: Create an Admin and Normal User Account in Active Directory.
- Step 5: Log into Client VM and join newly created domain.
- Step 6: Setup Remote Desktop for non-administrative users. After configuring system properties,you should be able
          to successfully log in as Admin or Non-admin user.

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/YrkucMv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Installing AD on the Domain Controller.
</p>
<br />

<p>
<img src="https://i.imgur.com/DvC01io.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adding new user to AD.
</p>
<br />

<p>
<img src="https://user-images.githubusercontent.com/124535030/219548082-00d03620-18d4-41de-82af-3860d70fe9a4.mp4
" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Unlocking user account using AD.
</p>




<br />
