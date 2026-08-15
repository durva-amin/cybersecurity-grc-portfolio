## Definition

**FTP (File Transfer Protocol)** is a network protocol used to **transfer files between a client and a server** over a network.

**Simple Definition:**

> FTP is used to **upload and download files** between computers.

---

## What is FTP Used For?

FTP can be used to:

- Upload files to a server.
- Download files from a server.
- Manage files and directories on a remote server.
- Transfer multiple files between systems.

---

## How FTP Works

A client connects to an FTP server and authenticates if required.

**Client → FTP Server → Upload/Download Files**

For example:

**Your Computer → FTP → Web Server**

You can upload website files to the server or download files from it.

---

## FTP Ports

FTP commonly uses:

- **Port 21** → Control connection
- **Port 20** → Traditionally associated with the data connection in **active mode**

FTP can also use different data ports depending on whether **active or passive mode** is used.

---

## Security Problem with FTP

Traditional FTP **does not encrypt usernames, passwords, or transferred data**.

This means sensitive information can potentially be intercepted.

For secure file transfer, alternatives such as **SFTP** or **FTPS** can be used.