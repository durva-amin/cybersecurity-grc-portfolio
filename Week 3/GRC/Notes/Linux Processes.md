## Definition

A **Linux process** is a **running instance of a program**.

**Simple Definition:**

> A process is a program that is currently **running and using system resources**.

---

## Example

When you open a text editor, the program starts running and becomes a **process**.

Program → Running → Process

A single application can also create multiple processes.

---

## Process ID (PID)

Every Linux process has a unique **Process ID (PID)**.

Example:

Process: Firefox

PID: 2450

The PID helps the operating system and administrators identify a specific process.

---

## Parent and Child Processes

Linux processes can create other processes.

- **Parent process** → Creates another process.
- **Child process** → Process created by the parent.

This creates a process hierarchy.

---

## Process States

A process can have different states, such as:

- **Running** → Currently executing.
- **Sleeping** → Waiting for something.
- **Stopped** → Temporarily stopped.
- **Zombie** → Finished execution but still has an entry waiting for its parent to collect its status.

---

## Why Processes Are Important in Cybersecurity

Security analysts may examine processes to identify:

- Unknown programs.
- Suspicious processes.
- Unusual resource usage.
- Unexpected processes running with high privileges.
- Processes associated with potentially malicious activity.

However, an unfamiliar process is **not automatically malware**. It needs further investigation.

---

## Useful Commands

### `ps`

Shows information about running processes.

ps

### `top`

Shows processes and resource usage in real time.

top

### `kill`

Sends a signal to a process, commonly to request that it terminate.

kill PID

You will study these commands separately.