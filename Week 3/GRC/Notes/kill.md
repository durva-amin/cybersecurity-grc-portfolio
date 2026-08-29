## Definition

**`kill`** is a Linux command used to **send a signal to a process**, usually to request that it stop or terminate.

**Simple Definition:**

> `kill` is used to **control or terminate a process using its PID**.

---

## Basic Syntax

kill PID

Example:

kill 2450

This sends the default termination signal to the process with PID **2450**.

---

## What is a Signal?

A **signal** is a message sent to a process telling it to perform a particular action.

Some important signals are:

|Signal|Number|Purpose|
|---|---|---|
|**SIGTERM**|15|Requests the process to terminate gracefully|
|**SIGKILL**|9|Immediately terminates the process|
|**SIGSTOP**|19|Stops the process|

By default:

kill PID

sends **SIGTERM (15)**.

---

## SIGTERM vs SIGKILL

### SIGTERM

kill 2450

It politely asks the process to terminate.

The process can clean up resources before exiting.

### SIGKILL

kill -9 2450

Immediately terminates the process.

The process **cannot catch or ignore SIGKILL**.

Because it does not allow normal cleanup, it should generally be used only when necessary.

---

## Finding the PID

Before using `kill`, you usually need the process's PID.

You can use:

ps aux

or:

top