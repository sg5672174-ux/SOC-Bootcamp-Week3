# SOC Analyst Journey — Week 03: Linux 

## Overview

Week 3 of my SOC Analyst learning journey focused on Linux fundamentals and basic Linux security operations.

The week covered Linux commands, file permissions, processes, system logs, and authentication log analysis.

The practical lab focused on investigating failed authentication attempts from a SOC Analyst perspective.

## Topics Covered

### Linux Basics
- Linux file system
- Basic Linux commands
- Working with files and directories
- Searching and filtering information
- Command-line navigation

### Linux Permissions
- Read, write, and execute permissions
- File and directory permissions
- `chmod`
- `chown`
- Understanding permission notation

### Linux Processes
- Understanding processes
- Viewing running processes
- Process identification
- Monitoring processes
- Basic process management

### Linux Logs
- Linux log files
- Authentication logs
- System logs
- Using `journalctl`
- Searching logs with `grep`
- Basic log analysis

##  Lab
### Linux Authentication Investigation

In this lab, I investigated Linux authentication logs from the perspective of a Tier-1 SOC Analyst.

The investigation focused on identifying:

- Failed login attempts
- Repeated authentication failures
- Usernames involved
- Source IP addresses
- Authentication services
- Possible brute-force activity

### Commands Used

```bash
ls /var/log/
