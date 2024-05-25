# osTicket-Post-Installation-Configuration
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
- Allow Anyone to Create Tickets
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once you log in to osTicket, choose the Admin Panel option. Cick on the Agents tab, followed by Roles. Create a new Role under Supreme Admin. Under the Permissions tab, check all boxes for Tickets, Tasks, and Knowledgebases.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Return to the Agents tab and choose Departments. Click the "Add a New Department" buton. Name the new department "System Administrators" and create the new Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Return to the Agents tab and choose Teams. Click the "Add New Team" button. Name the new Team "Level II Support". Under the Admin Panel, go to Settings, Users, then Authentication Settings. Check the "Require Registration and Login" box then save changes.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the Agents tab, choose Add New Agents and create both "John Doe" and "Jane Doe". Set passwords for both new Agents.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the Agent Panel, choose Users tab and add both "Karen" and "Ken" Users. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the Admin Panel, under the Manage Tab, choose SLA and click the New SLA PLan button. Create the following SLAs with the appropriate Grace Periods and Schedules: SEV-A (1 hour, 24/7), SEV-B (4 hours, 24/7), SEV-C (8 hours, business hours).
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Under the Admin Panel, under the Manage Tab, choose Help Topics and create the following Help Topics: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.
</p>
<br />
