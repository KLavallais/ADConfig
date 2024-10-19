# Active Directory Configuration Guide
![Active Directory Banner](https://github.com/KLavallais/KLavallais/blob/assets/Microsoft-Active-Directory-Banner_0001.png?raw=true)
---
## Tools/Programs Used:
- **Windows Server 2022**: Operating system used to manage and configure Active Directory.
- **Server Manager**: Used to manage roles, features, and configuration of the Active Directory environment.
- **Active Directory Users and Computers (ADUC)**: MMC snap-in for managing AD objects such as users, groups, and OUs.
- **MMC (Microsoft Management Console)**: Tool used to manage Windows infrastructure, including ADUC.

---

## Skills Demonstrated:
- Creating Organizational Units (OUs) for logical structuring of users.
- Adding and managing user accounts in Active Directory.
- Assigning user objects to specific OUs.
- Verifying and maintaining AD structure using ADUC.
- Organizing administrative user privileges for network management.
- Active Directory domain administration and organizational unit hierarchy setup.

---

## Organizational Units and User Creation Process

### 1. Accessing Server Manager
![Server Manager](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_01.png?raw=true)
*The Server Manager is accessed to manage and organize the Active Directory environment through the Active Directory Users and Computers MMC snap-in.*

### 2. Creating the "_EMPLOYEES" Organizational Unit
![Employees OU_01](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_04.png?raw=true)
![Employees OU_02](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_06.png?raw=true)
*A new Organizational Unit (OU) named “_EMPLOYEES” is created, which groups user accounts or computer accounts, facilitating the management of permissions and policies.*

### 3. Creating the "_ADMINS" Organizational Unit
![Admins OU](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_07.png?raw=true)
*The “_ADMINS” Organizational Unit is established to group user accounts that have administrative privileges over the network.*

### 4. Verifying the Creation of Organizational Units
![OUs Verification](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_08.png?raw=true)
*The successful creation of "_EMPLOYEES" and "_ADMINS" Organizational Units is confirmed under the domain.*

### 5. Adding a New User Account
![New User](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_09.png?raw=true)
*A new user object creation is underway in the “_ADMINS” OU.*

### 6. New User Details Entry
![User Details](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_10.png?raw=true)
*Entering the details of the new user, including names and logon credentials.*

### 7. Completion of New User Setup
![User Setup Completion](https://github.com/KLavallais/KLavallais/blob/assets/ADConfig_11.png?raw=true)
*The newly added user is now listed under the “_ADMINS” OU in the Active Directory Users and Computers interface.*




