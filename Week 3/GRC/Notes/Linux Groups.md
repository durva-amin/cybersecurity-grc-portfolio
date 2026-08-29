## Definition

A **Linux group** is a collection of user accounts used to **manage permissions and access to files, directories, and other resources**.

**Simple Definition:**

> A group lets you give the **same access permissions to multiple users**.

---

## Why Are Groups Used?

Imagine a company has:

- Alice → IT team
- Bob → IT team
- Carol → HR team

Instead of giving permissions separately to Alice and Bob, you can create an **IT group** and assign the required permissions to that group.

**Users → Group → Permissions**

---

## Primary and Secondary Groups

### Primary Group

Every Linux user has a **primary group**.

It is commonly associated with files the user creates.

### Secondary Groups

A user can belong to **additional groups**.

This allows the user to gain access to resources associated with those groups.

---

## Example

Suppose you have:

IT Group

├── Alice

├── Bob

└── David

A directory can be assigned to the **IT group**.

Then appropriate permissions can be given to the group instead of configuring every user individually.

---

## Important Commands

### `groups`

Shows the groups a user belongs to.

groups

### `id`

Shows the user's UID, GID, and group memberships.

id

### `groupadd`

Creates a new group.

sudo groupadd developers

### `usermod -aG`

Adds a user to a supplementary group.

sudo usermod -aG developers durva

**Important:** `-aG` is commonly used so you add the new group without removing the user's existing supplementary group memberships.

### `groupdel`

Deletes a group.

sudo groupdel developers

---

## Why Groups Are Important in Cybersecurity

Groups make **access control** easier to manage.

For example:

Finance Group → Access to Finance files

HR Group → Access to HR files

IT Group → Access to IT resources

This helps organizations follow the **principle of least privilege** by giving users access based on their role.