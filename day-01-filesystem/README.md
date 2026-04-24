
# Day 01 - Linux Filesystem

## Objective
Understand the Linux filesystem structure and where to find key system components.

## What I Did
- Explored root directory `/`
- Navigated through `/etc`, `/var/log`, `/home`, `/proc`
- Used `find` to locate configuration files

## Commands Used
```bash
ls -la /
cd /etc
cd /var/log
cat /proc/cpuinfo
find /etc -name "*.conf" 2>/dev/null