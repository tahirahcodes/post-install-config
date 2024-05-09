<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (Employees)
- Configure Users (Customers)

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/FNVLJJM.png" height="80%" width="80%" />
</p>
<p>
Go to localhost/osTicket to access the software. Sign in with the Admin username and password created in the last step of the installation process. 
</p>
<br />

<p>
<img src="https://imgur.com/z75inSr.png" height="50%" width="50%"/> <img src="https://imgur.com/H8wEizB.png" height="50%" width="50%"/> 
</p>
<p>
Go to the Admin Panel in the top right, then select Agents Then Add New Role.
</p>
<br />

<p>
<img src="https://imgur.com/M11rbQX.png" height="40%" width="40%"/> <img src="https://imgur.com/QH7dxHf.png" height="40%" width="40%"/>
</p>
<p>
Enter the name, email and username for the agent. Select Set Password. On the prompt, deselect "Send the agent a password reset email". Create the agent's password then deselect require password change at next login, then select Set.
</p>
<br />


<p>
<img src="https://imgur.com/uxE5820.png" height="50%" width="50%"/> <img src="https://imgur.com/UGQgbiS.png" height="50%" width="50%" /> 
</p>
<p>
Go to the Access tab. For Department, select System Administrators, then under role, select Supreme Admin. Next go to the Teams tab , select Level II support, Add, then Create. Create a second agent but for the Department, select Support, then under role select View Only.
</p>
<br />

<p>
<img src="https://imgur.com/YsAPuZm.png" height="80%" width="80%"/>
</p>
<p>
Go to the Manage tab, select SLA, then Add New SLA Plan.
</p>
<br />

<p>
<img src="https://imgur.com/NHogKsR.png" height="50%" width="50%"/> 
</p>
<p>
Name this SLA plan SEV A, Add 1 hour in the Grace Period, then select 24/7 in the dropdown for Schedule. Next add two more SLA plans: 

</br>
  Name: Sev B </br>
  Grace Period: 4 </br>
  Schedule: 24/7 </br>

  Name: Sev C </br>
  Grace Period: 8 </br>
  Schedule: Monday - Friday 8 am - 5pm with U.S. Holidays
  
</p>
<br />

<p>
<img src="https://imgur.com/z75inSr.png" height="50%" width="50%"/> 
</p>
<p>
Go to the Admin Panel in the top right, then select Agents Then Add New Role.
</p>
<br />

<p>
<img src="https://imgur.com/z75inSr.png" height="50%" width="50%"/> <img src="https://imgur.com/H8wEizB.png" height="50%" width="50%"/> 
</p>
<p>
Go to the Admin Panel in the top right, then select Agents Then Add New Role.
</p>
<br />

<p>
<img src="https://imgur.com/z75inSr.png" height="50%" width="50%"/> <img src="https://imgur.com/H8wEizB.png" height="50%" width="50%"/> 
</p>
<p>
Go to the Admin Panel in the top right, then select Agents Then Add New Role.
</p>
<br />
