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

- Configure Roles and permissions
- Configure departments
- Configure teams
- Configure agents
- Configure SLAs
- Adding users (Customers)

<h2>Configuration Steps</h2>

![image](https://github.com/BAHIIZI/post-install-config/assets/164538571/e97b96c3-83fa-4694-a6da-8c206c8b9bf5)

This is the agents' panel in osTicket. The agents' panel in osTicket provides agents with a comprehensive set of tools and functionalities to effectively manage and respond to customer support tickets, ensuring timely and efficient resolution of customer inquiries and issues.

Adding users (Customers);

1. Access Agent Panel: Log in as an agent to osTicket.
2. Navigate to Users: Go to the "Users" section in the agent panel.
3. Add New User: Click on the "Add New User" button.
4. Enter User Details: Fill in the user's information, such as name, email address, and any other relevant contact details.
5. Set User Role: Choose the appropriate user role for the user. This may include options like "End User" or "Customer."
6. Save the User: Click "Save" or "Add User" to save the user configuration.


![image](https://github.com/BAHIIZI/post-install-config/assets/164538571/1e5f8aa2-6b3f-40f9-84c0-3aec82ad8554)

This is the Admin Panel in osTicket. The Admin panel in osTicket provides administrators with a comprehensive set of tools and settings to configure, customize, and manage the osTicket helpdesk system according to their organization's needs and requirements.

configuring roles & permissions;

1. Access Admin Panel: Log in as an admin to osTicket.
2. Navigate to Roles & Permissions: Go to "Manage" and select "Roles & Permissions."
3. Create a New Role: Click "Add New Role."
4. Define Role Permissions: Check or uncheck permissions for actions like viewing, replying, and closing tickets, accessing departments and reports, modifying settings, etc.
5. Save the Role: Click "Save Changes" to save.
6. Assign Agents: Edit agent profiles to assign roles.
7. Assign Permissions to Users: Edit user profiles to assign roles.
8. Modify Existing Roles: Edit or delete existing roles as needed.
9. Test Roles: Ensure roles grant appropriate access.

Configuring departments;

1. Access Admin Panel: Log in as an admin to osTicket.
2. Navigate to Departments: Go to "Manage" and select "Departments."
3. Create a New Department: Click "Add New Department."
4. Define Department Details: Enter the department name, email address, and description.
5. Set Department Settings: Configure settings like ticket assignment, permissions, and notifications.
6. Save the Department: Click "Add Department" to save.
7. Modify Existing Departments: Edit or delete existing departments as needed.
8. Assign Agents to Departments: Assign agents to departments to manage tickets within their assigned departments.

Configuring teams;

1. Access Admin Panel: Log in as an admin to osTicket.
2. Navigate to Teams: Go to "Manage" and select "Teams."
3. Create a New Team: Click "Add New Team."
4. Define Team Details: Enter the team name and description.
5. Set Team Members: Assign agents to the team by selecting them from the list.
6. Configure Team Settings: Specify settings such as permissions, email settings, and notifications for the team.
7. Save the Team: Click "Add Team" to save the team configuration.
8. Modify Existing Teams: Edit or delete existing teams as needed.

Configuring agents;

1. Access Admin Panel: Log in as an admin to osTicket.
2. Navigate to Agents: Go to "Manage" and select "Agents."
3. Create a New Agent: Click "Add New Agent."
4. Enter Agent Details: Fill in the agent's information, including name, email address, and role.
5. Assign Departments and Teams: Assign the agent to one or more departments and teams based on their responsibilities.
6. Set Agent Permissions: Define permissions for the agent, specifying what actions they can perform within osTicket.
7. Configure Email Settings: Set up email settings for the agent, including the email address they will use for communication with customers.
8. Save the Agent: Click "Add Agent" to save the agent configuration.
9. Modify Existing Agents: Edit or delete existing agent profiles as needed.

Configure and manage SLAs;

1. Access Admin Panel: Log in as an admin to osTicket.
2. Navigate to SLAs: Go to "Manage" and select "SLAs."
3. Create a New SLA: Click "Add New SLA."
4. Define SLA Parameters: Specify SLA details such as name, description, response time, resolution time, escalation rules, and priority levels.
5. Set Business Hours: Define business hours during which SLA timers are active.
6. Assign SLA to Departments: Choose which departments will be governed by the SLA.
7. Configure SLA Rules: Customize SLA rules, including holidays, weekends, and exceptions.
8. Save the SLA: Click "Add SLA" to save the SLA configuration.
9. Modify Existing SLAs: Edit or delete existing SLAs as needed.
