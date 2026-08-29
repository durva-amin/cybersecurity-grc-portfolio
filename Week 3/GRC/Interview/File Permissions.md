# Interview Questions

### Q1. What are Linux file permissions?

**Answer:**  
Linux file permissions control who can read, write, or execute a file or directory.

### Q2. What are the three basic permissions?

**Answer:**  
**Read (`r`), Write (`w`), and Execute (`x`).**

### Q3. Who can have permissions on a Linux file?

**Answer:**  
Permissions are defined for the **owner, group, and others**.

### Q4. What does `rwxr-xr--` mean?

**Answer:**

- Owner → `rwx`
- Group → `r-x`
- Others → `r--`

So the owner can read, write, and execute; the group can read and execute; others can only read.

### Q5. What does `755` mean?

**Answer:**

Owner → 7 → rwx

Group → 5 → r-x

Others → 5 → r-x

So:

**755 = `rwxr-xr-x`**

### Q6. What is the purpose of file permissions in cybersecurity?

**Answer:**  
They help prevent unauthorized users from reading, modifying, or executing files.

---

# Scenario-Based Question

### Q. A confidential file should be readable and writable by its owner, readable by members of a specific group, and inaccessible to everyone else. What should an administrator configure?

**Answer:**  
The administrator should configure appropriate **owner, group, and others permissions** so that only authorized users can access the file.