# Configuring Roles & Role-Based Access in Azure AD
## 📌 Project Overview
This project provides a step-by-step guide on how to assign user roles and configure role-based access in Azure Active Directory (Azure AD). It also explains how to create, manage, and delete administrative units to enhance security and streamline user management.

This project was completed as part of the Microsoft Cybersecurity Certification to demonstrate expertise in access control within enterprise environments.

## 🔹 Key Features
✅ Assign and update roles in Azure AD
✅ Configure Privileged Identity Management (PIM) for secure access control
✅ Create and manage Administrative Units for better role delegation
✅ Perform bulk user operations using PowerShell scripts
✅ Remove users, groups, or devices efficiently

## 📖 Step-by-Step Guide
1️⃣ Assign and Adjust Roles in Azure AD
In Azure AD, role assignment is crucial to ensure proper access control.

### 🔹 Select the Role to Assign
Sign in to the Azure portal with the Privileged Role Administrator role.
Navigate to Azure Active Directory > Users.
Search for and select the user who will receive the role assignment.
Click on Assigned roles > Add assignments.
Choose the appropriate role and click Next.
### 🔹 Adjust Role Settings
Eligible: Requires activation each time the user needs permissions.
Active: Provides continuous access without activation.
If using PIM, you may require MFA, business justification, or approval.
Click Assign to complete the process.
### 🔹 Update or Remove Roles
To update a role, navigate to Assigned roles, select Update, modify settings, and save.
To remove a role, go to Assigned roles, select Remove, and confirm the action.
## 2️⃣ Create and Manage Administrative Units
Administrative units allow organizations to delegate user and group management.

### 🔹 Create an Administrative Unit
Sign in to Azure Portal.
Go to Azure Active Directory > Administrative Units.
Click Add, enter a name and description.
(Optional) Restrict management access to tenant-level administrators.
Assign roles and users if needed.
Click Create to finalize.
### 🔹 Delete an Administrative Unit
Go to Azure Active Directory > Administrative Units.
Select the unit to be deleted.
Remove all assigned roles.
Check the box next to the unit and click Delete.
Confirm the deletion.
## 3️⃣ Remove Users, Groups, or Devices from an Administrative Unit
When users, groups, or devices no longer need access, remove them:

### 🔹 Remove a Single User, Group, or Device
Go to Azure Active Directory > Users, Groups, or Devices.
Select the item to remove.
Click Administrative Units and uncheck the unit(s).
Click Remove from Administrative Unit.

## 📷 Screenshots
Here are some screenshots demonstrating the process:

### Assigning a Role
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/RBAC_02.png">

### Updating a Role
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/RBAC_05.png">

### Removing a Role
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/RBAC_06.png">

### Creating an Administrative Unit
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/RBAC_07.png">
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/RBAC_08.png">
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/RBAC_09.png">

### Deleting an Administrative Unit
<img src="https://github.com/harshitgarg-cs/Azure-Active-Directory/blob/main/images/RBAC_11.png">
