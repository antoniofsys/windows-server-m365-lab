# 🚪 KB-011 | User Offboarding

> Windows Server 2022 • Active Directory • Microsoft 365

## Request

The Human Resources department informed IT that **empleado3** had left the company.

IT was requested to revoke all access to corporate systems, ensuring that the user could no longer access on-premises resources or Microsoft 365 services.

---

## Tasks Performed

### Active Directory

- Disabled the user account
- Removed the user from the **Administration** security group

### Microsoft Entra ID

- Revoked all active user sessions

### Microsoft 365

Removed the following license:

```text
Microsoft 365 Business Premium
```

### Microsoft Teams

Removed the user from:

```text
Administration
```

### SharePoint Online

Removed the user from:

```text
Administration
```

---

## Result

✅ User offboarding completed successfully.

The user can no longer:

- Sign in to the domain
- Access Outlook
- Access Microsoft Teams
- Access SharePoint Online
- Access corporate resources

---

## Evidence

### Disable Active Directory account

![](01-disable-ad-account.png)

### Remove user from security group

![](02-remove-security-group.png)

### Revoke Microsoft Entra sessions

![](03-revoke-sessions.png)

### Remove Microsoft 365 license

![](04-remove-license.png)

### Remove user from Microsoft Teams

![](05-remove-teams.png)

### Remove user from SharePoint

![](06-remove-sharepoint.png)

### Disabled account verification

![](07-account-disabled.png)

### Outlook access denied

![](08-outlook-access-denied.png)

### SharePoint access denied

![](09-sharepoint-access-denied.png)

### Microsoft Teams access denied

![](10-teams-access-denied.png)

---

## Admin Tools

- Active Directory Users and Computers
- Microsoft Entra Admin Center
- Microsoft 365 Admin Center
- Microsoft Teams Admin Center
- SharePoint Online

---

## Skills

- User Offboarding
- Active Directory
- Microsoft Entra ID
- Microsoft 365 Administration
- Microsoft Teams
- SharePoint Online
- Identity and Access Management (IAM)
- Least Privilege Principle
- Helpdesk Operations