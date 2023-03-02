# post-install-config
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

- Configure roles, departments, and teams
- Allow Anyone to create tickets
- Configure Agents and user (workers)
- Create a New SLA plan
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/MV4gETE.png" height "="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. Created a role called Supreme Admin with access and permission to do ultimately anything on OS Ticket. Departments were created with teams for specific roles such as level I and level II support.
</p>
<br />

<p>
<img src="https://i.imgur.com/d7zpLvH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
User were created to experience role power and to mimic real life scenarios with IT suppport tickets. The users were added to departments/teams giving them a specific job in the open source ticketing system.
</p>
<br />

<p>
<img src="https://i.imgur.com/CpO8t9h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SLA Plans are created by going to the Admin Panel > Manage > SLA Plans. Agents can apply a timeslot or due date for the SLA plan. Sets a deadline and the urgency for a ticket's completion.
</p>
<br />
