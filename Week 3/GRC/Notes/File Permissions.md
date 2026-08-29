## Definition

**Linux file permissions** control **who can read, modify, or execute a file or directory**.

**Simple Definition:**

> File permissions decide **who can access a file and what they are allowed to do with it**.

---

## Three Types of Permissions

Linux has three basic permissions:

|Permission|Symbol|Meaning|
|---|---|---|
|**Read**|`r`|View/read the file|
|**Write**|`w`|Modify the file|
|**Execute**|`x`|Run the file/program|

---

## Three Permission Categories

Permissions are assigned to:

### 1. User / Owner (`u`)

The user who owns the file.

### 2. Group (`g`)

Users belonging to the file's group.

### 3. Others (`o`)

Everyone else.

So Linux permissions follow:

**User → Group → Others**

---

## Example

Run:

ls -l

You might see:

-rwxr-xr--

Break it down:

- | rwx | r-x | r--

    u     g     o

### User/Owner: `rwx`

Can:

- Read ✅
- Write ✅
- Execute ✅

### Group: `r-x`

Can:

- Read ✅
- Write ❌
- Execute ✅

### Others: `r--`

Can:

- Read ✅
- Write ❌
- Execute ❌

---

## Permission Numbers

Linux permissions can also be represented using numbers:

|Permission|Number|
|---|---|
|Read (`r`)|**4**|
|Write (`w`)|**2**|
|Execute (`x`)|**1**|

Add the numbers together:

**`rwx` = 4 + 2 + 1 = 7**

**`r-x` = 4 + 0 + 1 = 5**

**`r--` = 4 + 0 + 0 = 4**

So:

rwxr-xr--

becomes:

**754**

---

## Important Commands

### `ls -l`

View file permissions.

ls -l

### `chmod`

Change permissions.

Example:

chmod 755 script.sh

### `chown`

Change file ownership.

chown user file.txt

You will study `chmod` and `chown` separately.

---

## Why File Permissions Matter in Cybersecurity

File permissions help prevent **unauthorized access and modification**.

For example, a confidential company file should not be writable by every user.

Good permissions can help ensure:

> **Only authorized users can access or modify sensitive files.**