# Interview Questions

### Q1. What is chmod?

**Answer:**  
`chmod` is a Linux command used to change the permissions of files and directories.

### Q2. What does chmod stand for?

**Answer:**  
**Change mode.**

### Q3. What does `chmod 755 file` mean?

**Answer:**

- Owner → `rwx`
- Group → `r-x`
- Others → `r-x`

So `755` means **`rwxr-xr-x`**.

### Q4. What does `chmod u+x file` do?

**Answer:**  
It adds **execute permission to the file owner**.

### Q5. What does `chmod o-w file` do?

**Answer:**  
It removes **write permission from others**.

### Q6. Why is chmod important for security?

**Answer:**  
It helps control access to files and prevents unauthorized users from reading, modifying, or executing them.

---

# Scenario-Based Question

### Q. A script can be read but cannot be executed by its owner. What command can be used to give the owner execute permission?

**Answer:**

chmod u+x script.sh