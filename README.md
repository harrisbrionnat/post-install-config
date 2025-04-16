<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

There are two URLs used for logging into osTicket  that will be covered in this tutorial. One is for Admins/Analysts (http://localhost/osTicket/scp/login.php)  and the other is for End-Users (http://localhost/osTicket)

- Agent VS. Admin Panel
- Roles
- Departments
- Teams
- Agents
- Users
- SLAs
- Help Desk Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Roles allow us to give permissions to specific agents. There are default roles: All Access, Expanded Access, Limited Access, and View Only, but we can also add a new role. To do this, click on 'Add New Role' and Type the name of the role. If I wanted to create a role for a 'Super Admin' who had access to every feature, I could type 'Super Admin' as a name a give this role every single permission. Then click 'add'.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Departments allow for ticket visibility to specific departments within in organization, such as Maintenance, IT Support, Sales, etc. For instance, I could create a 'Sales' department by clicking 'add new department' and typing in 'Sales'. I could also provide a number of other configuration options I would like for this department to have under Settings.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Teams allows us to field agents/employees from different departments to work on specific tickets. For instance I could create a team for online banking which would have agents from different departments who work tickets that deal with online banking. To create this team, I would go to Agents-->Teams-->Add New Team. Then name it Online Banking.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Agents are specific workers for IT Support that are working the tickets. If I wanted to add a new agent named Timmy Jones, I would go to the Admin Panel--> Agents-->Add New Agent and type in Timmy Jones. I would also be able to do things like assign him a role and department through the Access tab. I could also set him a password by clicking 'set password' and clicking 'reset'.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Users are customers who will be submitting their tickets to be worked by agents. If I wanted to create a user named Bill Harris, I would go to the Agentt Panel-->Users--> Add User. Then I'd type in Bill's email address and full name.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLAs, or, Service Level Agreements, are stipulations on how long it should take one to respond or resolve a ticket based on a certain criteria. To configure an SLA, go the Admin Panel-->Manage-->SLA, If I wanted to create an SLA with a severity level of Sev-A, a grace period of 1 hour and a schedule of 24/7, I would click 'Add New SLA Plan'. Name it Sev-A, give it a grace period of one hour, and a schedule of 24/7. Then click 'Add Plan'.
</p>
<br />
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help Topics help us categorize help desk ticket issues. To configure these, go to Admin Panel--> Manage--> Help Topics. If I wanted to create a help desk topic for password resets I would click 'Add New Help Topic', type 'Password Reset' as the Topic and select an appropriate parent topic from the drop down menu.
</p>
<br />
