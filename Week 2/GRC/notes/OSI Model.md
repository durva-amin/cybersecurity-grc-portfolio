## Definition

The **OSI Model (Open Systems Interconnection Model)** is a **7-layer model that explains how data travels from one device to another over a network.**

**Simple Definition:**

> OSI Model is a **7-layer framework used to understand network communication.**

---

## The 7 Layers

|Layer|Name|Simple Meaning|
|---|---|---|
|7|**Application**|Network services used by applications|
|6|**Presentation**|Data format, encryption, compression|
|5|**Session**|Starts, manages, and ends communication sessions|
|4|**Transport**|Reliable data delivery and segmentation|
|3|**Network**|IP addressing and routing|
|2|**Data Link**|MAC addresses and frames|
|1|**Physical**|Cables, signals, and bits|

**Remember from Layer 7 → 1:**

> **A P S T N D P**  
> **All People Seem To Need Data Processing**

---

## Purpose

The OSI Model helps to:

- Understand how networks communicate.
- Troubleshoot network problems.
- Standardize network communication.
- Understand the role of different networking devices and protocols.

---

## How It Works

When you **send data**, it moves down through the layers:

**Application → Presentation → Session → Transport → Network → Data Link → Physical**

When the receiver gets the data, it moves back up:

**Physical → Data Link → Network → Transport → Session → Presentation → Application**