# Real-Life Example

A company sends an important digitally signed contract.

The sender signs it using their **private key**.

The recipient verifies the signature using the corresponding **public key**.

If someone modifies the signed document afterward, signature verification should fail.

---

# Digital Signature vs Encryption

|Digital Signature|Encryption|
|---|---|
|Authenticity & integrity|Confidentiality|
|Private key used to sign|Recipient's public key may be used to encrypt|
|Public key used to verify|Recipient's private key used to decrypt|
|Proves/checks origin & modification|Protects data from being read|

---

# Digital Signature vs Electronic Signature

They are not necessarily the same.

**Electronic Signature** is a broad term for electronic ways of indicating agreement or signing.

Examples could include:

- Typed name
- Drawn signature
- Clicking an agreement button

A **Digital Signature** specifically uses **cryptographic techniques** to provide integrity and authenticity properties.