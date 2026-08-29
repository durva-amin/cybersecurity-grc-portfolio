# Interview Questions

### Q1. What is the `kill` command?

**Answer:**  
`kill` sends a signal to a Linux process, commonly to request that it terminate.

### Q2. What does `kill` use to identify a process?

**Answer:**  
It uses the process's **PID (Process ID)**.

### Q3. What signal does `kill PID` normally send?

**Answer:**  
**SIGTERM (15)**.

### Q4. What is the difference between SIGTERM and SIGKILL?

**Answer:**  
**SIGTERM** politely requests that a process terminate and allows it to perform cleanup. **SIGKILL** immediately terminates the process and cannot be caught or ignored.

### Q5. What does `kill -9 PID` do?

**Answer:**  
It sends **SIGKILL**, which immediately terminates the process.

### Q6. Should `kill -9` always be used?

**Answer:**  
No. It should generally be used only when a normal termination request does not work or when immediate termination is necessary.

---

# Scenario-Based Question

### Q. A security analyst identifies a confirmed malicious process running on a Linux server. What command can be used to send a termination signal to the process?

**Answer:**

kill PID

The analyst should first verify the PID and understand the impact before terminating the process.