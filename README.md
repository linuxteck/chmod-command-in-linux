# 12 chmod Commands in Linux (File Permissions Guide) — 2026

> A practical reference for Linux beginners, sysadmins & DevOps engineers.

📖 **Read the full article:** [linuxteck.com/chmod-command-in-linux-with-examples](https://www.linuxteck.com/chmod-command-in-linux-with-examples/)

---

## What This Guide Covers

- What the chmod command does and how file permissions work in Linux
- Numeric mode vs symbolic mode — when to use each
- Numeric permission values table (0–7) explained
- 12 real examples with terminal output
- Setting SUID, SGID, and sticky bit
- Recursive permission changes with -R
- Bulk updates using find + chmod
- Why chmod 777 is dangerous in production

---

## Examples Covered

| # | Command | What It Does |
|---|---------|--------------|
| 01 | `chmod 755 file` | Set standard executable permissions |
| 02 | `chmod u+x file` | Add execute for owner only |
| 03 | `chmod g-w file` | Remove write from group |
| 04 | `chmod a+x file` | Add execute for all users |
| 05 | `chmod o=r file` | Set read-only for others |
| 06 | `chmod -R 750 dir` | Recursive permission change |
| 07 | `chmod -v 644 *.conf` | Verbose mode to confirm changes |
| 08 | `chmod +t /dir` | Set sticky bit |
| 09 | `chmod u+s file` | Set SUID bit |
| 10 | `chmod g+s /dir` | Set SGID bit |
| 11 | `chmod u=rwx,g=rx,o= file` | Set multiple permissions at once |
| 12 | `find /dir -type f -exec chmod 644 {} \;` | Bulk update with find |

---

## Full Guide

👉 [Read the complete guide on LinuxTeck](https://www.linuxteck.com/chmod-command-in-linux-with-examples/)

---

## Author

**LinuxTeck** — A Complete Linux Learning Blog
🌐 [www.linuxteck.com](https://www.linuxteck.com)

---

### 🏷️ Suggested Repository Topics

Add these topics via the **gear icon ⚙️** next to "About" on your repository page:
```
chmod linux file-permissions linux-commands sysadmin devops
rhel ubuntu linux-security linux-administration shell-scripting
```
