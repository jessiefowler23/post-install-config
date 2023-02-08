<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=K7T_JjvEamg)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Created Roles 
- Created Dapartments
- Created Teams 
- Created Agents 
- Users
- Created SLA 

<h2>Configuration Steps</h2>

<p>
<img src=https://i.imgur.com/bsKFB70.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I needed to create a new Role once I had logged back into my OsTicket account. In which I was able to access Permissions and give the Users access to specific areas of the Ticket, Task, and Knowledgebases sections.
</p>
<br />

<p>
<img src=https://i.imgur.com/N2TIxyZ.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that, I had to build a new department so that tickets could be forwarded through it. This enables the prepared document to be assigned a specific issue.
</p>
<br />

<p>
<img src=https://i.imgur.com/86DHVC2.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I had to set up Teams, which enables me to gather agents from various Departments and group them according to the user or issue at hand using a Help topic or Ticket filter.
</p>
<br />

<p>
<img src=https://i.imgur.com/LBrAuoL.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next step is to create default Agents with the identities Jane Doe and John Doe. Then I can proceed to assign the default agents to the appropriate Department and Role. From there, I can add them to the Team I created in the previous slide.
</p>
<br />

<p>
<img src=https://i.imgur.com/hx10Br9.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The Users will then be created by me. When used in this context, the term "users" actually refers to the customer who is the owner of the ticket. A default Ken Ken users account will be made by me. As soon as they are created, the agents will be able to receive tickets from the users.
</p>
<br />

<p>
<img src=https://i.imgur.com/FpnTPLb.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
The next thing I'll do is create an SLA, which is defined as the period during which the ticket will be resolved promptly. I'll go to the OsTicket's Mange section and establish the Sev-A (1 hour, 24/7), Sev-B (4 hours, 24/7), and Sev-C (8 hours, Monday-Friday) of the new SLA plans. When a ticket is received, the agents must follow these three guidelines.
</p>
<br />
