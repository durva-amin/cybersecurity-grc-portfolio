## Real-Life Example

Suppose a company wants to protect an important server.

It uses:

- 🔐 Locked server room
- 🔥 Firewall
- 🔑 MFA
- 🛡️ Endpoint protection
- 🔒 Encryption
- 👤 Least Privilege
- 🔍 Security monitoring

If an attacker gets past one layer, other layers still provide protection.

This is **Defense in Depth**.

---

## Defense in Depth vs Single Control

### ❌ Single Layer

```
Internet → Firewall → Server
```

If the firewall is bypassed, the server may have little additional protection.

### ✅ Defense in Depth

```
Internet
   ↓
Firewall
   ↓
MFA / Access Control
   ↓
Endpoint Protection
   ↓
Encryption
   ↓
Monitoring
   ↓
Sensitive Data
```

Multiple controls work together.