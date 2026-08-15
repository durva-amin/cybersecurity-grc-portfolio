## Definition

**TLS (Transport Layer Security)** is a security protocol that **protects data exchanged between two systems over a network by providing encryption, authentication, and integrity.**

**Simple Definition:**

> TLS creates a **secure and encrypted connection** between a client and a server.

---

## What Does TLS Provide?

### 1. Encryption

Protects data so unauthorized people cannot easily read it.

### 2. Authentication

Helps verify the identity of the server using digital certificates.

### 3. Integrity

Helps ensure that data is not modified while being transmitted.

---

## How TLS Works

In a simplified way:

1. Client connects to the server.
2. Client and server perform a **TLS handshake**.
3. The server provides its digital certificate.
4. They establish cryptographic keys.
5. A secure encrypted connection is created.
6. Data is exchanged securely.

**Simple flow:**

**Client → TLS Handshake → Server → Secure Connection → Data**

---

## TLS and HTTPS

HTTPS uses TLS to secure HTTP communication.

**HTTP + TLS = HTTPS**

For example:

`https://example.com`

The **HTTPS** connection uses TLS to protect the communication.

---

## TLS vs SSL

|TLS|SSL|
|---|---|
|Modern security protocol|Older protocol|
|More secure|Outdated|
|Used by modern HTTPS|No longer recommended|
|Successor to SSL|Predecessor to TLS|