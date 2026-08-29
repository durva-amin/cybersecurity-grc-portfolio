## Definition

**Windows Services** are background programs that **run automatically or on demand to perform specific system or application functions in Windows**.

**Simple Definition:**

> A Windows Service is a background process that performs a specific task without requiring constant user interaction.

---

## What Do Windows Services Do?

Services can handle tasks such as:

- Networking
- Windows updates
- Security functions
- Printing
- System maintenance
- Application-related functions

Many services can start automatically when Windows starts.

---

## Service States

A Windows service can commonly be:

- **Running** → The service is currently active.
- **Stopped** → The service is not currently running.
- **Paused** → The service is temporarily paused, where supported.

---

## Startup Types

Services can have different startup configurations, such as:

### Automatic

The service starts automatically when Windows starts.

### Automatic (Delayed Start)

The service starts automatically, but after some other startup activity.

### Manual

The service starts when it is needed or when another component starts it.

### Disabled

The service cannot be started normally until its startup configuration is changed.

---

## How to View Windows Services

You can open the Services management console by:

**Windows Search → Services**

or:

**Win + R → `services.msc` → Enter**

You can then view service names, status, startup type, and other information.

---

## Why Are Services Important in Cybersecurity?

Security analysts may check services when investigating a suspicious system.

For example, an attacker may try to establish persistence by creating or modifying a service.

However, **an unknown service is not automatically malicious**. It should be investigated before taking action.