## Definition

**`sudo`** is a Linux command that allows an **authorized user to run a command with elevated privileges**, usually as the root user.

**Simple Definition:**

> `sudo` allows a permitted user to **perform administrative tasks without logging in directly as root**.

---

## What Does sudo Mean?

**sudo = superuser do**

It is commonly used when a normal user needs to perform an administrative operation.

Example:

sudo apt update

Here, the command is executed with elevated privileges.

---

## Why is sudo Used?

`sudo` can be used for tasks such as:

- Installing software.
- Updating the system.
- Changing file ownership.
- Managing users and groups.
- Starting or stopping services.
- Modifying protected system files.

---

## How sudo Works

When you run:

sudo command

Linux checks whether your user is **authorized to use sudo**.

If authorized:

**User → sudo → Elevated privileges → Command executes**

If not authorized, the command is denied.