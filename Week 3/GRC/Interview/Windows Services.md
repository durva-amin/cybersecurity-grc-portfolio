# Interview Questions

### Q1. What is a Windows Service?

**Answer:**  
A Windows Service is a background program that performs a specific system or application function, often without direct user interaction.

### Q2. What are common service startup types?

**Answer:**  
Common startup types include **Automatic, Automatic (Delayed Start), Manual, and Disabled**.

### Q3. What is the difference between Automatic and Manual?

**Answer:**  
**Automatic** services start automatically according to their configuration, usually during Windows startup. **Manual** services start when they are requested or triggered.

### Q4. How can you view Windows Services?

**Answer:**  
You can open **Services (`services.msc`)** from Windows.

### Q5. Why are Windows Services relevant to cybersecurity?

**Answer:**  
Services can be important during security investigations because malicious software can sometimes use services for **persistence or background execution**.

### Q6. Should you disable an unknown Windows Service immediately?

**Answer:**  
No. First determine what the service is, which executable it uses, who installed it, and whether it is legitimate. Disabling an important system service can cause problems.

---

# Scenario-Based Question

### Q. During an investigation, an analyst finds a newly created Windows service that starts automatically and launches an unfamiliar executable. What should the analyst do?

**Answer:**  
The analyst should **investigate the service and executable** to determine whether they are legitimate or malicious, rather than immediately assuming it is malware.