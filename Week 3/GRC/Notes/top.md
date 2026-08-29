## Definition

**`top`** is a Linux command used to **monitor running processes and system resource usage in real time**.

**Simple Definition:**

> `top` shows **which processes are running and how much CPU and memory they are using**.

---

## What Does `top` Show?

`top` can display:

- Process ID (**PID**)
- CPU usage
- Memory usage
- Process owner
- Process status
- Running processes
- System load

The display updates continuously while `top` is running.

---

## Basic Command

top

This opens the real-time process monitoring screen.

To exit:

q

---

## Example

Suppose your Linux system becomes very slow.

You run:

top

You notice:

PID    USER    %CPU    %MEM    COMMAND

2450   durva   95.0    10.2    unknown_process

The process is using a very high amount of CPU, so you can investigate it further.

---

## `top` vs `ps`

|`ps`|`top`|
|---|---|
|Shows a snapshot|Continuously updates|
|Good for viewing process details|Good for real-time monitoring|
|Command ends after displaying output|Keeps running until you exit|
|`ps aux`|`top`|

---

## Why `top` is Important in Cybersecurity

`top` can help analysts identify:

- Processes using unusually high CPU.
- Processes consuming large amounts of memory.
- Unexpected processes.
- Resource-intensive activity.
- Potentially suspicious processes that require investigation.

High resource usage **does not automatically mean malware**. It needs further investigation.