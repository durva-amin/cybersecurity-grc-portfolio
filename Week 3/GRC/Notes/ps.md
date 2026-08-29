## Definition

**`ps` (process status)** is a Linux command used to **view information about running processes**.

**Simple Definition:**

> `ps` helps you see **which processes are running and their details**.

---

## Basic Command

ps

This shows processes associated with the **current terminal/session**.

Example:

PID   TTY      TIME     CMD

1234  pts/0    00:00:00 bash

1456  pts/0    00:00:01 python

- **PID** → Process ID
- **TTY** → Terminal associated with the process
- **TIME** → CPU time used
- **CMD** → Command/program running

---

## Important `ps` Commands

### `ps aux`

Shows a detailed list of processes from all users.

ps aux

Useful when investigating what is running across the system.

### `ps -ef`

Shows processes in a detailed format, including the **parent process ID (PPID)**.

ps -ef

### Find a Specific Process

You can combine `ps` with `grep`:

ps aux | grep firefox

This searches the process list for entries containing `firefox`.

---

## Why `ps` is Important in Cybersecurity

`ps` can help an analyst:

- Find suspicious processes.
- Check which users started processes.
- Identify processes running with high privileges.
- Examine parent-child process relationships.
- Investigate unusual programs running on a system.