## Definition

**NAT (Network Address Translation)** is a technique used by a router or firewall to **translate IP addresses between different networks**, commonly between private IP addresses and a public IP address.

**Simple Definition:**

> NAT allows devices using **private IP addresses** to communicate with the Internet by translating their addresses.

---

## Why is NAT Used?

NAT is mainly used to:

- Allow multiple devices with private IP addresses to share a public IPv4 address.
- Translate private and public IP addresses.
- Help conserve limited IPv4 addresses.
- Keep private internal addresses from being directly exposed to the public Internet.

---

## How Does NAT Work?

Suppose your laptop has:

**Private IP:** `192.168.1.10`

When it accesses the Internet:

**Laptop → Router/NAT → Internet**

The router translates the private source IP into a public IP address.

When the response comes back, the router uses its NAT information to send the response to the correct internal device.

## Common Types of NAT

### 1. Static NAT

One private IP is permanently mapped to one public IP.

**Private IP ↔ Public IP**

### 2. Dynamic NAT

Private IP addresses are mapped to public IP addresses from a pool.

### 3. PAT

**Port Address Translation (PAT)** allows many private devices to share **one public IPv4 address** by using different port numbers.

PAT is commonly used in home networks.