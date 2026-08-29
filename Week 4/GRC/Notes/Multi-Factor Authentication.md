## Definition

**Multi-Factor Authentication (MFA)** is an authentication method that requires a user to provide **two or more different types of authentication factors** before access is granted.

**Simple Definition:**

> MFA = Prove your identity using **more than one type of proof**.

---

# Authentication Factors

There are three common categories you should remember:

|Factor|Meaning|Example|
|---|---|---|
|**Something you know**|Knowledge|Password, PIN|
|**Something you have**|Possession|Phone, security key, smart card|
|**Something you are**|Inherence|Fingerprint, face|

### Example

To log in:

**Password** → Something you know  
**Authenticator-app approval/code** → Something you have

Two different factors = **MFA**.

---

# How Does MFA Work?

Basic process:

**Enter username → Enter password → Provide second factor → Identity verified → Access granted**

For example:

```
Email
   ↓
Password
   ↓
Authenticator App
   ↓
Access Granted ✅
```

---

## Why Is MFA Important?

MFA helps:

- Prevent unauthorized account access
- Reduce risk from stolen passwords
- Protect sensitive accounts
- Strengthen authentication
- Reduce the impact of phishing/password attacks

If an attacker steals your password, they may still need another factor to access the account.

---

# MFA vs 2FA

### 2FA — Two-Factor Authentication

Requires exactly **two different authentication factors**.

### MFA — Multi-Factor Authentication

Requires **two or more different authentication factors**.

Therefore:

> **2FA is a type of MFA.**

---

## Important Interview Point

Two passwords are **not** true MFA.

For example:

**Password + PIN**

Both are **something you know**.

MFA requires different **factor categories**, not simply multiple credentials.