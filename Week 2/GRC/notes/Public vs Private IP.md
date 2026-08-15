## Definition

An **IP address** can be classified as **Public** or **Private** depending on where it is used.

**Simple Definition:**

> **Public IP** → Used to communicate over the Internet.  
> **Private IP** → Used inside a local network.

---

## 1. Public IP

A **Public IP address** is an IP address that is used to identify a network or device **on the Internet**.

### Example

`8.8.8.8`

### Key Points

- Used for Internet communication.
- Generally assigned by an **Internet Service Provider (ISP)**.
- Must be globally unique when used on the public Internet.
- Can be visible to Internet services.

### Real-Life Example

Your home router has a public IP address assigned by your ISP. Websites use this public-facing address to communicate back with your home network.

---

## 2. Private IP

A **Private IP address** is used to identify devices **inside a local network**, such as a home, office, or college network.

### Common Private IPv4 Ranges

|Range|Example|
|---|---|
|`10.0.0.0 – 10.255.255.255`|`10.0.0.5`|
|`172.16.0.0 – 172.31.255.255`|`172.16.5.10`|
|`192.168.0.0 – 192.168.255.255`|`192.168.1.10`|

### Key Points

- Used inside local networks.
- Not directly routable on the public Internet.
- Multiple separate networks can use the same private IP addresses.
- A router commonly uses **NAT** to allow devices with private IPs to access the Internet.

---

# Public vs Private IP

| Public IP               | Private IP                          |
| ----------------------- | ----------------------------------- |
| Used on the Internet    | Used inside a local network         |
| Globally unique         | Can be reused in different networks |
| Usually assigned by ISP | Usually assigned by router/DHCP     |
| Example: `8.8.8.8`      | Example: `192.168.1.10`             |
| Internet-routable       | Not Internet-routable               |