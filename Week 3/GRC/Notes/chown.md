## Definition

**`chown`** is a Linux command used to **change the owner and/or group ownership of a file or directory**.

**Simple Definition:**

> `chown` controls **who owns a file or directory**.

---

## What Does chown Mean?

**chown = change ownership**

It is different from `chmod`:

- **`chmod` → Changes permissions**
- **`chown` → Changes ownership**

---

## Basic Syntax

chown user filename

Example:

sudo chown durva file.txt

This changes the **owner** of `file.txt` to `durva`.

---

## Change Owner and Group

You can change both at the same time:

sudo chown durva:developers file.txt

This means:

- Owner → `durva`
- Group → `developers`

---

## Change Only Group

You can use:

sudo chown :developers file.txt

This changes the group ownership to `developers` while keeping the current owner.

---

## Recursive Ownership

The `-R` option applies the ownership change to a directory and its contents:

sudo chown -R durva:developers project/

This changes the owner and group for the directory and everything inside it.

⚠️ **Be careful with `-R`**, especially on system directories, because incorrect ownership can break applications or system functions.

---

## How to Check Ownership

Use:

ls -l

Example:

-rw-r--r--  durva  developers  file.txt

Here:

- `durva` → Owner
- `developers` → Group