A program has stopped responding.

You find its PID:

PID = 2450

You can first try:

kill 2450

If the process does not terminate and you have determined that forceful termination is appropriate:

kill -9 2450

---

## Why `kill` is Important in Cybersecurity

During an investigation, an analyst may identify a **confirmed malicious process** that needs to be stopped.

However, analysts should **verify the process before terminating it**, because stopping a legitimate system process could cause service disruption.