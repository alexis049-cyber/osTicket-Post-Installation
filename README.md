<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.

Admin/Analyst Login (controller)

End Users osTicket (user)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2 Gen 2)

<h2>Post-Install Configuration Objectives</h2>

- Set up roles and permissions for agents and users.
- Configure ticket visibility and help desk functionality.
- Establish SLAs to define response times for tickets.
- Enhance user experience by organizing help topics.
- Secure the osTicket system with proper permissions and user settings.

<h2>Configuration Steps</h2>

### Step 1: Configure Roles
- Navigate to Admin Panel -> Agents -> Roles.
- Create a role:
  - Supreme Admin

<img width="1190" height="718" alt="image" src="https://github.com/user-attachments/assets/50795030-bf60-4363-9c25-8019ee411ce4" />
<img width="1264" height="614" alt="image" src="https://github.com/user-attachments/assets/79be49b4-8647-42c8-8286-5b0b8b2dc568" />


### Step 2: Configure Departments
- Navigate to Admin Panel -> Agents -> Departments.
- Create departments for ticket visibility:
  - Example: SysAdmins
 
<img width="1156" height="1184" alt="image" src="https://github.com/user-attachments/assets/f8e3d79f-3e26-4cd3-90bb-6090b06724a7" />

 
### Step 3: Configure Teams
- Navigate to Admin Panel -> Agents -> Teams.
- Create a team and pull agents from different departments:
  - Example: Online Banking

<img width="1116" height="902" alt="image" src="https://github.com/user-attachments/assets/47f5f0fa-b007-4867-963e-afb25720f8ce" />


### Step 4: User Settings
- Navigate to Admin Panel -> Settings -> User Settings.
- Configure ticket creation settings:
  - Uncheck: Unregistered users can create tickets.
  - Require registration and login to create tickets.

<img width="1074" height="1004" alt="image" src="https://github.com/user-attachments/assets/9b4e0dd8-5635-4eff-824a-d7eee8bb931e" />


### Step 5: Configure Agents (Workers)
- Navigate to Admin Panel -> Agents -> Add New.
- Add agents:
  - Jane (Dept: SysAdmins)
  - John (Dept: Support)
 
<img width="1000" height="464" alt="image" src="https://github.com/user-attachments/assets/568ec3e0-bf67-4c6a-9038-65b3929c7e79" />
<img width="1118" height="546" alt="image" src="https://github.com/user-attachments/assets/5dd6e566-8203-4612-b7a7-563d958dbdef" />
<img width="1144" height="864" alt="image" src="https://github.com/user-attachments/assets/c065c94d-4ce2-4994-aabd-3a3b4ca7a78c" />
<img width="1068" height="702" alt="image" src="https://github.com/user-attachments/assets/0891b020-dfaa-49cb-8b66-ea9aa8420cb7" />


### Step 6: Configure Users (Customers)
- Navigate to Agent Panel -> Users -> Add New.
- Add users:
  - Karen
  - Ken

 <img width="1336" height="464" alt="image" src="https://github.com/user-attachments/assets/46b6dd61-f3d7-4b75-820c-32a946befe3a" />
<img width="1252" height="804" alt="image" src="https://github.com/user-attachments/assets/abba1b04-f3d3-498f-87d2-61d50b90b501" />


### Step 7: Configure SLA
- Navigate to Admin Panel -> Manage -> SLA.
- Create SLAs:
  - Sev-A (Grace Period: 1 hour, Schedule: 24/7)
  - Sev-B (Grace Period: 4 hours, Schedule: 24/7)
  - Sev-C (Grace Period: 8 hours, Business Hours)

<img width="1314" height="894" alt="image" src="https://github.com/user-attachments/assets/2e657639-0689-4cc0-bf9f-559490773c3d" />
<img width="1260" height="936" alt="image" src="https://github.com/user-attachments/assets/334116f6-126a-4c27-923f-389bd38a05e8" />
<img width="1310" height="986" alt="image" src="https://github.com/user-attachments/assets/feeb4c9a-54f8-41df-8ed3-f721992cabc9" />


### Step 8: Configure Help Topics
- Navigate to Admin Panel -> Manage -> Help Topics.
- Add help topics:
  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Request
  - Password Reset
  - Other
  <img width="1276" height="894" alt="image" src="https://github.com/user-attachments/assets/8cf2b000-bee2-4e42-883b-95bd2b44e071" />
<img width="1230" height="848" alt="image" src="https://github.com/user-attachments/assets/3b56044a-6768-451b-a78c-403684c469df" />


## Conclusion
These steps complete the post-installation setup for osTicket. With these configurations, you can manage your help desk efficiently and ensure a smooth workflow for both agents and users.
