<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Setup</h1>
This guide details the post-installation configuration process for osTicket, the open-source help desk ticketing system.<br />




<h2>Utilized Environments and Technologies</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Supreme Admin Role
- System Administrators Department
- Level II Support Team
- Configuring new Agents
- Setting SLA's

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/9lUVsMW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the initial step, I established a "Supreme Admin" role within osTicket, granting the role members unrestricted access to all functionalities, allowing them to perform any task or assignment—a state of complete access.
</p>
<br />

<p>
<img src="https://i.imgur.com/jOup3jS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this step, I created a department specifically for system administrators, who are the designated individuals capable of addressing and resolving these issues.
</p>
<br />

<p>
<img src="https://i.imgur.com/6MRny1A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, I'm currently in the process of forming a Level II support team, as illustrated in the image above.
<br />

<p>
<img src="https://i.imgur.com/lHFgiY6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here, as demonstrated, I established a new agent named John Doe. John Doe's access is limited, allowing him to view tickets and be a member of the support team, as indicated in the image above. Before creating John Doe, I also configured another agent named Jane Doe, who has supreme access and is a member of the sys-admin department.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ococ5On.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In this final step, I'll be demonstrating how to configure SLAs. For this specific SLA, I've configured it with a severity level of A, including a 1-hour grace period, and it is scheduled to be completed within a day's time.
</p>
<br />
