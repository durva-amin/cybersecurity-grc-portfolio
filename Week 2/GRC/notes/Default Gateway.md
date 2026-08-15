## Definition

A **Default Gateway** is a **device, usually a router, that forwards traffic from a local network to other networks.**

**Simple Definition:**

> Default Gateway is the **exit point from your local network to another network or the Internet.**

---

## Why is a Default Gateway Needed?

It allows a device to:

- Communicate with devices outside its local network.
- Access the Internet.
- Send traffic to another network.
- Forward packets to the appropriate router.

---

## Example

Suppose your laptop has:

**IP Address:** `192.168.1.10`  
**Subnet Mask:** `255.255.255.0`  
**Default Gateway:** `192.168.1.1`

If your laptop communicates with another device in the same network, it can communicate directly.

But if it wants to access a website on another network, it sends the traffic to:

**`192.168.1.1` → Default Gateway**

The router then forwards the traffic toward the Internet.