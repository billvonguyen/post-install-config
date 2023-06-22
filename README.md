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

- Configure Roles, Departments, and Teams 
- Grant access to anyone to create tickets
- Configure Agents(workers), Users(customers), and SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/wJCXRxZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Once signed into osTicket using the username and password created in the osTicket Installation guide, you'll want to create a role within osTicket. To do so you'll want to navigate to Roles by making sure that you're on the "Admin Panel" of the page, click "Agents" then "Roles" and "Add New Role".

</p>
<img src="https://i.imgur.com/eh7yoGT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<p>
From here we will be creating a Supreme Admin role. So name the role as "Supreme Admin" as shown below.
</p>
<img src="https://i.imgur.com/SdjSZH0.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

Click on the "Permissions" tab and grant that particular role access to all of the options as shown below for "Tickets","Tasks", and "Knowledgebase".

<img src="https://i.imgur.com/7bp20ez.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/ARzC9Ch.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

Next step is to create our "Departments", proceed by clicking on "Agents" then "Departments" then "Add New Department".

<img src="https://i.imgur.com/zpK6G5I.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

For this example it's okay to leave everything as is by default and just name the department "System Administrators" as shown below.

<img src="https://i.imgur.com/rcRY3eV.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

Next thing to do is to create a "team" basically our group of Tech Support Specialists page, in order to do so you must click on the "Teams" tab under "Agents" and for our example we will name the team "Level II Support" and click "Create" as shown below.

<img src="https://i.imgur.com/0yNphRh.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>
  
2. 2nd Step is to allow access to anyone to create tickets, this step is pretty simple. Just click on "Settings" then "Users" and make sure that the "Registration Required" checkbox is left unchecked and that's it.
</p>
<img src="https://i.imgur.com/Zg4QjLf.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<br />

<p>
3. 3rd Step is to create our "Agents", so click on the "Agents" tab, "Agents", and "Add New Agent".
  
</p>
<p>
For our Agent example you may name it to however you like as well as the email but please do take note of the username, email, and password just incase so you don't forget! You may assign the particular agent any "status" or "settings" to whatever you like as well.
</p>
<img src="https://i.imgur.com/mVruAQ5.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

Click on over to the "Access" tab and for this example we'll assign this agent to "System Administrators" with the access to "System Admin" powers that we created earlier. And as for the permissions tab everything should be left alone by default and we'll assign the agent to "Level II Support" in the "Teams" tab.

<img src="https://i.imgur.com/lNXEOFS.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>For our next step we'll be creating "Users" for our osTicket so in this example you'll first want to switch over to the "Agent Panel" so go ahead and click "Agent Panel" in the top right corner of the osTicket webpage.</p>
<img src="https://i.imgur.com/uW0E5MC.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Make your way to the "User Directory" by clicking on the "Users" tab then click "Add User".</p>

<img src="https://i.imgur.com/qNWGIyr.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>Name the user to whatever you like and click "Add User".</p>

<img src="https://i.imgur.com/WiBEP9p.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<br />

<p>
Next is to create an SLA to do so you must head back to the "Admin Panel", you must click on "Admin Panel" in the top right corner of the osTicket webpage then click on the "Manage" tab then "SLA".
</p>
<img src="https://i.imgur.com/wdMBmIJ.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

For this SLA example you'll be creating a schedule of 24/7 with a grace period of 1 hour. And you can add more SLA plans with different schedules if you want to.

<img src="https://i.imgur.com/8Ohk8dL.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>

<p>
4. 4th Step is to create Help Topics for our System Admins to review and help our Users. To do so make sure that we're in the Admin Panel, click the "Manage" tab, then click "Help Topics" and "Add New Help Topic". From here you can add as many "Help Topics" as you like, but for this example you can just add one and name it "Business Critical Outage".
</p>
<img src="https://i.imgur.com/yqnZJ8h.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/pk8Sadm.png" height="70%" width="70%" alt="Disk Sanitization Steps"/>
