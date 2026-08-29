## Definition

A **Linux user** is an account that identifies a person or process on a Linux system and determines **what resources and actions it can access**.

**Simple Definition:**

> A Linux user account provides an identity and helps control **who can access what** on the system.

---

## Types of Linux Users

### 1. Root User

The **root user** is the superuser with very high privileges.

- Usually has **UID 0**
- Can perform almost any administrative action.
- Can modify system files and settings.
- Should be used carefully.

### 2. Normal User

A normal user has limited permissions.

For example, they generally cannot modify protected system files without additional privileges.

### 3. System/Service Users

These accounts are commonly created for **services and applications** rather than human users.

They can help limit the privileges of a service.

---

## User ID (UID)

Linux identifies users using a **UID (User ID)**.

For example:

root → UID 0

A username is mainly for humans, while the system uses the UID to identify the account.

---

## Home Directory

Normal users usually have a home directory under:

/home/

For example:

/home/durva

The home directory is where a user's personal files and settings are commonly stored.

---

## Important Commands

### `whoami`

Shows the currently logged-in username.

whoami

### `id`

Shows the current user's UID, GID, and group memberships.

id

### `who`

Shows users currently logged into the system.

who

### `w`

Shows logged-in users and additional information about their current activity.

w

### `passwd`

Used to change a user's password.

passwd

### `sudo`

Allows an authorized user to run a command with elevated privileges.

You will study `sudo` separately.

---

## Why Linux Users Are Important in Cybersecurity

User accounts are important for **access control and accountability**.

For example:

- Normal users should not have unnecessary administrative privileges.
- Services can run under dedicated accounts.
- User activity can be associated with specific accounts.
- Limiting privileges reduces the potential impact of a compromised account.

This follows the **principle of least privilege**.