## Definition

**DHCP (Dynamic Host Configuration Protocol)** is a protocol that **automatically provides devices with network configuration information**, such as an IP address.

**Simple Definition:**

> DHCP automatically gives a device the **IP address and other network settings** it needs to communicate on a network.

---

## What Information Does DHCP Provide?

DHCP can provide:

- **IP Address**
- **Subnet Mask**
- **Default Gateway**
- **DNS Server**

---

## How Does DHCP Work?

DHCP commonly follows the **DORA** process:

### 1. Discover

The device broadcasts a **DHCP Discover** message looking for a DHCP server.

### 2. Offer

The DHCP server sends a **DHCP Offer** with an available IP address and configuration.

### 3. Request

The device sends a **DHCP Request** asking to use the offered configuration.

### 4. Acknowledge

The server sends a **DHCP ACK**, confirming the configuration.

**Remember:**

> **D → O → R → A**  
> **Discover → Offer → Request → Acknowledge**