# Interview Questions

### Q1. What is Hashing?

**Answer:**  
Hashing converts data into a fixed-length hash value using a hash function and is designed to be one-way.

### Q2. Is Hashing reversible?

**Answer:**  
No. Cryptographic hashing is designed to be one-way and does not have a decryption process.

### Q3. What is a Hash Value?

**Answer:**  
It is the fixed-length output produced by a hash function.

### Q4. Give examples of Hash Algorithms.

**Answer:**  
SHA-256 and SHA-3 are common cryptographic hash algorithms. Argon2, bcrypt, and scrypt are commonly used for password hashing.

### Q5. What is the difference between Encryption and Hashing?

**Answer:**  
Encryption is reversible with the appropriate key and primarily protects confidentiality. Hashing is designed to be one-way and is commonly used for integrity and verification.

### Q6. How does Hashing help with Integrity?

**Answer:**  
You can compare hash values before and after data transfer or storage. If the hashes differ, the data has changed.

### Q7. Why shouldn't passwords be stored in plain text?

**Answer:**  
If the password database is exposed, plain-text passwords would be immediately readable. Secure systems should use appropriate salted password hashing.

### Q8. What is Salt in password hashing?

**Answer:**  
A salt is a unique random value added to each password before hashing. It helps protect against precomputed attacks and prevents identical passwords from having identical stored hashes.

---

# Scenario-Based Question

### Q. During an audit, you discover that an application stores employee passwords in plain text. What would you recommend?

**Answer:**  
I would report it as a serious security weakness and recommend that passwords be stored using an appropriate **salted password-hashing algorithm**, such as Argon2, bcrypt, or scrypt, according to the organization's security requirements.