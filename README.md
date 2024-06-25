<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-installation configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configuring Roles
- Configuring Departments
- Configuring Teams
- Allow Anyone to Create Tickets
- Configuring Agents
- Configuring Users
- Configuring SLA
- Configuring Help Topics

<h2>Configuration Steps</h2>

![image](https://github.com/cedhorton/post-install-config/assets/173581553/ea340523-ba39-4df0-8f0c-e87a6e98c923)

<p>
Configured a new role titled "Supreme Admin" and assigned permissions to the role as an admin in osTicket.
  
 * Admin Panel -> Agents -> Roles
 * Supreme Admin

</p>
<br />

![image](https://github.com/cedhorton/post-install-config/assets/173581553/9a8a4983-86fe-476c-9c6a-d2c10ea090fd)

<p>
Configured a new department titled "System Administrators" as an admin in osTicket.

  * Admin Panel -> Agents -> Departments
  * System Administrators

</p>
<br />

![image](https://github.com/cedhorton/post-install-config/assets/173581553/984cdffd-8525-43ea-963a-f7f4614171ba)

<p>
Configured a new team titled "Level II Support" and assigned a teammember to the newly created team as an admin in osTicket.

  * Admin Panel -> Agents -> Teams
  * Add New Team -> Create Team Name -> Members

</p>
<br />

![image](https://github.com/cedhorton/post-install-config/assets/173581553/9c24abf6-28ea-42ba-9ea7-a628e02a9ddf)

<p>
To allow anyone to create tickets, go to:

  * Admin Panel -> Settings -> User Settings
  * Registration Required: Uncheck "Require registration and login to create tickets"

</p>
<br />

![image](https://github.com/cedhorton/post-install-config/assets/173581553/6cda99a6-a8f7-45dc-896e-c4e1b4570418)

<p>
Configured a new agent named "Jane Doe" in of osTicket as an admin.

  * Admin Panel -> Agents -> Add New
</p>
<br />

![image](https://github.com/cedhorton/post-install-config/assets/173581553/d53c8c35-4595-4c11-b12e-8f673e89517f)

<p>
Configured a user/customer in osTicket named "Karen Karen" as an agent.

  * Agent Panel -> Users -> Add New

</p>
<br />

![image](https://github.com/cedhorton/post-install-config/assets/173581553/7a234be0-6ec1-4b94-9d51-fd73b7c87bab)

<p>
Configured SLA plans titled "SEV-A, SEV-B, SEV-C" as an admin in osTicket

  * Admin Panel -> Manage -> SLA

      - Sev-A (1 hour, 24/7)
      - Sev-B (4 hours, 24/7)
      - Sev-C (8 hours, business hours)

</p>
<br />

![image](https://github.com/cedhorton/post-install-config/assets/173581553/0ec313de-9b07-48fa-9e45-3f2c0c682278)

<p>
Configured help topics as an admin in osTicket.

  * Admin Panel -> Manage -> Help Topics

      - Business Critical Outage
      - Personal Computer Issues
      - Equipment Request
      - Password Reset

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It is important to take care of the patient, to be followed by the patient, but it will happen at such a time that there is a lot of work and pain. For to come to the smallest detail, no one should practice any kind of work unless he derives some benefit from it. Do not be angry with the pain in the reprimand in the pleasure he wants to be a hair from the pain in the hope that there is no breeding.
</p>
<br />
