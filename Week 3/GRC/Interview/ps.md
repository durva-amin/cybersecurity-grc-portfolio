# Interview Questions

### Q1. What is `ps`?

**Answer:**  
`ps` stands for **process status** and is used to display information about running processes.

### Q2. What does `ps aux` do?

**Answer:**  
It displays a detailed list of processes from users on the system, including information such as the user, PID, CPU usage, memory usage, and command.

### Q3. What does PID mean?

**Answer:**  
**PID = Process ID**, a unique identifier assigned to a process.

### Q4. What is PPID?

**Answer:**  
**PPID = Parent Process ID**, which identifies the process that created a particular child process.

### Q5. Is `ps` a real-time process monitor?

**Answer:**  
No. `ps` provides a **snapshot** of processes at the time the command is executed. `top` is commonly used for real-time monitoring.

### Q6. How can `ps` help in cybersecurity?

**Answer:**  
It can help analysts identify suspicious processes, their users, PIDs, and parent-child relationships during an investigation.

---

# Scenario-Based Question

### Q. A security analyst wants to see all processes running on a Linux server and identify which user started each process. Which command could they use?

**Answer:**

ps aux