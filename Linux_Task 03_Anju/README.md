# Linux Task 03 - Process Management, System Monitoring & Basic Shell Scripting

## Student Information

* **Name:** Anju Sahana
* **Task:** Linux Task 03
* **Topic:** Process Management, System Monitoring & Basic Shell Scripting

---

## Objective

The objective of this task is to understand how Linux manages processes, monitors system resources, manages services, and automates tasks using shell scripts. These skills are important for Linux Administrators, SOC Analysts, and Cyber Security Professionals.

---

## Part A: Process Monitoring

Commands Used:

```bash
ps
ps aux
top
htop
```

Activities Performed:

* Viewed running processes.
* Identified Process IDs (PID).
* Monitored CPU and memory usage.
* Analyzed active processes using `top` and `htop`.

---

## Part B: Process Management

Commands Used:

```bash
sleep 300
ps aux | grep sleep
kill PID
kill -9 PID
```

Activities Performed:

* Created a temporary process using `sleep`.
* Located the process using its PID.
* Terminated the process using `kill`.
* Forcefully terminated a process using `kill -9`.

---

## Part C: System Monitoring

Commands Used:

```bash
free -h
df -h
uptime
uname -a
```

Information Collected:

* Total RAM
* Available RAM
* Disk Usage
* System Uptime
* Kernel Version

---

## Part D: Service Monitoring

Commands Used:

```bash
systemctl status ssh
systemctl status NetworkManager
```

Activities Performed:

* Checked the status of system services.
* Understood the importance of background services.
* Learned how service failures can affect system functionality.

---

## Part E: Shell Scripting

Script Name:

```bash
system_report.sh
```

Features:

* Displays current user.
* Displays hostname.
* Displays current date and time.
* Displays current directory.
* Displays memory usage.
* Displays disk usage.

Execution:

```bash
chmod +x system_report.sh
./system_report.sh
```

---

## Part F: Security Monitoring Research

Commands Studied:

* `netstat`
* `ss`
* `who`
* `w`
* `last`

Topics Covered:

* Purpose of each command.
* Example outputs.
* Security monitoring use cases.
* User activity and network monitoring.

---

## Part G: Mini SOC Activity

Topics Covered:

1. Identifying resource-heavy processes.
2. Detecting suspicious processes.
3. Collecting information before terminating a process.

Tools Used:

* `top`
* `htop`
* `ps aux`
* `kill`

---

## Folder Structure

```text
Linux_Task_03_AnjuSahana/
├── Screenshots/
├── Shell_Script/
│   └── system_report.sh
├── System_Report/
├── Command_Outputs/
├── Research_Answers/
└── README.md
```

---

## Conclusion

This task provided practical experience in Linux process management, system monitoring, service monitoring, shell scripting, and basic security analysis. The commands and techniques learned are essential for Linux administration and cyber security operations.
