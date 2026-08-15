# Interview Questions

### Q1. What is NAT?

**Answer:**  
NAT is a technique that translates IP addresses between networks, commonly translating private IP addresses to a public IP address for Internet communication.

### Q2. What does NAT stand for?

**Answer:**  
**Network Address Translation.**

### Q3. Why is NAT commonly used?

**Answer:**  
It allows multiple devices with private IPv4 addresses to share a public IPv4 address and helps conserve IPv4 address space.

### Q4. Can multiple devices share one public IP using NAT?

**Answer:**  
Yes. **PAT** allows multiple devices to share one public IPv4 address by using different port numbers.

### Q5. Does NAT provide security?

**Answer:**  
NAT can reduce direct exposure of internal private addresses, but **NAT itself is not a security control or replacement for a firewall**.

---

# Scenario-Based Question

### Q. A home has 10 devices, each with a private IP address, but the ISP provides only one public IPv4 address. How can all devices access the Internet?

**Answer:**  
The router can use **NAT, typically PAT**, to allow all devices to share the single public IPv4 address.





