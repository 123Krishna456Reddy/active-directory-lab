# Automated User Management with PowerShell
This project demonstrates automated user lifecycle management in Active Directory using PowerShell. It focuses on Identity and Access Management (IAM) concepts such as user provisioning, modification, and deprovisioning.

The automation reduces manual effort, improves consistency, and reflects real-world enterprise user management practices.

## Table of Contents

### Project Goals
- Streamline User Management: Automate repetitive Active Directory user management tasks to improve administrative efficiency.
- Enhance Efficiency: Minimize manual effort and reduce time spent on user account operations through automation.
- Ensure Consistency: Maintain standardized and consistent user account configurations across the organization. 

### Features
- User Creation: Automate the provisioning of new user accounts in Active Directory using PowerShell.
- User Modification: Update and manage user attributes such as title, department, and email efficiently.
- User Deletion: Securely deprovision and remove user accounts from Active Directory.

### Prerequisites
To use these scripts, the following prerequisites are required:

- A system running Windows Server or Windows 10 with Remote Server Administration Tools (RSAT) installed
- Active Directory Module for Windows PowerShell
- Appropriate administrative permissions to perform user management tasks in Active Directory

### Usage Instructions
### Step 1: Import the Active Directory Module
Before executing any scripts, import the Active Directory module to access the required cmdlets.
```powershell
Import-Module ActiveDirectory
```
### Screenshot:

![Screenshot](Screenshot_01.png)



