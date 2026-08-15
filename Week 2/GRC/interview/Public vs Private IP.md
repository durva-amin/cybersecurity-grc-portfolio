# Interview Questions

### Q1. What is a Public IP?

**Answer:**  
A Public IP is an IP address used for communication over the Internet and is globally unique when publicly routed.

### Q2. What is a Private IP?

**Answer:**  
A Private IP is an IP address used inside a local network and is not directly routable on the public Internet.

### Q3. Give examples of Private IP addresses.

**Answer:**  
`10.0.0.5`, `172.16.5.10`, and `192.168.1.10`.

### Q4. Can two devices have the same Private IP?

**Answer:**  
They cannot have the same private IP **within the same network at the same time**, but the same private IP can be used in different separate networks.

### Q5. Can a Private IP directly communicate with the Internet?

**Answer:**  
Not directly. Typically, a router uses **NAT** to translate private addresses into a public address for Internet communication.

---

# Scenario-Based Question

### Q. An office has 50 computers using addresses such as `192.168.1.10` and `192.168.1.11`. Are these Public or Private IP addresses?

**Answer:**  
They are **Private IP addresses** because `192.168.0.0/16` is a private IPv4 address range.






