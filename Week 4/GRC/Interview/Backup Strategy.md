# Interview Questions

### Q1. What is a Backup Strategy?

**Answer:**  
A backup strategy defines how an organization creates, stores, protects, tests, and restores copies of important data.

### Q2. What are the main types of backup?

**Answer:**  
Full, Incremental, and Differential backups.

### Q3. What is the 3-2-1 Backup Rule?

**Answer:**  
Maintain three copies of data, on two different storage types/media, with one copy stored off-site.

### Q4. What is RPO?

**Answer:**  
Recovery Point Objective defines the organization's acceptable amount of data loss measured in time.

### Q5. What is RTO?

**Answer:**  
Recovery Time Objective defines the target time for restoring a system or service after disruption.

### Q6. Why should backups be tested?

**Answer:**  
To verify that the backup is usable and that data and systems can actually be restored when required.

### Q7. How do backups help against ransomware?

**Answer:**  
Protected and tested backups can allow an organization to restore clean data after ransomware damages or encrypts production data.

### Q8. Should backup copies be protected?

**Answer:**  
Yes. Backups should have appropriate access controls, encryption where required, monitoring, and protection against deletion or modification.

---

# Scenario-Based Question

### Q. During an audit, a company tells you, “We take backups every day, so our data is safe.” What else would you check?

**Answer:**  
I would check:

- Where backups are stored
- Whether backup access is restricted
- Whether off-site/offline/immutable copies exist where appropriate
- Whether backups are encrypted where required
- Whether restoration is regularly tested
- Whether backup frequency meets the RPO
- Whether recovery can meet the RTO

Simply creating backups does not guarantee successful recovery.