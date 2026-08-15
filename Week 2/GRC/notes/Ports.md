## Definition

A **port** is a **logical communication endpoint** used by networked applications and services to identify where network traffic should be delivered on a device.

**Simple Definition:**

> A port helps a device know **which application or service should receive network traffic**.

---

## Why Are Ports Used?

A single computer can run many network services at the same time.

For example:

- Web server → Port **80**
- HTTPS → Port **443**
- SSH → Port **22**

The IP address identifies the **device**, while the port identifies the **service/application endpoint**.

**IP Address → Which device?**  
**Port → Which service?**

---

## Port Number Range

TCP and UDP ports range from:

**0 to 65,535**

They are commonly divided into:

- **0–1023 → Well-known ports**
- **1024–49,151 → Registered ports**
- **49,152–65,535 → Dynamic/Private ports**

---

## Common Ports

|Port|Protocol/Service|
|---|---|
|**20/21**|FTP|
|**22**|SSH|
|**25**|SMTP|
|**53**|DNS|
|**80**|HTTP|
|**110**|POP3|
|**143**|IMAP|
|**443**|HTTPS|

You will study these protocols separately, so for now focus on understanding **what a port does**.

---

## TCP and UDP Ports

Ports can be used with both:

- **TCP**
- **UDP**

For example, a service can listen on a particular TCP port, while another service may use the same numerical port with UDP.