# ☁️ KB-007 | Microsoft 365 License Assignment

> Microsoft 365 • Exchange Online • Microsoft Teams

## Problem

The user (**empleado1.cloud@estudiantehelpdesk.onmicrosoft.com**) reported that Microsoft 365 services were unavailable.

Although the user could successfully authenticate, services such as **Outlook** and **Microsoft Teams** could not be accessed.

---

## Root Cause

The user account existed in Microsoft Entra ID and authentication was successful.

However, no Microsoft 365 license had been assigned to the account.

---

## Resolution

Locate the affected user in the Microsoft 365 Admin Center.

Verify the assigned licenses.

Assign the following license:

```text
Microsoft 365 Business Premium
```

Wait for the license assignment to complete.

Verify access to Microsoft 365 services.

---

## Result

✅ Microsoft 365 services restored.

The user successfully:

- Accessed Outlook
- Accessed Microsoft Teams
- Sent emails
- Received emails

---

## Evidence

### Microsoft 365 Admin Center

![](01-admin-center-users.png)

### User without license

![](02-user-without-license.png)

### Outlook access error

![](03-outlook-error.png)

### Microsoft Teams access error

![](04-teams-error.png)

### User overview

![](05-user-overview.png)

### License verification

![](06-license-verification.png)

### Assign Microsoft 365 Business Premium

![](07-assign-license.png)

### Outlook working

![](08-outlook-working.png)

### Microsoft Teams working

![](09-teams-working.png)

### Email sent successfully

![](10-email-sent.png)

### Email received successfully

![](11-email-received.png)

---

## Skills

- Microsoft 365 Administration
- License Management
- Exchange Online
- Microsoft Teams
- Microsoft Entra ID
- User Administration
- Helpdesk Troubleshooting