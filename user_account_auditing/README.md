# User Account Auditing – Accounts & Permissions

## 🔹 Project Overview
This project focuses on **auditing user accounts and permissions** in a simulated environment.  
The goal was to identify unnecessary accounts, privilege escalations, and potential security risks.

## 🔹 Key Tasks
- Enumerated all existing user accounts.  
- Audited **group memberships** and administrative privileges.  
- Identified inactive, duplicate, or unauthorized accounts.  
- Reviewed file and folder permissions for policy violations.  
- Created an **audit report** with recommendations.  

## 🔹 Tools & Methods Used
- **Linux**: `id`, `groups`, `getent passwd`, `ls -l`, `auditd`.  
- **Windows**: `net user`, Local Users & Groups (lusrmgr.msc), and permission checks.  
- Security principle of **least privilege**.  

## 🔹 Deliverables
- Audit checklist of users and groups.  
- Screenshots of account/permission enumeration.  
- Report with recommendations for remediation.  

## 📄 Files in This Folder
- `README.md` – Project summary.  
- `report.pdf` – Full audit documentation with screenshots and recommendations.
