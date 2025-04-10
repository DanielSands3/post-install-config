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

- Create Roles
- Create Departments
- Create Teams
- Allow anyone to create tickets
- Create Agents
- Create Users
- Create SLA's
- Create Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="440" alt="image" src="https://github.com/user-attachments/assets/5a884749-ae47-40b4-b15e-7b60ac18af92" />
</p>
<p>
The first part of our post installation configuration will be creating roles. Here we create a new role of Supreme Administrator which has access to all possible functionalties in contrast to other roles which have restrictions.
</p>
<br />

<p>
<img width="437" alt="image" src="https://github.com/user-attachments/assets/da0d73a4-ec44-49fb-b5a4-a974e87b262e" />
</p>
<p>
Next, we create a new Department. Departments are responisble for ticket visibility. In this example a Sysadmins department is made which can oversee all tickets. 
</p>
<br />

<p>
<img width="437" alt="image" src="https://github.com/user-attachments/assets/71bd72ae-6508-462f-9b49-e8477909a528" />
</p>
<p>
Next, we configure a Team. A Team is used when multiple members from different departments are used in combination with eachother. For example we could have Sysadmin on the Online Banking Team in addition to the teams own designated Online Banking Members. 
</p>
<br />

<p>
<img width="440" alt="image" src="https://github.com/user-attachments/assets/5c1ea6d1-162b-43c4-ae61-ba620ca9a684" />
</p>
<p>
Next navigate over to User settings and allow anyone to create tickets. This will allow us to create mock tickets and begin the ticket life-cycle.
</p>
<br />

<p>
<img width="442" alt="image" src="https://github.com/user-attachments/assets/a76292e6-5a8c-4257-a983-44b99b8876e5" />
</p>
<p>
After, we navigate over to the Agents panel and create new Agents. In this example we create an Agent named John which will be assigned to the Support Department and will have View Only access to tickets.
</p>
<br />

<p>
<img width="297" alt="image" src="https://github.com/user-attachments/assets/e8e54464-a99f-4054-9346-e4a16ef2f3b8" />
</p>
<p>
Next, we navigate to the User section and create a new User. This User will be creating a ticket for the analyst to work to completion.
</p>
<br />

<p>
<img width="440" alt="image" src="https://github.com/user-attachments/assets/eabbaf43-d8e0-4e3e-92ca-8be54f18b5a7" />
</p>
<p>
Next, we create new SLA's (Service Level Agreements) to assign to tickets in the future. In this case we create a new SLA of Sev-A with a 1hr grace period on a 24/7 schedule. 
</p>
<br />

<p>
<img width="445" alt="image" src="https://github.com/user-attachments/assets/95c75111-b4e5-480a-8bbc-ac330360a87e" />
</p>
<p>
Lastly, we configure Help Topics or categories for end users to pick from when creating a ticket.
</p>
<br />
