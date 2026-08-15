# Interview Questions

### Q1. What is a Subnet Mask?

**Answer:**  
A subnet mask is used to identify the network and host portions of an IP address.

### Q2. Why do we need a Subnet Mask?

**Answer:**  
It helps devices determine whether another IP address belongs to the same network and helps divide networks into smaller subnets.

### Q3. Give an example of a Subnet Mask.

**Answer:**  
`255.255.255.0` is a commonly used subnet mask.

### Q4. What does `/24` mean?

**Answer:**  
`/24` means **24 bits are used for the network portion** of the IPv4 address, leaving 8 bits for hosts.

### Q5. What is the relationship between an IP address and a Subnet Mask?

**Answer:**  
The IP address identifies the device, while the subnet mask helps identify which part of that address represents the network and which part represents the host.

---

# Scenario-Based Question

### Q. Two computers have IP addresses `192.168.1.10` and `192.168.1.20`, both with subnet mask `255.255.255.0`. Are they on the same network?

**Answer:**  
Yes. Both belong to the **`192.168.1.0/24` network**.




