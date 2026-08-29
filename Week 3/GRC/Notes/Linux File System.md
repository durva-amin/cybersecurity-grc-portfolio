## Definition

The **Linux File System** is the structure Linux uses to **organize and manage files and directories** on a computer.

**Simple Definition:**

> The Linux file system organizes everything into a **hierarchical directory structure starting from `/` (root).**

---

## Root Directory `/`

The Linux file system starts at:

/

This is called the **root directory**.

Unlike Windows, Linux does not normally organize the entire system using drive letters such as `C:` or `D:`.

---

## Important Linux Directories

You don't need to memorize every directory. For cybersecurity and interviews, know these:

|Directory|Purpose|
|---|---|
|`/`|Root of the entire file system|
|`/home`|Home directories of normal users|
|`/root`|Home directory of the root user|
|`/etc`|System and application configuration files|
|`/var`|Variable data such as logs|
|`/tmp`|Temporary files|
|`/bin`|Essential user commands|
|`/usr`|User programs and related files|
|`/dev`|Device files|
|`/proc`|Information about running processes and the kernel|
|`/boot`|Files needed for system booting|

---

## Example Structure

A simplified Linux file system may look like:

/

├── home

│   └── durva

├── etc

├── var

│   └── log

├── tmp

├── usr

├── dev

├── proc

└── boot

---

## Important for Cybersecurity

Some directories are especially useful during security investigations:

### `/var/log`

Contains many system and application logs.

An analyst can examine logs to investigate events such as authentication activity or system problems.

### `/etc`

Contains many configuration files.

An analyst may examine configuration files when investigating system settings.

### `/home`

Contains users' personal directories and files.

### `/proc`

Provides information about the **running system and processes** through a virtual filesystem.

---

## Useful Commands

### `pwd`

Shows your current directory.

pwd

### `ls`

Lists files and directories.

ls

### `cd`

Changes the current directory.

cd /etc

### `cd ..`

Moves to the parent directory.

cd ..

### `cd /`

Moves to the root directory.

cd /