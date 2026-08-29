# Quick Revision

- **Hashing = Data → Hash/Digest**
- Designed to be **one-way**
- Produces fixed-length output
- Same input + same algorithm → Same hash
- Small input change → Very different hash
- Used for:
    - Integrity
    - Password verification
    - File verification
- **SHA-256 / SHA-3 → Cryptographic hashes**
- **Argon2 / bcrypt / scrypt → Password hashing**
- **MD5 / SHA-1 → Legacy/insecure for collision-sensitive uses**

### ⭐ Easy Trick

> **Encryption = Lock & Unlock 🔐🔓**  
> **Hashing = Fingerprint 🧬**

**You can unlock encrypted data with the right key.**

**You don't "unhash" a hash.**