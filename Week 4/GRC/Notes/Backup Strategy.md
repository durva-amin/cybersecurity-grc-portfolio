## Definition

A **Backup Strategy** is a planned approach for **creating, storing, protecting, and testing copies of important data** so it can be recovered after data loss, corruption, system failure, or a security incident.

**Simple Definition:**

> Backup Strategy = **How, when, and where we back up data so we can recover it when needed.** 💾

---

# Why Is a Backup Strategy Important?

Backups help organizations recover from:

- Ransomware
- Accidental deletion
- Hardware failure
- Data corruption
- System failure
- Disasters
- Some cyberattacks

> **Backup is not enough — the organization must also be able to restore the data successfully.**

---

# Types of Backup

## 1. Full Backup

Copies **all selected data**.

Example:

```
100 GB data → Backup all 100 GB
```

**Advantages:**

- Simple restoration

**Disadvantages:**

- Requires more storage
- Takes more time

---

## 2. Incremental Backup

Copies only data **changed since the most recent backup**.

Example:

```
Monday → Full Backup
Tuesday → Changes since Monday
Wednesday → Changes since Tuesday
```

**Advantages:**

- Faster backup
- Uses less storage

**Disadvantage:**

- Restoration can require multiple backup sets.

---

## 3. Differential Backup

Copies data **changed since the last full backup**.

Example:

```
Monday → Full
Tuesday → Changes since Monday
Wednesday → All changes since Monday
Thursday → All changes since Monday
```

It generally grows larger each day until another full backup occurs.

---

# Full vs Incremental vs Differential

|Type|What is backed up?|Backup Speed|Storage|
|---|---|---|---|
|**Full**|Everything selected|Slower|Higher|
|**Incremental**|Changes since latest backup|Faster|Lower|
|**Differential**|Changes since last full backup|Between the two|Between the two|

---

# 3-2-1 Backup Rule

Very useful for interviews.

Maintain:

> **3 → Copies of your data**  
> **2 → Different types of storage/media**  
> **1 → Copy off-site**

For stronger ransomware resilience, organizations may also use **offline or immutable backups** where appropriate.

---

# Backup Frequency

How often backups are taken depends on:

- Importance of the data
- How frequently the data changes
- Business requirements
- Recovery requirements
- Risk level

Examples:

- Daily
- Weekly
- Hourly for highly critical systems

There is no single frequency suitable for every organization.

---

# RPO and RTO

Very important GRC concepts.

### RPO — Recovery Point Objective

> **How much data loss can the organization tolerate?**

Example:

**RPO = 4 hours**

The organization aims to recover to a point no more than approximately 4 hours before the disruption.

### RTO — Recovery Time Objective

> **How quickly should the system be restored?**

Example:

**RTO = 2 hours**

The organization aims to restore the service within approximately 2 hours.

### Easy Trick

> **RPO → DATA ⏪**  
> **RTO → TIME ⏱️**

---

# Backup Testing

Backups should be **tested regularly**.

Why?

Because having a backup doesn't guarantee that:

- It isn't corrupted
- The required data was actually backed up
- The restoration procedure works
- The organization can meet its recovery objectives

> **Successful backup ≠ Successful recovery**