## Definition

**Asymmetric Encryption** is a cryptographic method that uses a **pair of mathematically related keys: a Public Key and a Private Key**.

For confidentiality, data encrypted with the recipient's **public key** can be decrypted with the corresponding **private key**.

**Simple Definition:**

> Asymmetric Encryption = **Two keys — Public Key + Private Key.** 🔑🔑

---

# The Two Keys

### 🔓 Public Key

- Can be shared with others.
- Used in public-key operations such as encrypting data for the key owner.

### 🔐 Private Key

- Must be kept secret.
- Used to decrypt data encrypted for the owner.
- Also has an important role in **digital signatures**.

> **Public Key → Share**  
> **Private Key → Secret**

---

# How Does It Work?

For confidential communication to Bob:

```
Alice
  ↓
Bob's Public Key
  ↓
Encrypt Message
  ↓
Ciphertext
  ↓
Bob's Private Key
  ↓
Decrypt
  ↓
Original Message
```

Only the holder of Bob's corresponding private key should be able to decrypt that message.

---

# Common Asymmetric Algorithms

Important examples:

- **RSA**
- **ECC** — Elliptic Curve Cryptography

You mainly need to remember:

> **RSA and ECC are examples of public-key/asymmetric cryptography.**

---

# Advantages

- Helps solve the shared-secret key distribution problem
- Enables secure key establishment/exchange mechanisms
- Supports digital signatures
- Public key can be distributed openly

---

# Disadvantages

- Generally slower than symmetric encryption
- More computationally expensive
- Not normally used alone to encrypt very large amounts of data

Because of this, real systems often use **symmetric and asymmetric cryptography together**.