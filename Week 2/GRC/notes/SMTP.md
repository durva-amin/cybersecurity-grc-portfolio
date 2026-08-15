## Definition

**SMTP (Simple Mail Transfer Protocol)** is a network protocol used to **send email messages from email clients to mail servers and between mail servers**.

**Simple Definition:**

> SMTP is mainly used for **sending emails**.

---

## What Does SMTP Do?

SMTP is responsible for **outgoing email delivery**.

For example:

**You → SMTP Server → Recipient's Mail Server**

SMTP helps transfer the email toward the recipient's mail server.

---

## How SMTP Works

Suppose you send an email to someone:

1. You write the email in your email application.
2. Your email client sends the message to your mail server using SMTP.
3. The sending mail server communicates with the recipient's mail server using SMTP.
4. The recipient's mail server stores the email.
5. The recipient retrieves it using a mail retrieval protocol such as **POP3 or IMAP**.

---

## SMTP Ports

Common SMTP ports include:

|Port|Use|
|---|---|
|**25**|Traditional SMTP server-to-server mail transfer|
|**587**|Commonly used for authenticated email submission|
|**465**|Commonly used for SMTP over TLS/implicit TLS|

For interviews, remember:

> **SMTP → 25 / 587 / 465**

---

## SMTP vs POP3 vs IMAP

| Protocol | Main Purpose                      |
| -------- | --------------------------------- |
| **SMTP** | Sending email                     |
| **POP3** | Retrieving/downloading email      |
| **IMAP** | Accessing and synchronizing email |