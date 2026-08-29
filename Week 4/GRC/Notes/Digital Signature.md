## Definition

A **Digital Signature** is a cryptographic mechanism used to verify the **authenticity and integrity of digital data** and to provide evidence that the holder of a particular private key signed it.

It uses **asymmetric/public-key cryptography**.

**Simple Definition:**

> Digital Signature = A **cryptographic signature** that helps prove **who signed the data and whether it was changed**. ✍️🔐

---

# What Does a Digital Signature Provide?

Remember these three:

### 1. Authentication 👤

Helps verify the identity associated with the signing key.

### 2. Integrity 📄

Helps verify that the signed data has not been modified after signing.

### 3. Non-repudiation ✍️

Can provide evidence that makes it harder for the signer to deny having signed, depending on how the keys and identities are managed.

> A digital signature does **not primarily provide confidentiality**.

---

# How Does a Digital Signature Work?

At a beginner level:

### Signing

```
Document
   ↓
Hashing
   ↓
Hash/Digest
   ↓
Sign using Sender's Private Key
   ↓
Digital Signature
```

### Verification

The receiver uses the sender's **Public Key** to verify the signature and checks it against the document.

If verification succeeds:

> **Signature valid + Document unchanged ✅**

If the document has been modified:

> **Verification fails ❌**

---

# Which Keys Are Used?

This is very important for interviews:

> 🔐 **Private Key → Sign**

> 🔓 **Public Key → Verify**

### Easy Trick

**Private → Sign ✍️**

**Public → Verify ✅**