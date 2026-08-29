# Interview Questions

### Q1. What is a Digital Signature?

**Answer:**  
A digital signature is a cryptographic mechanism used to verify the authenticity and integrity of digital information.

### Q2. Which key is used to create a Digital Signature?

**Answer:**  
The signer's **Private Key**.

### Q3. Which key verifies a Digital Signature?

**Answer:**  
The corresponding **Public Key**.

### Q4. What security properties does a Digital Signature provide?

**Answer:**  
Primarily **authentication, integrity, and support for non-repudiation**.

### Q5. Does a Digital Signature provide confidentiality?

**Answer:**  
Not by itself. Encryption is used when confidentiality is required.

### Q6. What happens if a signed document is modified?

**Answer:**  
The signature verification should fail because the document's data no longer matches what was originally signed.

### Q7. What is the difference between Digital Signature and Encryption?

**Answer:**  
Encryption primarily protects **confidentiality**, while digital signatures help provide **authenticity and integrity**.

### Q8. Is a Digital Signature the same as a scanned handwritten signature?

**Answer:**  
No. A digital signature uses cryptographic techniques, while an image of a handwritten signature does not provide the same cryptographic verification.

---

# Scenario-Based Question

### Q. A company receives an important document and wants to verify that it came from the expected sender and wasn't modified after signing. What can be used?

**Answer:**  
A **Digital Signature**.

The recipient can verify the signature using the sender's corresponding **public key**.

A successful verification provides evidence of the document's **authenticity and integrity**.