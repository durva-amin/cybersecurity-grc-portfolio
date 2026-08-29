# Interview Questions

### Q1. What is sudo?

**Answer:**  
`sudo` is a Linux command that allows an authorized user to execute a command with elevated privileges, commonly as root.

### Q2. What does sudo stand for?

**Answer:**  
**Superuser do.**

### Q3. Why is sudo used instead of always using the root account?

**Answer:**  
It allows users to perform specific administrative tasks when needed while normally operating with their regular privileges.

### Q4. Is every Linux user allowed to use sudo?

**Answer:**  
No. Only users who are appropriately authorized through the system's sudo configuration can use it.

### Q5. Why is sudo important for security?

**Answer:**  
It supports **least privilege** by allowing administrative privileges to be used when required instead of giving users permanent root-level access.

### Q6. What happens if a user is not authorized to use sudo?

**Answer:**  
The command will be denied, and the user will not receive the requested elevated privileges.

---

# Scenario-Based Question

### Q. A developer needs to restart a service but does not have permission to perform the operation as a normal user. What could an administrator allow them to use?

**Answer:**  
The administrator could configure appropriate **sudo permissions** so the developer can run the required administrative command without giving them unrestricted root access.