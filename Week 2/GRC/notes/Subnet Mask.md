## Definition

A **Subnet Mask** is used with an IP address to **identify which part represents the network and which part represents the host/device**.

**Simple Definition:**

> A subnet mask tells us **which part of an IP address is the network and which part is the device.**

---

## Example

IP Address:

`192.168.1.10`

Subnet Mask:

`255.255.255.0`

Here:

- `192.168.1` → **Network part**
- `10` → **Host/device part**

So devices such as:

`192.168.1.10`  
`192.168.1.20`  
`192.168.1.30`

are on the same `192.168.1.0/24` network.

---

## Why is a Subnet Mask Used?

A subnet mask helps to:

- Identify the network portion of an IP address.
- Identify the host portion.
- Determine whether two devices are on the same network.
- Divide a larger network into smaller networks.

---

## Common Subnet Masks

| Subnet Mask     | CIDR  | Common Use           |
| --------------- | ----- | -------------------- |
| `255.0.0.0`     | `/8`  | Large network        |
| `255.255.0.0`   | `/16` | Medium/Large network |
| `255.255.255.0` | `/24` | Common LAN           |