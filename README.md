<p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.

## Environments and Technologies Used
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used 
- Windows 10 (21H2)

## Post-Install Configuration Objectives
This tutorial covers the following login URLs for osTicket:
- Admin/Analysts: [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- End-Users: [http://localhost/osTicket](http://localhost/osTicket)

### Topics Covered:
- Agent vs. Admin Panel
- Roles
- Departments
- Teams
- Agents
- Users
- SLAs
- Help Desk Topics

## Configuration Steps

### 1. Roles
Roles allow us to assign permissions to specific agents. There are default roles: 
- All Access
- Expanded Access
- Limited Access
- View Only

To add a new role:
- Navigate to the **Admin Panel** > **Agents** > **Roles**.
- Click **Add New Role** and type the name of the role (e.g., 'Super Admin').
- Assign all permissions to this role and click **Add**.

![Add New Role](https://imgur.com/k9AP5jn.png)

![Role Configuration](https://imgur.com/02r7lNV.png)

### 2. Departments
Departments allow ticket visibility to specific areas within an organization, such as Maintenance or IT Support. To create a new department:
- In the **Admin Panel**, go to **Agents** > **Departments**.
- Click **Add New Department** and enter the department name (e.g., 'Sales').
- Configure additional options as desired.

![Add Department](https://imgur.com/BL1h6Xx.png)

![Department Configuration](https://imgur.com/ziWcbpX.png)

### 3. Teams
Teams allow agents from different departments to collaborate on specific tickets. To create a new team:
- In the **Admin Panel**, navigate to **Agents** > **Teams** > **Add New Team**.
- Name the team (e.g., 'Online Banking').

![Add Team](https://imgur.com/BVKTBl8.png)

### 4. Agents
To add new agents who will handle tickets:
- Go to the **Admin Panel** > **Agents** > **Add New Agent**.
- Enter the agent's name (e.g., 'Timmy Jones').
- Assign a role and department by going to the access tab.
- Set set a password.

![Agent Configuration](https://imgur.com/zCuGT7y.png)

### 5. Users
Users are customers submitting tickets. To create a new user:
- Navigate to the **Admin Panel** > **Users** > **Add User**.
- Enter the user's email address and full name (e.g., 'Bill Harris').

![User Configuration](https://i.imgur.com/DJmEXEB.png)

### 6. SLAs (Service Level Agreements)
SLAs define response and resolution times for tickets based on certain criteria. To configure an SLA:
- Go to the **Admin Panel** > **Manage** > **SLA**.
- Click **Add New SLA Plan**, name it (e.g., 'Sev-A'), set the grace period and schedule, and click **Add Plan**.

![SLA Configuration](https://i.imgur.com/DJmEXEB.png)

### 7. Help Topics
Help Topics categorize help desk ticket issues. To configure:
- Go to **Admin Panel** > **Manage** > **Help Topics**.
- Click **Add New Help Topic**, set the topic name (e.g., 'Password Reset'), and select an appropriate parent topic.



