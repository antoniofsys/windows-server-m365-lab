# 🔒 KB-003 | User Unable to Access Shared Folder

> Windows Server 2022 • Active Directory • File Server

## Problem

A domain user (**empleado1**) was unable to access the **IT** shared folder.

The user was **not a member of the `GG_Usuarios` security group** required to access the resource.

---

## Root Cause

- Shared permissions ✔️
- NTFS permissions ✔️
- User not assigned to `GG_Usuarios` ❌

---

## Resolution

- Verified Shared Folder permissions
- Verified NTFS permissions
- Checked `GG_Usuarios`
- Added `empleado1` to `GG_Usuarios`
- Executed:

```powershell
gpupdate /force
```

- Verified access

---

## Result

✅ User successfully accessed the shared folder.

---

## Evidence

### 1. Access denied

![](01-access-denied.png)

### 2. Shared Folder permissions

![](02-share-permissions.png)

### 3. NTFS permissions

![](03-ntfs-permissions.png)

### 4. Empty `GG_Usuarios`

![](04-empty-group.png)

### 5. Add user to `GG_Usuarios`

![](05-add-user-to-group.png)

### 6. User group membership

![](06-user-memberof.png)

### 7. Refresh Group Policy

```powershell
gpupdate /force
```

![](07-gpupdate.png)

### 8. Successful access

![](08-successful-access.png)

---

## Skills

- Active Directory
- Security Groups
- NTFS Permissions
- Shared Folder Permissions
- Group Policy
- Windows Server 2022
- Helpdesk Troubleshooting