## Definition

**Encryption** is the process of converting readable data (**plaintext**) into an unreadable form (**ciphertext**) using an encryption algorithm and a key.

Only someone with the appropriate key should be able to convert it back into readable information.

**Simple Definition:**

> Encryption = **Convert readable data into unreadable data to protect it.** 🔐

---

# Important Terms

|Term|Meaning|
|---|---|
|**Plaintext**|Original readable data|
|**Ciphertext**|Encrypted unreadable data|
|**Encryption**|Plaintext → Ciphertext|
|**Decryption**|Ciphertext → Plaintext|
|**Key**|Value used by the cryptographic algorithm|

Example:

```
Plaintext
   ↓
Encryption + Key
   ↓
Ciphertext
   ↓
Decryption + Appropriate Key
   ↓
Plaintext
```

---

# Why Is Encryption Used?

Encryption helps:

- Protect confidential information
- Prevent unauthorized people from reading data
- Protect sensitive business information
- Protect personal information
- Reduce the impact of data theft
- Support regulatory/security requirements

Encryption primarily supports **Confidentiality** in the CIA Triad.

---

# Data at Rest vs Data in Transit

### 1. Data at Rest

Data that is **stored somewhere**.

Examples:

- Laptop hard drive
- Database
- USB drive
- Server storage

Encryption can protect stored data if the device or storage is stolen or accessed improperly.

### 2. Data in Transit

Data that is **moving between systems**.

Example:

```
Your Laptop → Internet → Website Server
```

Protocols such as **TLS** can encrypt communications while data travels across a network.