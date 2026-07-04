# 🖥️ Windows Server + Microsoft 365 Hybrid Lab

> Enterprise Infrastructure Laboratory focused on Windows Server Administration, Microsoft 365 and IT Helpdesk Operations.

---

## 📖 Project Overview

This project documents the design, deployment and administration of a hybrid enterprise infrastructure based on **Windows Server 2022** and **Microsoft 365**.

The laboratory simulates a real corporate environment where users, computers, permissions, shared resources and cloud services are centrally managed.

Throughout the project, enterprise services were deployed, configured and validated following common IT administration and Helpdesk procedures.

The repository includes both the infrastructure documentation and a technical Knowledge Base containing real support scenarios and their corresponding resolutions.

---

## 🎯 Objectives

The main objectives of this project are:

- Deploy a Windows Server domain environment.
- Implement core infrastructure services.
- Integrate Microsoft 365 cloud services.
- Simulate a corporate Helpdesk environment.
- Document real administrative procedures.
- Build a professional technical portfolio.

---

# 🏗️ Infrastructure

## On-Premises Infrastructure

- Windows Server 2022
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- File Server

## Cloud Infrastructure

- Microsoft Entra ID
- Microsoft 365
- Exchange Online
- SharePoint Online
- Microsoft Teams
- Microsoft 365 Groups

## Helpdesk

- Jira Service Management
- Knowledge Base
- Incident Management
- Service Requests

---

# 🌐 Laboratory Architecture

```text
                           Internet
                               │
                               ▼
                     Microsoft 365 Tenant
                               │
      ┌─────────────────────────────────────────┐
      │                                         │
      │        Exchange Online                  │
      │        SharePoint Online                │
      │        Microsoft Teams                  │
      │        Microsoft 365 Groups             │
      │                                         │
      └─────────────────────────────────────────┘
                               │
                    Hybrid Identity Services
                               │
                               ▼
      ┌─────────────────────────────────────────┐
      │         Windows Server 2022             │
      │                                         │
      │  • Active Directory                     │
      │  • DNS                                 │
      │  • DHCP                                │
      │  • Group Policy                        │
      │  • File Server                         │
      └─────────────────────────────────────────┘
                               │
                               ▼
                  Windows 11 Domain Client
```

---

# 🛠️ Technologies

| Infrastructure | Cloud | Collaboration | ITSM |
|---------------|-------|---------------|------|
| Active Directory | Microsoft Entra ID | Microsoft Teams | Jira Service Management |
| DNS | Microsoft 365 | SharePoint Online | Knowledge Base |
| DHCP | Exchange Online | Microsoft 365 Groups | Incident Management |
| Group Policy | Outlook | OneDrive | Service Requests |
| File Server | Microsoft 365 Admin Center | | |

---

# 📂 Repository Structure

```text
windows-server-m365-lab/
│
├── architecture/
│
├── docs/
│
├── screenshots/
│   ├── 01-active-directory/
│   ├── 02-dns/
│   ├── 03-dhcp/
│   ├── 04-gpo/
│   ├── 05-file-server/
│   ├── 06-microsoft-365/
│   ├── 07-exchange-online/
│   ├── 08-sharepoint/
│   ├── 09-microsoft-teams/
│   ├── 10-microsoft-365-groups/
│   └── 11-jira-service-management/
│
├── knowledge-base/
│   ├── KB-001-password-reset/
│   ├── KB-002-account-lockout/
│   ├── KB-003-group-based-shared-folder-access/
│   ├── KB-004-dns-name-resolution/
│   ├── KB-005-dhcp-configuration-failure/
│   ├── KB-006-group-policy-not-applied/
│   ├── KB-007-microsoft365-license-assignment/
│   ├── KB-008-sharepoint-site-access/
│   ├── KB-009-user-onboarding/
│   ├── KB-010-user-department-transfer/
│   ├── KB-011-user-offboarding/
│   ├── KB-012-shared-mailbox-access/
│   └── KB-013-microsoft365-group-membership/
│
└── README.md
```

---

# 📸 Infrastructure Documentation

The repository contains detailed documentation for every deployed service, including:

- Active Directory
- DNS
- DHCP
- Group Policy
- File Server
- Microsoft 365
- Exchange Online
- SharePoint Online
- Microsoft Teams
- Microsoft 365 Groups
- Jira Service Management

Each section contains:

- Service overview
- Configuration details
- Validation steps
- Administrative tools
- Supporting screenshots

---

# 📚 Knowledge Base

The project also includes a complete Helpdesk Knowledge Base documenting real administrative procedures.

Current documented procedures include:

- Password Reset
- Account Unlock
- Shared Folder Permissions
- DNS Troubleshooting
- DHCP Troubleshooting
- Group Policy Troubleshooting
- Microsoft 365 License Assignment
- SharePoint Permissions
- User Onboarding
- Department Transfer
- User Offboarding
- Shared Mailbox Administration
- Microsoft 365 Group Membership

---

# 🎯 Skills Demonstrated

## Windows Server

- Active Directory Administration
- DNS Administration
- DHCP Administration
- Group Policy Management
- File Server Administration
- NTFS Permissions
- Shared Folders

## Microsoft 365

- Microsoft Entra ID
- Exchange Online
- Outlook
- SharePoint Online
- Microsoft Teams
- Microsoft 365 Groups
- License Management

## Helpdesk

- Incident Management
- User Administration
- Identity Management
- Access Management
- Troubleshooting
- Technical Documentation

---

# 🚀 Future Improvements

Future versions of the laboratory may include:

- Windows Server Update Services (WSUS)
- Print Server
- DFS Namespace
- DFS Replication
- Azure AD Connect
- Intune
- PowerShell Automation
- Microsoft Defender for Endpoint
- Azure Virtual Machines
- Monitoring and Logging

---

# 📄 License

This repository was created for educational purposes as part of a personal IT infrastructure and Helpdesk portfolio.

---