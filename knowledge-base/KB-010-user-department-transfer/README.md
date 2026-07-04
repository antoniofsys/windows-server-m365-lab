# 🔄 KB-010 | User Department Transfer

> Windows Server 2022 • Microsoft 365 • Microsoft Teams • SharePoint Online

## Request

The Human Resources department informed IT that **empleado3.lab** had been transferred from the **IT Support** department to the **Administration** department.

As part of the department transfer, the user's access to IT resources had to be revoked and new permissions assigned for the Administration department.

---

## Tasks Performed

### Active Directory

Reviewed the user's current group membership.

### SharePoint Online

Granted access to:

```text
Administration
```

Removed access to:

```text
Intranet Helpdesk
```

### Microsoft Teams

Added the user to:

```text
Administration
```

Removed the user from:

```text
Soporte IT
```

### Validation

Verified that the user:

- Lost access to the IT shared folder
- Gained access to the Administration shared folder
- Could only access the Administration Team
- Could access the Administration SharePoint site
- Could no longer access the Intranet Helpdesk site

---

## Result

✅ Department transfer completed successfully.

The user's permissions were updated according to the new job role, ensuring access only to Administration resources.

---

## Evidence

### Review current group membership

![](01-group-membership.png)

### Grant SharePoint Administration access

![](02-sharepoint-add-administration.png)

### Remove Intranet Helpdesk access

![](03-sharepoint-remove-intranet.png)

### Add user to Administration Team

![](04-add-teams-administration.png)

### Remove user from IT Support Team

![](05-remove-teams-support.png)

### Access denied to IT shared folder

![](06-it-folder-access-denied.png)

### Successful access to Administration shared folder

![](07-administration-folder-access.png)

### Microsoft Teams validation

![](08-teams-administration.png)

### SharePoint Administration access

![](09-sharepoint-administration.png)

### Access denied to Intranet Helpdesk

![](10-sharepoint-intranet-denied.png)

---

## Admin Tools

- Active Directory Users and Computers
- Microsoft Teams Admin Center
- SharePoint Online

---

## Skills

- Active Directory
- Microsoft Teams Administration
- SharePoint Online
- Access Management
- User Lifecycle Management
- Least Privilege Principle
- Helpdesk Operations