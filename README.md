<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket Logo"/>
</p>

# osTicket - Post-Install Configuration

This project demonstrates the **post-installation configuration of osTicket** in a Microsoft Azure lab environment.

The objective was to configure roles, departments, teams, agents, users, SLA policies, and help topics to simulate a real-world Help Desk environment.

## Environments and Technologies Used

- Microsoft Azure Virtual Machine
- Windows 10
- Remote Desktop (RDP)
- Internet Information Services (IIS)
- osTicket

## Post-Install Configuration Objectives

- Configure Agent and Admin panels
- Configure Roles and permissions
- Configure Departments and Teams
- Create Help Desk Agents and Users
- Configure SLA policies
- Configure Help Topics
- Configure user ticket registration settings

# Configuration Steps

## 1. Access the osTicket Portals

Admin / Agent Portal:

`http://localhost/osTicket/scp/login.php`

End User Portal:

`http://localhost/osTicket`

The **Admin Panel** is used to configure the Help Desk environment, while the **Agent Panel** is used by support technicians to manage users and tickets.

<p>
<img width="1105" height="462" alt="image" src="https://github.com/user-attachments/assets/094e21d2-9868-4b24-8ebe-779eda234f51" />
</p>

## 2. Configure Roles

Navigate to:

`Admin Panel → Agents → Roles`

Create the following role:

`Supreme Admin`

Roles define the permissions available to Help Desk agents.

<p>
<img width="1082" height="642" alt="image" src="https://github.com/user-attachments/assets/3fc55c56-cb03-4a11-b2be-b85a5a036ddb" />
</p>

## 3. Configure Departments

Navigate to:

`Admin Panel → Agents → Departments`

Create:

`SysAdmins`

Departments organize agents and control ticket visibility and responsibilities.

<p>
<img width="1085" height="792" alt="image" src="https://github.com/user-attachments/assets/a5fa4f59-e9cd-411c-8954-6fa7b45ca933" />
</p>

## 4. Configure Teams

Navigate to:

`Admin Panel → Agents → Teams`

Create:

`Online Banking`

Teams allow agents from different departments to collaborate on specific types of tickets.

<p>
<img width="1087" height="766" alt="image" src="https://github.com/user-attachments/assets/c5c4b53d-5a90-4d7c-a330-51fe4af538cc" />
</p>

## 5. Configure User Registration

Navigate to:

`Admin Panel → Settings → Users`

Disable **Registration Required** to allow users to create tickets without creating an account first.

<p>
<img width="1075" height="765" alt="image" src="https://github.com/user-attachments/assets/c6ae31c8-4e34-46b6-9ff8-405a443fa533" />
</p>

## 6. Create Help Desk Agents

Navigate to:

`Admin Panel → Agents → Add New`

Create the following agents:

- Jane — SysAdmins Department
- John — Support Department

Agents represent Help Desk technicians responsible for working support tickets.

<p>
<img width="1100" height="647" alt="image" src="https://github.com/user-attachments/assets/e4870ef9-5f7c-49b1-8fff-d72473292854" />
</p>

## 7. Create Users

Navigate to:

`Agent Panel → Users → Add New`

Create the following users:

- Karen
- Ken

Users represent customers or employees who submit Help Desk tickets.

<p>
<img width="741" height="462" alt="image" src="https://github.com/user-attachments/assets/3f16486a-5623-4fe3-bf62-8e1a463cef68" />
</p>

## 8. Configure SLA Policies

Navigate to:

`Admin Panel → Manage → SLA`

Create:

- **Sev-A** — 1 Hour Grace Period — 24/7
- **Sev-B** — 4 Hour Grace Period — 24/7
- **Sev-C** — 8 Hour Grace Period — Business Hours

SLA policies define how quickly tickets should be addressed based on their severity.

<p>
<img width="1086" height="741" alt="image" src="https://github.com/user-attachments/assets/cb56d473-032c-4c23-bf82-cfda2c3a9217" />
</p>

## 9. Configure Help Topics

Navigate to:

`Admin Panel → Manage → Help Topics`

Create the following Help Topics:

- Business Critical Outage
- Personal Computer Issues
- Equipment Request
- Password Reset
- Other

Help Topics allow users to categorize their support requests when creating tickets.

<p>
<img width="1077" height="711" alt="image" src="https://github.com/user-attachments/assets/8600efe7-7464-4782-86c6-b709add71239" />
</p>

# Skills Demonstrated

- Help Desk administration
- User and Agent management
- Role-based access control
- Department and Team configuration
- SLA management
- Ticket categorization
- Help Desk workflow configuration
- Basic IT service management concepts

# Project Outcome

Successfully configured an **osTicket Help Desk environment** with agents, users, departments, teams, SLA policies, permissions, and ticket categories to simulate a real-world IT support environment.
