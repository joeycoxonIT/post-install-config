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
