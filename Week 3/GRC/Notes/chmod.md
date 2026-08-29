## Definition

**`chmod`** is a Linux command used to **change the permissions of files and directories**.

**Simple Definition:**

> `chmod` controls **who can read, write, or execute** a file or directory.

---

## What Does chmod Mean?

**chmod = change mode**

It changes the permission settings of a file or directory.

---

## Basic Syntax

chmod permissions filename

Example:

chmod 755 script.sh

This changes the permissions of `script.sh` to **755**.

---

## Numeric Permissions

Remember:

|Permission|Number|
|---|---|
|Read (`r`)|4|
|Write (`w`)|2|
|Execute (`x`)|1|

### Example: `755`

7 = rwx

5 = r-x

5 = r-x

Therefore:

755 = rwxr-xr-x

Meaning:

- **Owner →** Read + Write + Execute
- **Group →** Read + Execute
- **Others →** Read + Execute

---

## Symbolic Permissions

You can also use letters.

### Add permission

chmod u+x script.sh

Adds **execute permission to the owner**.

### Remove permission

chmod o-w file.txt

Removes **write permission from others**.

### Add group write permission

chmod g+w file.txt

Adds **write permission to the group**.

---

## Permission Categories

|Symbol|Meaning|
|---|---|
|`u`|User/Owner|
|`g`|Group|
|`o`|Others|
|`a`|All|


## Why chmod is Important in Cybersecurity

Incorrect permissions can allow unauthorized users to:

- Read sensitive files.
- Modify important files.
- Execute unauthorized programs.

Using `chmod` correctly helps enforce **least privilege**.