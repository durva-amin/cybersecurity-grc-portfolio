# Interview Questions

### Q1. What is a Linux user?

**Answer:**  
A Linux user is an account that provides an identity and controls access to system resources and actions.

### Q2. What is the root user?

**Answer:**  
Root is the Linux superuser with **UID 0** and extensive administrative privileges.

### Q3. What is UID?

**Answer:**  
UID stands for **User ID**. It is a numerical identifier used by Linux to identify a user account.

### Q4. What is the UID of root?

**Answer:**  
**0**.

### Q5. What is the purpose of a normal user account?

**Answer:**  
It provides controlled access to the system without giving the user unnecessary administrative privileges.

### Q6. Why are separate service users used?

**Answer:**  
Services can run under dedicated accounts with limited permissions, which helps reduce the impact if the service is compromised.

### Q7. Which command shows the current user's identity?

**Answer:**

whoami

### Q8. Which command shows a user's UID and groups?

**Answer:**

id

---

# Scenario-Based Question

### Q. A web server application is compromised. The organization wants to limit what the compromised application can access. What Linux security practice can help?

**Answer:**  
Run the application under a **dedicated user account with only the permissions it needs**. This follows the principle of least privilege and limits the potential impact of a compromise.