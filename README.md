<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments, Teams, Agents, and Users
- Allow anyone to create tickets
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure departments and teams, access the Admin Panel and navigate to Agents. Under Departments, system administrators can organize various departments, while under Teams, teams like Level I Support and Level II Support can be createed and managed. To allow ticket creation by anyone, go to the Admin Panel, then Settings, and enable "Registration Required" to enforce registration and login for ticket creation. Agents can be configured by accessing the Admin Panel, going to Agents, and adding new agents like Jane and John. Similarly, users can be configured by accessing the Agent Panel, navigating to Users, and adding new users such as Karen and Ken.</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure the SLA, go to the Admin Panel, select Manage, then choose SLA, and create the following service level agreements: Sev-A with a 1-hour response time available 24/7, Sev-B with a 4-hour response time available 24/7, and Sev-C with an 8-hour response time during business hours.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure Help Topics, navigate to the Admin Panel, select Manage, then go to Help Topics, and create the following topics: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset.</p>
<br />
