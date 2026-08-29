# Quick Revision

- **Digital Signature = Cryptographic signature**
- Uses asymmetric cryptography
- Provides:
    - **Authentication**
    - **Integrity**
    - **Non-repudiation support**
- 🔐 **Private Key → SIGN**
- 🔓 **Public Key → VERIFY**
- Does **not** provide confidentiality by itself.
- Uses hashing as part of the signing process.

### ⭐ Easy Trick

Remember:

> **Private → SIGN ✍️**  
> **Public → VERIFY ✅**

And:

> **Encryption → Keep it SECRET 🔐**  
> **Hashing → Check CHANGE 🧬**  
> **Digital Signature → Check WHO + CHANGE ✍️✅**