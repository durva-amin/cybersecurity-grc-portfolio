# Interview Questions

### Q1. What is MFA?

**Answer:**  
MFA is an authentication method that requires two or more different types of authentication factors to verify a user's identity.

### Q2. What are the common authentication factors?

**Answer:**

- Something you **know**
- Something you **have**
- Something you **are**

### Q3. Give an example of MFA.

**Answer:**  
A password combined with an authenticator app or hardware security key.

### Q4. Why is MFA important?

**Answer:**  
MFA provides an additional layer of security and can help prevent unauthorized access even when a password is compromised.

### Q5. Is password + PIN MFA?

**Answer:**  
Not normally. Both are **knowledge factors**, so they do not provide two different factor types.

### Q6. What is the difference between 2FA and MFA?

**Answer:**  
2FA uses two different authentication factors, while MFA means two or more different factors.

### Q7. Can MFA completely prevent account compromise?

**Answer:**  
No. MFA significantly improves security, but some methods can still be targeted through phishing, social engineering, session theft, or MFA-fatigue attacks.

### Q8. Which is generally stronger: SMS code or an authenticator/security key?

**Answer:**  
SMS can improve security over password-only authentication, but authenticator apps and especially phishing-resistant methods such as hardware security keys/passkeys can provide stronger protection.

---

# Scenario-Based Question

### Q. An employee's password is stolen through phishing, but the attacker cannot log in because the account also requires a security key. Which control helped protect the account?

**Answer:**  
**Multi-Factor Authentication (MFA).**

The attacker had the password (**something you know**) but did not have the required security key (**something you have**).