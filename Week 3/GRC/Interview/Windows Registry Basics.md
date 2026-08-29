# Interview Questions

### Q1. What is the Windows Registry?

**Answer:**  
The Windows Registry is a hierarchical database that stores configuration settings and information used by Windows, applications, users, and hardware.

### Q2. What is Registry Editor?

**Answer:**  
**Registry Editor (`regedit`)** is the Windows tool used to view and modify Registry settings.

### Q3. What are Registry keys and values?

**Answer:**  
**Keys** organize Registry settings, while **values** contain the actual configuration data.

### Q4. What is HKLM?

**Answer:**  
**HKEY_LOCAL_MACHINE (HKLM)** contains configuration information related to the computer and operating system.

### Q5. What is HKCU?

**Answer:**  
**HKEY_CURRENT_USER (HKCU)** contains configuration settings for the currently logged-in user.

### Q6. Why is the Registry relevant to cybersecurity?

**Answer:**  
Attackers and malware can sometimes modify Registry settings for purposes such as **persistence or changing system behavior**, so analysts may examine the Registry during investigations.

### Q7. Should you modify the Registry without knowing what you are doing?

**Answer:**  
No. Incorrect Registry changes can cause applications or Windows to malfunction.

---

# Scenario-Based Question

### Q. During a malware investigation, an analyst suspects that a malicious program is configured to start automatically when a user logs in. What Windows component could the analyst examine?

**Answer:**  
The **Windows Registry** is one component the analyst could examine for startup-related configuration and potential persistence mechanisms.