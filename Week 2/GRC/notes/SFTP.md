## Definition

**SFTP (SSH File Transfer Protocol)** is a secure protocol used to **transfer and manage files over an encrypted SSH connection**.

**Simple Definition:**

> SFTP allows users to **securely upload, download, and manage files** on a remote server.

---

## What is SFTP Used For?

SFTP can be used to:

- Upload files securely.
- Download files securely.
- Create and manage directories.
- Rename or delete files, depending on permissions.
- Transfer sensitive files securely.

---

## How SFTP Works

SFTP operates over an **SSH connection**.

**Client → 🔒 SSH/SFTP Connection → Server**

The connection is encrypted, protecting authentication information and transferred data.

---

## SFTP Port

SFTP commonly uses:

**Port 22**

It uses the same default port as SSH because SFTP operates through SSH.

---

## SFTP vs FTP

|SFTP|FTP|
|---|---|
|Secure file transfer|Traditional file transfer|
|Uses SSH|Does not use SSH|
|Encrypted|Not encrypted by default|
|Common port: **22**|Control port: **21**|
|Suitable for sensitive data|Not recommended for sensitive data without additional protection|

---

## Important Point

**SFTP and FTPS are different.**

- **SFTP** → SSH File Transfer Protocol, runs over SSH.
- **FTPS** → FTP secured using TLS.