# post-install-config

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

- Configure Roles (for grouping permissions)
- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Configure Teams
- Configure Agents (workers) and Configure Users (customers)
- Configure SLA and Configure Help Topics (For when users create a ticket)

<h2>Configuration Steps</h2>

<p>
</p>
<img width="896" alt="Screenshot 2024-12-22 at 1 16 33 PM" src="https://github.com/user-attachments/assets/4921d09e-13bb-4fba-ab0b-639effa69ab7" />

<p>
Set Up Roles, Departments, and Teams:
Define roles for permission grouping (e.g., Supreme Admin).
Create departments to organize ticket visibility (e.g., SysAdmins, Networking).
Set up teams by pulling agents from different departments (e.g., Online Banking Team).
</p>
<br />

<p>
<img width="674" alt="Screenshot 2024-12-22 at 1 56 43 PM" src="https://github.com/user-attachments/assets/b70d730d-b9ff-46fd-b0ec-1a04f821583e" />

</p>
<p>
Add Agents, Users, and Ticket Rules:
Add agents (workers) and assign them to departments (e.g., Jane: SysAdmins, John: Support).
Add users (customers) to the system (e.g., Karen, Ken).
Configure user settings for ticket creation (e.g., require login to create tickets).
</p>
<br />

<p>
<img width="942" alt="Screenshot 2024-12-22 at 1 49 22 PM" src="https://github.com/user-attachments/assets/c1f360be-eb8f-44c4-8e88-0c3fcd66aa1d" />

</p>
<p>
Set SLAs and Help Topics:
Define SLA policies with grace periods and schedules (e.g., Sev-A: 1 hour, 24/7).
Create help topics for user ticket categorization (e.g., Password Reset, Equipment Request).
</p>
<br />
