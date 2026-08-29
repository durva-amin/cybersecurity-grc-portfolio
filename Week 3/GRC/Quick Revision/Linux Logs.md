# Quick Revision

- **Linux logs = Records of system activity**
- Common location: **`/var/log`**
- `auth.log` → Authentication-related events on Ubuntu/Debian
- `syslog` → Various system/service messages on systems that use it
- `kern.log` → Kernel-related messages where configured
- `journalctl` → View systemd journal
- `tail -f` → Monitor new log entries
- `grep` → Search log entries
- Logs are important for **troubleshooting and security investigations**.

### ⭐ Easy Trick

> **Logs = System's history book 📖**

**Something happens → System records it → Analyst checks the log → Understands what happened**