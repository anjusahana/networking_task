Linux Task 02: Users, Groups & File Permissions

Overview

This lab introduces basic Linux administration concepts including navigation commands, directory management, file management, user and group management, file ownership, and file permissions. The exercises provide hands-on experience with Linux commands commonly used in system administration and cyber security.

---

 Objectives

* Learn basic Linux navigation commands.
* Create and manage directories and files.
* Understand Linux user and group management.
* Explore file ownership and permissions.
* Practice permission modification using `chmod`.
* Understand Linux security concepts and best practices.

---

 Tasks Performed

Part B: Basic Navigation Commands

Commands executed:

* `pwd`
* `ls`
* `ls -la`
* `cd`
* `clear`
* `history`
* `whoami`
* `hostname`

Purpose:

* Navigate the Linux file system.
* View files and directories.
* Identify the current user and system.

---
 Part C: Directory Management

Created directory structure:

CyberSecurity_Lab
├── Networking
├── Linux
├── CyberSecurity
├── EthicalHacking
└── Reports

Commands used:

* `mkdir`
* `cd`
* `tree`

---

Part D: File Management

Files created:

* notes.txt
* commands.txt
* report.txt

Operations performed:

* Create files using `touch`
* Copy files using `cp`
* Move and rename files using `mv`
* Delete files using `rm`

---

 User and Group Management

Groups created:

* interns
* cyberteam

Users created:

* student1
* student2
* student3

Commands used:

* `groupadd`
* `useradd`
* `usermod`
* `groups`
* `id`

---

File Ownership

Created files:

* report.txt
* notes.txt
* credentials.txt

Ownership verification:

* `ls -l`

Ownership modification:

* `sudo chown student1 credentials.txt`

---

File Permissions

Created file:

* security_policy.txt

Permissions tested:

| Permission Type | Command                       |
| --------------- | ----------------------------- |
| Read Only       | chmod 444 security_policy.txt |
| Read & Write    | chmod 666 security_policy.txt |
| Full Access     | chmod 777 security_policy.txt |

Commands used:

* `chmod`
* `ls -l`

---

Permission Analysis

| Permission | Description                                        |
| ---------- | -------------------------------------------------- |
| 755        | Owner has full access, others can read and execute |
| 644        | Owner can read and write, others can only read     |
| 777        | Everyone has full access                           |
| 600        | Only owner can read and write                      |
| 700        | Only owner has full access                         |

---

Security Concepts Learned

* Importance of file permissions
* User and group access control
* Principle of Least Privilege
* File ownership management
* Linux security best practices

---
 Conclusion

This lab provided practical experience with Linux administration and security fundamentals. Through user management, file ownership, and permission control, the importance of protecting system resources and maintaining secure access control was demonstrated.
