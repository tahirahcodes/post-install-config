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
<h3>Configure Roles</h3>
<p>
<img src="https://imgur.com/FNVLJJM.png" height="80%" width="80%" />
</p>
<p>
Go to localhost/osTicket to access the software. Sign in with the Admin username and password created in the last step of the installation process. 
</p>
<br />

<p>
<img src="https://imgur.com/z75inSr.png" height="80%" width="80%"/> 
<p> Go to the Admin Panel in the top right.
</p>
</br>

<p>
  <img src="https://imgur.com/H8wEizB.png" height="80%" width="80%"/> 
</p>
<p>
Select Agents then Add New Role. Name it Supreme Admin.
</p>
<br />

<p>
  <img src="https://imgur.com/CH8HRbT.png" height="50%" width="50%"/> 
</p>
<p>
Under Permissions select all checkboxes under Tickets.
</p>
<br />

<p>
  <img src="https://imgur.com/QsBRV6Z.png" height="50%" width="50%"/> 
</p>
<p>
Under Tasks, ensure all the checkboxes is selected.
</p>
<br />

<p>
  <img src="https://imgur.com/17FSifr.png" height="80%" width="80%"/> 
</p>
<p>
Under Knowledgebase, select Premade, then select Add Role.
</p>
<br />

<h3>Configure Departments</h3>
<p>
  <img src="https://imgur.com/9Hkdyfo.png" height="80%" width="80%"/> 
</p>
<p>
Navigate to the Departments tab, then select Add New Department
</p>
<br />

<p>
  <img src="https://imgur.com/wkrKoeM.png" height="80%" width="80%"/> 
</p>
<p>
Name it System Adminstrators then select Create Dept.
</p>
<br />

<h3>Configure Teams</h3>
<p>
<img src="https://imgur.com/97tuhf5.png" height="80%" width="80%"/> 
<p>
  <p>
    Navigate to the Teams tab, then select Add New Team.
  </p>
  </br>

<img src="https://imgur.com/0GlyVQy.png" height="80%" width="80%"/> 
<p>
  <p>
    From the dropdown select your user profile, select Add, then Create Team.
  </p>
  </br>

<h3>Configure Agents</h3>

<p>
<img src="https://imgur.com/sa2rq0G.png" height="80%" width="80%"/> 
<p>
  <p>
    Go to the Agents Tab then select Add New Agent.
  </p>
  </br>
  
<p>
<img src="https://imgur.com/M11rbQX.png" height="80%" width="80%"/> 
<p>
  <p>
    Enter the name, email and username for the agent. Select Set Password.
  </p>
  </br>
  
<img src="https://imgur.com/QH7dxHf.png" height="50%" width="50%"/>
</p>
<p>
On the prompt, deselect "Send the agent a password reset email". Create the agent's password then deselect require password change at next login, then select Set.
</p>
<br />

<p>
<img src="https://imgur.com/uxE5820.png" height="80%" width="80%"/>
</p>
<p> Go to the Access tab. For Department, select System Administrators, then under role, select Supreme Admin.</p>
</br>

<p>
<img src="https://imgur.com/UGQgbiS.png" height="80%" width="80%" /> 
</p>
<p>
Next go to the Teams tab , select Level II support, Add, then Create. Create a second agent but for the Department, select Support, then under role select View Only.
</p>
<br />

<h3> Configure SLA </h3>

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

<h3>Confgure Help Topics</h3>

<p>
<img src="https://imgur.com/C8cj9Kg.png" height="80%" width="80%"/> 
</p>
<p>
Navigate to the Help Topics tab, then Add New Help Topic.
</p>
<br />

<p>
<img src="https://imgur.com/lLhylH6.png" height="50%" width="50%"/> 
</p>
<p>
Name the topic Business Critical Outage, then select Add Topic. Add three more topics: 
</br>

  Personal Computer Issues </br>
  Equipment Request </br>
  Password Reset
</p>

<h3>Configure Users</h3>
<p>
<img src="https://imgur.com/VH6Qy32.png" height="50%" width="50%"/> 
</p>
<p>
Navigate to the Agent Panel at the top right. Select the Users tab, then Add User
</p>

<p>
<img src="https://imgur.com/Nmpepyw.png" height="50%" width="50%"/> 
</p>
<p>
Enter the an email address and fullname of the user, then select Add User. Add a second user with a different email and name.
</p>

<p> <strong>The Post Installation Setup is Now Complete</strong></p>
