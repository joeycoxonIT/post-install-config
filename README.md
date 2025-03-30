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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
First, we will configure roles. Go to this link: "http://localhost/osTicket/scp/login.php" and login using your admin credentials. Once you’re logged in, go to “Agent Panel” at the top right of the screen, then select “Agents” -> “Roles”. Then click “Add New Role”.
</p>
<p>
<img src="https://i.imgur.com/S9au8gB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Once that’s done, we will now create a role for someone with full access, for this tutorial, we will name it “Supreme Admin”. Then select “Permissions” and make sure all permissions are checked. Then click "Add Role".
</p>
<p>
<img src="https://i.imgur.com/UAkhEh9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/l0hLmB9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/AkXf5Ye.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/vM5H8Gd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next we will configure departments. Go back to your Admin Panel, then click “Agents” -> “Departments”. Then select “Add New Department”.
</p>
<p>
<img src="https://i.imgur.com/Zev2asQ.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
For “Parent”, click on the drop-down list that reads “--Top Level Department–” and select “Support”. Then name the department “SysAdmins”. Then scroll to the bottom and click “Create Dept”.
</p>
<p>
<img src="https://i.imgur.com/01AKRc4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next we will configure teams. Select “Agents” -> “Teams” and click “Add New Team”. Then give the team a name. For this tutorial, we will name it “Online Banking” Then click “Create Team”.
</p>
<p>
<img src="https://i.imgur.com/CPMCiGg.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/AVwcQs6.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Ticket Permissions
Next we will allow ticket permissions for everyone. Go to “Settings” -> “Users” and make sure the check box within “Registration required” is unchecked. Then click “Save Changes”.
</p>
<p>
<img src="https://i.imgur.com/coMMIpq.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next we will add agents. Go back to your Admin Panel then click “Agents” -> “Add New Agent”.
</p>
<p>
<img src="https://i.imgur.com/sy3p2qg.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create the agent.
</p>
<p>
<img src="https://i.imgur.com/0zV5LTO.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then assign “Access”, “Permissions”, and “Teams” to the agent whatever you deem necessary. Once that's done, click "Create".
</p>
<p>
<img src="https://i.imgur.com/ymaXtHz.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/cpSrqjw.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ljESbLF.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next we will add users. Go to your Agent Panel at the top right of the page. Then click “User” -> “Add User”. Then enter the user’s email and name.
</p>
<p>
<img src="https://i.imgur.com/omMG7sE.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/LOjJxFC.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/ZLl7Zy8.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Next we will configure SLA. Go back to your Admin Panel. Then click “Manage” -> “SLA” -> “Add a New SLA Plan”.
</p>
<p>
For this tutorial we will create three SLA plans:
</p>
<p>
Sev-A (Grace Period: 1 hour, Schedule: 24/7)
</p>
<p>
Sev-B (Grace Period: 4 hours, Schedule: 24/7)
</p>
<p>
Sev-C (Grace Period: 8 hours, Business Hours)
</p>
<p>
<img src="https://i.imgur.com/0E1Qlvb.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/8ij75n6.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
Lastly, we will configure help topics. Go back to your Admin Panel, then click “Manage” -> “Help Topics”. For this tutorial, we will create these help topics:
</p>
<p>
Business Critical Outage
</p>
<p>
Personal Computer Issues
</p>
<p>
Equipment Request
</p>
<p>
Password Reset
</p>
<p>
Other
</p>
<p>
<img src="https://i.imgur.com/5OJd8rO.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/TCPQ2gZ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
</p>
<br />

<p>
That concludes this tutorial, congratulations!
</p>
