# Day 01 - Filesystem Exploration

## Objective
Understand Linux filesystem structure and navigate key directories.

## What I already knew
- /etc → config files
- /var → variable data such as logs, cache, etc...
- /bin → binaries, basic tools
- /boot → system starter
- /lib → common toolbox
- /dev → physical and virtual devices
- /tmp → temporary files
- /proc → live system data
- /opt → installed external software
- /home → self workspace

## Commands Used
```bash
ssh servername
pwd
cd /
whoami
sudo su -
ls -la /
ls bin
cat /bin/ls
file /bin/ls
ls lib64
file lib64/ld-linux-x86-64.so.2
ls /lib
ls /lib/nvidia
file /lib/nvidia/alternate-install-available
ls /var/log
find /var/log -name "*.log"
cat var/log/bootstrap.log
cat /proc/cpuinfo
ls dev/null
file dev/null
ls /etc
find /etc -name "*.conf" 2>/dev/null
find /etc -name "*.conf" | wc -l


Note: Used sudo su - to make exploration easier while learning