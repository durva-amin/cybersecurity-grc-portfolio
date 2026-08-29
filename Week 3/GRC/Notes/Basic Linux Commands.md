## Definition

**Linux commands** are instructions entered in the **terminal** to perform tasks such as navigating directories, managing files, checking system information, and working with processes.

**Simple Definition:**

> Linux commands allow you to **interact with and manage a Linux system using the terminal**.

---

## Important Basic Commands

### 1. `pwd` → Print Working Directory

Shows your current location.

pwd

Example:

/home/durva

---

### 2. `ls` → List

Shows files and directories.

ls

Useful option:

ls -l

Shows detailed information such as permissions and ownership.

---

### 3. `cd` → Change Directory

Moves to another directory.

cd /home

Go to the parent directory:

cd ..

Go to your home directory:

cd ~

---

### 4. `mkdir` → Make Directory

Creates a new directory.

mkdir projects

---

### 5. `touch`

Creates a new empty file.

touch notes.txt

---

### 6. `cat`

Displays the contents of a file.

cat notes.txt

---

### 7. `cp` → Copy

Copies files or directories.

cp notes.txt backup.txt

---

### 8. `mv` → Move / Rename

Moves a file or directory.

mv notes.txt documents/

It can also rename a file:

mv old.txt new.txt

---

### 9. `rm` → Remove

Deletes a file.

rm notes.txt

⚠️ Be careful because deleted files may not go to a recycle bin.

---

### 10. `rmdir`

Removes an **empty directory**.

rmdir projects

---

### 11. `whoami`

Shows the current user.

whoami

---

### 12. `id`

Shows the user's UID, GID, and group memberships.

id

---

### 13. `clear`

Clears the terminal screen.

clear

---

### 14. `man` → Manual

Shows the manual/help page for a command.

man ls

---

### 15. `echo`

Displays text in the terminal.

echo "Hello Linux"

---

### 16. `grep`

Searches for text inside files or command output.

grep "error" log.txt

---

### 17. `find`

Searches for files and directories.

find /home -name "notes.txt"

---

### 18. `history`

Shows previously executed commands.

history

---

### 19. `ps`

Shows running processes.

ps

---

### 20. `top`

Shows running processes and resource usage in real time.

top

---

### 21. `kill`

Sends a signal to a process.

kill PID

---

### 22. `chmod`

Changes file permissions.

chmod 755 script.sh

---

### 23. `chown`

Changes file ownership.

sudo chown user file.txt

---

### 24. `sudo`

Runs an authorized command with elevated privileges.

sudo command

---

## Basic Command Cheat Sheet

|Command|Purpose|
|---|---|
|`pwd`|Show current directory|
|`ls`|List files/directories|
|`cd`|Change directory|
|`mkdir`|Create directory|
|`touch`|Create empty file|
|`cat`|Display file contents|
|`cp`|Copy|
|`mv`|Move/rename|
|`rm`|Delete file|
|`rmdir`|Delete empty directory|
|`whoami`|Show current user|
|`id`|Show user/group information|
|`clear`|Clear terminal|
|`man`|Show command manual|
|`echo`|Display text|
|`grep`|Search text|
|`find`|Find files/directories|
|`history`|Show command history|
|`ps`|View processes|
|`top`|Monitor processes|
|`kill`|Send signal to process|
|`chmod`|Change permissions|
|`chown`|Change ownership|
|`sudo`|Run with elevated privileges|