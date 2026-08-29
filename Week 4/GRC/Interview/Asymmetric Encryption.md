# Interview Questions

### Q1. What is Asymmetric Encryption?

**Answer:**  
Asymmetric encryption uses a pair of mathematically related keys: a public key and a private key.

### Q2. What is a Public Key?

**Answer:**  
A public key can be shared with others and can be used to encrypt information for the key owner or verify certain digital signatures.

### Q3. What is a Private Key?

**Answer:**  
A private key must be kept secret and is used for operations such as decrypting data encrypted for the owner and creating digital signatures.

### Q4. Give examples of asymmetric algorithms.

**Answer:**  
**RSA and ECC** are common examples of asymmetric/public-key cryptography.

### Q5. What is the main difference between Symmetric and Asymmetric Encryption?

**Answer:**  
Symmetric encryption uses the **same shared secret key**, while asymmetric encryption uses a **public/private key pair**.

### Q6. Which is faster: Symmetric or Asymmetric Encryption?

**Answer:**  
Symmetric encryption is generally faster.

### Q7. Why isn't Asymmetric Encryption normally used for all data?

**Answer:**  
Because it is computationally more expensive than symmetric encryption. Systems often combine both approaches.

### Q8. Should a Private Key ever be shared publicly?

**Answer:**  
No. The private key must be protected and kept secret.

---

# Scenario-Based Question

### Q. You want people to send confidential information to you without first sharing a secret encryption key with each person. Which key could you provide them?

**Answer:**  
Your **Public Key**.

They can use it to encrypt information for you, and the corresponding **Private Key** is used to decrypt it.