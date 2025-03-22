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

- Configure Agents

- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="806" alt="Created roles for new agents" src="https://github.com/user-attachments/assets/34ef17c4-0105-441f-9e4f-41f2a25ac146" />

</p>
<p>
1. Navigate to Admin Panel: Got to Admin Panel > Manage > Roles.
2. Add a Role: Click New Role and provide a role name (e.g., "Supreme Admin").
3. Set Permissions: Assign permissions for tickets, knoledgebase, staff management, etc., based on the role's responsibilities.
4. Save Changes: Click Save to apply the role settings.
</p>
<br />

<p>
<img width="799" alt="Set up new agents departments" src="https://github.com/user-attachments/assets/5c5fbac8-549a-4182-9c01-520091e06f5f" />

</p>
<p>
1. Navigate to Admin Panel: Got to Admin Panel > Manage > Departments. 2. Add a Department: Click Add New Department, provide a name (e.g., "SysAdmins"), and assign a department head. 3. Set Department Settings: Configure options like email, ticket routing, and permissions. 4. Save Changes: Click Save to apply the department configuration.
</p>
<br />

<p>
<img width="766" alt="New agents access setup" src="https://github.com/user-attachments/assets/1fc1060d-169f-40cd-af02-5442c85e40cf" />

</p>
<p>
1. Navigate to Admin Panel: Go to Admin Panel > Manage > Staff. 2. Add New Agent: Click Add New Staff Member, enter the agent's details (name, email, access). 3. Assign Departments: Choose which departments the agent will have access to. 4. Set Permissions: Configure permissions for ticket handling, reporting, etc. 5. Save Changes: Click Save to create the agent profile.
</p>
<br />

</p>
<img width="777" alt="Created Service Level Agreements for severity" src="https://github.com/user-attachments/assets/5e784449-1f3e-46f2-96d1-01b8483d22cb" />

</p>
<p>
1. Navigate to Admin Panel: To to Admin Panel > Manage > SLA. 2. Add New SLA: Click Add New SLA and provide a name and description. 3. Define SLA Targets: Set response and resolution times for each priority level (e.g., High Sev-A, Medium Sev-B, Low Sev-C). 4. Save Changes: Click Save to activate the SLA.
</p>
<br />

<p>
<img width="749" alt="Created Help topics" src="https://github.com/user-attachments/assets/50c25190-073d-439d-81a4-66f7b02dfbf3" />

</p>
<p>
1. Navigate to Admin Panel: Go to Admin Panel > Manage > Help Topics. 2. Add New Topic: Click Add New Help Topic, then provide a name and description. 3. Assign Categories: Choose relevant ticket categories and configure the visibility settings (e.g., Password Reset, Business Critical Outage, etc.). 4. Save Changes: Click Save to apply the new help topic.

