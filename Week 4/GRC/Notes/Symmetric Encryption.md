## Definition

**Symmetric Encryption** is an encryption method where the **same secret key is used to encrypt and decrypt data**.

**Simple Definition:**

> Symmetric Encryption = **Same key to lock and unlock the data.** 🔑

---

# How Does It Work?

```
Plaintext
   ↓
Encryption + Secret Key
   ↓
Ciphertext
   ↓
Decryption + Same Secret Key
   ↓
Plaintext
```

Example:

**Key = Secret123**

- Sender encrypts data using `Secret123`
- Receiver decrypts it using the **same key**

Therefore, both sides need access to the shared secret key.

---

# Common Symmetric Encryption Algorithms

Important ones to know:

- **AES** — Advanced Encryption Standard
- **DES** — Data Encryption Standard _(old/insecure for modern use)_
- **3DES** — Triple DES _(legacy/deprecated)_

For interviews, remember:

> **AES is a widely used modern symmetric encryption algorithm.**

---

# Advantages

### 1. Fast

Symmetric encryption is generally **fast and efficient**.

### 2. Good for Large Amounts of Data

It is commonly used to encrypt large amounts of information.

### 3. Lower Computational Overhead

It generally requires fewer computational resources than asymmetric encryption.

---

# Disadvantages

The major challenge is **key distribution and management**.

Both parties need the same secret key.

If that key is exposed:

> An unauthorized person who obtains the key may be able to decrypt the protected data.

So the secret key must be securely protected and shared.