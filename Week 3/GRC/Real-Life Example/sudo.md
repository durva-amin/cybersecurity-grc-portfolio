Suppose a normal user wants to install a software package.

Without sufficient privileges:

apt install package

The operation may be denied.

With appropriate authorization:

sudo apt install package

The command can execute with elevated privileges.

---

## Why sudo is Important in Cybersecurity

`sudo` supports **least privilege** because users can operate normally with their regular permissions and use elevated privileges only when necessary.

Administrators can also control **which users are allowed to run which commands** through the sudo configuration.