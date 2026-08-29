## Definition

**Linux logs** are records of events and activities that happen on a Linux system.

**Simple Definition:**

> Linux logs help you understand **what happened on a Linux system**.

---

## What Information Can Logs Contain?

Logs can record things such as:

- User login attempts
- System events
- Application activity
- Errors and warnings
- Service activity
- Authentication events
- Security-related events

---

## Where Are Linux Logs Stored?

Many Linux logs are commonly stored in:

/var/log

Some systems use traditional log files, while others also use the **systemd journal**.

---

## Common Log Files

### `/var/log/auth.log`

On Debian/Ubuntu systems, this commonly contains **authentication and authorization-related events**.

For example:

- Successful logins
- Failed login attempts
- `sudo` activity

### `/var/log/syslog`

On Debian/Ubuntu systems, this commonly contains various **system and service messages**.

### `/var/log/kern.log`

May contain messages related to the **Linux kernel**.

### `/var/log/dmesg`

Can contain information related to **kernel and hardware events**, though the exact logging setup can vary by distribution.

---

## Linux Logs in Cybersecurity

Logs are very important for security investigation.

For example, if an attacker tries to log in repeatedly with incorrect credentials, an analyst can examine authentication logs for evidence of those failed attempts.

**Event → Log recorded → Analyst investigates**

---

## Useful Commands

### View a log file

cat /var/log/auth.log

### View the latest lines

tail /var/log/auth.log

### Follow new log entries

tail -f /var/log/auth.log

### Search for a word

grep "Failed" /var/log/auth.log

### View systemd journal

journalctl

These commands may require appropriate permissions depending on the system.