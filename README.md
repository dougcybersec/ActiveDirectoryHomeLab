# ActiveDirectoryHomeLab
Created Active Directory instance for basic practice
Active Directory Lab (Windows Server 2022)
### Overview

This project demonstrates the setup and basic administration of an Active Directory environment using Windows Server 2022. The lab focuses on foundational identity and access management tasks commonly performed in entry-level IT and system administration roles.

The environment was built as a single-domain controller lab for learning and demonstration purposes.

### Objectives
Install and configure Active Directory Domain Services (AD DS)
Promote a Windows Server 2022 machine to a Domain Controller
Create and organize Organizational Units (OUs)
Manage user accounts and security groups
Perform account lifecycle tasks (creation, password reset, and unlocking accounts)

### Environment
Windows Server 2022 (Desktop Experience)
Active Directory Domain Services (AD DS)
DNS Role (installed with AD DS)
Single Domain Controller Lab Environment

### Domain Configuration
Domain Name: corp.local
Server Role: Domain Controller

### Active Directory Structure
Domain: CORP.local

OU Structure:
Company
├── Users        (User accounts)
├── Groups       (Security groups / RBAC)
├── Computers    (Workstations / devices)
└── Admins       (Privileged accounts)
    
### aSecurity Groups Created
GG_HR_Users
GG_IT_Users
GG_HelpDesk
GG_Admins

These groups were used to simulate role-based access control (RBAC) within an organization.

### User Accounts Created
Example users:
jsmith (HR)
mgarcia (IT)
tnguyen (HelpDesk)
ajohnson (IT/Admin test user)

Users were assigned to appropriate security groups based on role.

### Tasks Performed
##### Active Directory Administration
Created Organizational Units (OUs)
Created and managed user accounts
Created and managed security groups
Assigned users to groups
##### Account Management
Reset user passwords
Enabled “User must change password at next logon”
Unlocked locked user accounts

### Key Skills Demonstrated
Active Directory user and group management
Identity and access management (IAM) fundamentals
Windows Server administration basics
Password and account lifecycle management
Introductory PowerShell automation
Basic organizational structure design (OUs and RBAC concepts)

### Notes
This is a self-contained lab environment built for learning and demonstration purposes. No production systems were used.

Future Improvements
Add Group Policy Objects (GPOs)
Add second Windows client machine for domain join testing
Expand PowerShell automation (bulk user updates, reporting)
Implement file share permissions using AD groups
