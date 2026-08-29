## Definition

**Hashing** is the process of converting data into a **fixed-length output called a hash (or hash value/digest)** using a hash function.

Hashing is designed to be **one-way**, meaning you generally cannot reverse the hash to recover the original data.

**Simple Definition:**

> Hashing = **Data → Unique-looking fixed-length fingerprint** 🧬

---

# How Does Hashing Work?

```
Original Data
     ↓
Hash Function
     ↓
Hash Value / Digest
```

Example:

```
"Hello"
   ↓
SHA-256
   ↓
Fixed-length hash value
```

Even a small change in the input should produce a very different hash.

```
Hello  → Hash A
hello  → Hash B
```

---

# Important Properties of Hashing

### 1. One-Way

A secure cryptographic hash is designed so that it is computationally impractical to recover the original input from the hash.

### 2. Fixed-Length Output

The same hash algorithm always produces the same output length.

For example:

> **SHA-256 → 256-bit hash**

regardless of whether the input is a short word or a large file.

### 3. Same Input → Same Hash

Using the same algorithm:

```
"Durva" → Hash X
"Durva" → Hash X
```

### 4. Small Change → Very Different Hash

Changing even a small part of the input should significantly change the resulting hash.

---

# Why Is Hashing Used?

Hashing is commonly used for:

- Integrity verification
- Password verification/storage systems
- File verification
- Digital signatures
- Detecting data changes

---

# Hashing and Passwords

Systems should not store passwords in plain text.

Instead, secure password-storage systems generally store a **salted password hash** using a suitable password-hashing algorithm.

During login:

```
Entered Password
      ↓
Password Hashing Process
      ↓
Compare with stored verifier
      ↓
Match → Authentication continues
```

---

# Common Hash Algorithms

### Modern/general cryptographic hashes

- **SHA-256**
- **SHA-3**

### Password hashing

Purpose-built algorithms include:

- **Argon2**
- **bcrypt**
- **scrypt**

### Older algorithms

- **MD5** ❌
- **SHA-1** ❌

MD5 and SHA-1 should not be relied upon for modern collision-resistant security uses.

---

# Hashing vs Encryption

Very important interview question:

|Hashing|Encryption|
|---|---|
|Designed to be one-way|Reversible with appropriate key|
|No decryption process|Has encryption & decryption|
|Produces hash/digest|Produces ciphertext|
|Often used for integrity/password verification|Used primarily for confidentiality|

### Easy Difference

> **Encryption → Hide data 🔐**  
> **Hashing → Fingerprint data 🧬**