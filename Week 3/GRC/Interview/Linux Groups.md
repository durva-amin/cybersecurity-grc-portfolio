# Interview Questions

### Q1. What is a Linux group?

**Answer:**  
A Linux group is a collection of users used to manage access permissions to files and other resources.

### Q2. Why are groups used?

**Answer:**  
Groups allow administrators to assign permissions to multiple users efficiently instead of managing each user individually.

### Q3. What is the difference between a user and a group?

**Answer:**  
A **user** represents an individual account, while a **group** is a collection of users used to manage shared access permissions.

### Q4. What is a primary group?

**Answer:**  
A primary group is the main group associated with a Linux user and is commonly used as the group ownership for files the user creates.

### Q5. What is a secondary group?

**Answer:**  
A secondary group is an additional group that a user belongs to and can provide additional access to resources.

### Q6. Which command shows a user's groups?

**Answer:**

groups

or:

id

### Q7. How do you add a user to a group?

**Answer:**

sudo usermod -aG groupname username

---

# Scenario-Based Question

### Q. A company has 20 employees in the Finance department. All of them need access to the same Finance folder. What is a better approach than giving permissions to each user individually?

**Answer:**  
Create a **Finance group**, add the employees to it, and assign the appropriate permissions to the group.