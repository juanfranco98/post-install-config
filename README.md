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

 To configure the following:
- Roles
- Departments
- Teams
- Agents
- Users
- SLA
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/bvKINYW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In order to configure Roles follow this path: Admin Panel -> Agents -> Roles. Once you get there go ahead and create a role called "Supreme Admin".
</p>
<br />

<p>
<img src="https://i.imgur.com/tjYIzXV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, configure Departments by following this path: Admin Panel -> Agents -> Departments. Create a system administrator department
</p>
<br />

<p>
<img src="https://i.imgur.com/CECYwRa.png" height="40%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Continuiue by creating the Teams "Level I Support" and "Level II Support". From the Admin Panel go to Agents and then Teams.
</p>
<br />

<p>
<img src="https://i.imgur.com/wNrJG20.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Now you must make it so that anonymous users can create tickets even if they arent a user of the actual system. To do this go to settings, then user settings, and make sure that "Registration Required" is unchecked.
</p>
<br />

<p>
<img src="https://i.imgur.com/zNv25dV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 We must now create a couple Agents(workers) that we can use to sign in and out of osTicket with to see how tickets would actually look from a workers perspective. Do this by going to the Agents panel and then selecting "Add New". You can use whatever names you'd like, but for simplicity we'll use Jane and John. Create a fake email for each as well as a username. Make sure to uncheck the box that would require password resets as the email doesnt actually exist. Make everyones passwords the same so it isn't forgotten since this is just for practice.
</p>
<br />

<p>
<img src="https://i.imgur.com/iottNGH.png" height="40% width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Lets now create some users(customers) by going to the "Agent Panel" then "Users" and "Add New". Follow the same steps from when we created Jane and John.
 
 
 
 
 
 
 
 
 
