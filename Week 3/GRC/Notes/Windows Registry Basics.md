## Definition

The **Windows Registry** is a hierarchical database in Windows that stores **configuration settings and information used by the operating system, applications, users, and hardware**.

**Simple Definition:**

> The Registry is like a **central database of Windows configuration settings**.

---

## What is Stored in the Registry?

The Registry can contain information about:

- Windows configuration
- Installed applications
- User settings
- Hardware configuration
- System settings
- Application settings
- Startup-related configuration

---

## Registry Structure

The Registry is organized into:

**Keys → Subkeys → Values**

Think of it like folders:

**Key → Subkey → Value**

A **value** contains the actual configuration data.

---

## Important Registry Hives

Some major Registry hives are:

### 1. HKEY_LOCAL_MACHINE (HKLM)

Contains settings related to the **computer/system**, such as hardware and installed software configuration.

### 2. HKEY_CURRENT_USER (HKCU)

Contains settings specific to the **currently logged-in user**.

### 3. HKEY_CLASSES_ROOT (HKCR)

Contains information related to **file associations and registered application classes**.

### 4. HKEY_USERS (HKU)

Contains information for **user profiles loaded on the system**.

### 5. HKEY_CURRENT_CONFIG (HKCC)

Contains information about the **current hardware profile**.

For interviews, remember the names and the basic purpose of **HKLM and HKCU** especially.

---

## How to Open Registry Editor

Press:

**Win + R → `regedit` → Enter**

This opens **Registry Editor**.

⚠️ **Important:** Do not randomly modify Registry entries. Incorrect changes can cause applications or Windows itself to malfunction.

---

## Why is the Registry Important in Cybersecurity?

Security analysts may examine the Registry during investigations because malware can sometimes modify Registry settings to:

- Maintain persistence
- Change system configuration
- Modify application behavior
- Configure startup-related behavior

However, **not every Registry change is malicious**. It must be investigated in context.