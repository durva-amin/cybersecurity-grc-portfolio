# Interview Questions

### Q1. What is `chown`?

**Answer:**  
`chown` is a Linux command used to change the owner and/or group ownership of a file or directory.

### Q2. What does chown stand for?

**Answer:**  
**Change ownership.**

### Q3. What is the difference between `chmod` and `chown`?

**Answer:**

> **`chmod` changes permissions, while `chown` changes ownership.**

### Q4. How do you change the owner of a file?

**Answer:**

sudo chown username file.txt

### Q5. How do you change both owner and group?

**Answer:**

sudo chown username:groupname file.txt

### Q6. What does `chown -R` do?

**Answer:**  
It recursively changes ownership of a directory and its contents.

### Q7. Why is file ownership important in cybersecurity?

**Answer:**  
Ownership helps determine which user and group are associated with a file, which works together with permissions to control access.

---

# Scenario-Based Question

### Q. A file is owned by the wrong user, and the administrator wants to assign it to the correct user and group. Which command can they use?

**Answer:**

sudo chown username:groupname file.txt