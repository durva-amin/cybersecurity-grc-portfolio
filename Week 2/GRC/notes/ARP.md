## Definition

**ARP (Address Resolution Protocol)** is a protocol used in **IPv4 networks to find the MAC address associated with a known IP address on the local network.**

**Simple Definition:**

> ARP finds the **MAC address of a device when its IP address is already known.**

---

## Why is ARP Needed?

Devices use **IP addresses** to identify destinations at the network layer, but Ethernet frames on a local network need a **MAC address**.

ARP helps connect these two:

**IP Address → MAC Address**

---

## How Does ARP Work?

Suppose your computer wants to communicate with:

**IP:** `192.168.1.20`

But it does not know the device's MAC address.

1. Your computer sends an **ARP Request** asking:  
    _"Who has 192.168.1.20?"_
2. The device with that IP sends an **ARP Reply** containing its MAC address.
3. Your computer stores the result in its **ARP cache**.
4. It can then send the Ethernet frame to that MAC address.