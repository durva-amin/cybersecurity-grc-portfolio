## Definition

**POP3 (Post Office Protocol version 3)** is an email protocol used to **retrieve emails from a mail server to an email client**.

**Simple Definition:**

> POP3 is mainly used to **download emails from a mail server to your device**.

---

## How POP3 Works

When you check your email using POP3:

1. Your email client connects to the mail server.
2. It authenticates you.
3. It downloads your emails.
4. Depending on the configuration, downloaded emails may be removed from the server or kept there.

**Simple flow:**

**Mail Server → POP3 → Your Device**

---

## POP3 Port

POP3 commonly uses:

**Port 110** → Standard POP3

For secure POP3 using TLS:

**Port 995** → POP3 over TLS/SSL

---

## POP3 vs IMAP

|POP3|IMAP|
|---|---|
|Mainly downloads emails|Keeps emails synchronized with the server|
|Designed for local retrieval|Designed for server-based access|
|Can remove downloaded emails depending on settings|Emails generally remain on the server|
|Less suitable for multiple devices|Better for multiple devices|