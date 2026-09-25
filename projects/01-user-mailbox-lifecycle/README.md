# Project 1: User & Mailbox Lifecycle (Exchange Online / Entra ID)

## 📌 Scenario
Onboard a new starter, "Jane Doe," by provisioning her user account, assigning the appropriate Microsoft 365 license, and ensuring her Exchange Online mailbox is correctly configured before her start date.

## 🎯 Objective
To demonstrate the end-to-end process of user creation, license-based service provisioning, and verification of mailbox creation using both the graphical admin centers and PowerShell.

## 🛠️ Tools Used
- Microsoft 365 Admin Center
- Microsoft Entra ID (Azure AD)
- Exchange Admin Center (EAC)
- Exchange Online PowerShell (EXO V2 Module)

---

## 🚀 Step-by-Step Implementation

### 1. Create the User Account
- Navigated to `admin.microsoft.com` → **Users** → **Active users** → **Add a user**.
- Entered basic information and set the UPN to `user1@contoso.onmicrosoft.com`.

![Add User](Account creation.webp)

### 2. Assign License
- Assigned an **E5 license** to trigger automatic mailbox provisioning.

![Assign License](./screenshots/02-assign-license.png)

### 3. Verify Mailbox Creation in EAC
- Confirmed the mailbox appears in **Recipients** → **Mailboxes**.

![Verify Mailbox](./screenshots/03-verify-mailbox.png)

### 4. Verify via PowerShell
```powershell
Connect-ExchangeOnline
Get-Mailbox -Identity user1@contoso.onmicrosoft.com
