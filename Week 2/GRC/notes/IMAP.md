## Definition

**IMAP (Internet Message Access Protocol)** is an email protocol used to **access and manage emails stored on a mail server**.

**Simple Definition:**

> IMAP lets you **access and synchronize your emails across multiple devices** while keeping the emails on the server.

---

## How IMAP Works

When you check your email using IMAP:

1. Your email client connects to the mail server.
2. It authenticates you.
3. It displays emails stored on the server.
4. Changes such as read/unread status, folders, and deletions are synchronized with the server.

**Simple flow:**

**Mail Server ↔ IMAP ↔ Your Device**

---

## IMAP Ports

- **Port 143** → Standard IMAP
- **Port 993** → IMAP over TLS

For secure email access, **993** is commonly used.

---

## IMAP vs POP3

|IMAP|POP3|
|---|---|
|Emails remain primarily on the server|Mainly downloads emails to the device|
|Synchronizes across devices|Less suited for multi-device synchronization|
|Changes sync with the server|Changes are more local depending on configuration|
|Good for phones, laptops, tablets|Useful when local email storage is desired|