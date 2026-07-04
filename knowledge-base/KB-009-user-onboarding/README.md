# 👤 KB-009 | User Onboarding

> Windows Server 2022 • Active Directory • Microsoft 365

## Request

The Human Resources department requested the onboarding of a new employee joining the IT Support team.

The request included:

- Corporate user account
- Domain access
- Security groups
- Microsoft 365 services
- Microsoft Teams
- SharePoint
- Exchange Online
- Shared resources

---

## Tasks Performed

### Active Directory

- Created the domain user account
- Configured the initial password
- Added the user to the `GG_Usuarios` security group

### Microsoft Entra ID

- Created the cloud user account

### Microsoft 365

Assigned the following license:

```text
Microsoft 365 Business Premium
```

### Microsoft Teams

Added the user to:

```text
Soporte IT
```

### SharePoint

Granted access to:

```text
Intranet Helpdesk
```

### Network

Verified DHCP configuration.

```powershell
ipconfig
```

### Validation

Verified access to:

- Outlook
- Exchange Online
- Microsoft Teams
- SharePoint
- Shared resources

---

## Result

✅ New employee successfully onboarded.

The user was able to:

- Sign in to the domain
- Receive network configuration
- Access Outlook
- Send and receive emails
- Access Microsoft Teams
- Join the IT Support team
- Access the SharePoint site
- Open corporate documentation

---

## Evidence

### Create Active Directory user

![](01-create-ad-user.png)

### Configure initial password

![](02-configure-password.png)

### Add user to security group

![](03-add-to-gg_usuarios.png)

### Verify group membership

![](04-group-membership.png)

### Create Microsoft Entra ID user

![](05-create-entra-user.png)

### Assign Microsoft 365 license

![](06-assign-license.png)

### Add user to Microsoft Teams

![](07-add-to-teams.png)

### Grant SharePoint access

![](08-sharepoint-membership.png)

### Verify network configuration

![](09-ipconfig.png)

### Outlook access

![](10-outlook-access.png)

### Send email

![](11-send-email.png)

### Receive email

![](12-receive-email.png)

### Microsoft Teams access

![](13-teams-access.png)

### SharePoint access

![](14-sharepoint-access.png)

### Open technical documentation

![](15-open-documentation.png)

---

## Admin Tools

- Active Directory Users and Computers
- Microsoft Entra Admin Center
- Microsoft 365 Admin Center
- Microsoft Teams Admin Center
- SharePoint Online

---

## Commands Used

```powershell
ipconfig
```

---

## Skills

- Active Directory
- Microsoft Entra ID
- Microsoft 365 Administration
- Exchange Online
- Microsoft Teams
- SharePoint Online
- Security Groups
- User Provisioning
- Helpdesk Operations