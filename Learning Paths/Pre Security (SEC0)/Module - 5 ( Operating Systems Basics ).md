# 🖥️ Operating Systems Basics

> **Learning Path:** Pre Security
> **Module:** 05 — Operating Systems Basics
> **Platform:** TryHackMe
> **Status:** ✅ Completed

---

# 📖 About This Module

Operating systems are the foundation of every modern computer system. They act as the bridge between hardware and software, managing system resources while providing users and applications with a secure and efficient environment to perform tasks.

Whether using Windows, Linux, macOS, Android, or iOS, every digital device relies on an operating system to coordinate processes, manage memory, organize files, control hardware, and facilitate communication between applications and the underlying hardware.

For cybersecurity professionals, understanding operating systems is essential. Attackers exploit operating system vulnerabilities, while defenders use built-in security features, logs, permissions, and system utilities to detect, investigate, and respond to threats.

This module introduces the architecture, components, and day-to-day operation of modern operating systems, providing the foundation for system administration, digital forensics, malware analysis, cloud computing, and penetration testing.

---

# 🎯 Learning Objectives

After completing this module, I was able to:

* Explain the purpose of an operating system.
* Understand the relationship between hardware, software, and the operating system.
* Compare Windows and Linux operating systems.
* Understand the role of the kernel.
* Navigate file systems using command-line interfaces.
* Understand users, groups, and permissions.
* Explain processes, services, and resource management.
* Build foundational knowledge for system administration and cybersecurity.

---

# 📚 Rooms Completed

| Room                           | Status      |
| ------------------------------ | ----------- |
| Operating Systems Introduction | ✅ Completed |
| Windows Basics                 | ✅ Completed |
| Linux Shell                    | ✅ Completed |
| Windows Command Line           | ✅ Completed |
| Linux Fundamentals             | ✅ Completed |

---

# 🌍 Why Operating Systems Matter

Every cybersecurity discipline depends on understanding operating systems.

A security analyst investigates Windows Event Logs.

A penetration tester interacts with Linux servers.

A malware analyst studies process behaviour.

A cloud engineer manages Linux virtual machines.

A SOC analyst monitors system logs.

A forensic investigator examines file systems.

Without understanding how operating systems work, analysing attacks or securing systems becomes extremely difficult.

Operating systems provide:

* Resource management
* Security controls
* User authentication
* File management
* Process scheduling
* Network communication
* Hardware abstraction

Understanding these responsibilities enables cybersecurity professionals to diagnose problems, identify malicious activity, and secure enterprise environments.

---

# 🧠 Core Concepts

Throughout this module I explored the following concepts.

---

## What is an Operating System?

An Operating System (OS) is system software responsible for managing computer hardware and software resources while providing services for applications and users.

Its primary responsibilities include:

* Managing hardware resources
* Running applications
* Managing memory
* Controlling storage
* Managing files
* Providing security
* Scheduling processes
* Handling networking

Examples include:

* Microsoft Windows
* Linux
* macOS
* Android
* iOS

---

## The Kernel

The kernel is the core component of an operating system.

It acts as the intermediary between hardware and software, controlling access to system resources and ensuring stable operation.

Responsibilities include:

* CPU scheduling
* Memory management
* Device communication
* Process management
* Interrupt handling
* System calls

Without the kernel, applications cannot communicate directly with hardware.

---

## File Systems

Operating systems organise data using hierarchical file systems.

Common elements include:

* Files
* Directories
* File paths
* Partitions
* Storage devices

Examples:

Windows

```text
C:\Users\Aman\Documents
```

Linux

```text
/home/aman/Documents
```

Understanding file systems is essential for digital forensics, malware analysis, and incident response.

---

## Windows Operating System

Microsoft Windows is the most widely used desktop operating system in enterprise environments.

Common components include:

* Desktop Environment
* Task Manager
* File Explorer
* Windows Registry
* Event Viewer
* PowerShell
* Command Prompt

Windows provides extensive enterprise security features including:

* Windows Defender
* BitLocker
* Windows Firewall
* Active Directory Integration
* Group Policy

---

## Linux Operating System

Linux is widely used in servers, cloud infrastructure, cybersecurity, networking equipment, and embedded systems.

Characteristics include:

* Open Source
* Highly Customisable
* Stable
* Secure
* Command-Line Oriented

Popular distributions include:

* Ubuntu
* Debian
* Fedora
* Kali Linux
* Arch Linux
* Red Hat Enterprise Linux

Linux plays a major role in cloud computing, penetration testing, DevOps, and cybersecurity.

---

## Command Line Interfaces (CLI)

Command-line interfaces allow users to interact directly with the operating system using text-based commands.

Examples include:

Windows

* cmd
* PowerShell

Linux

* Bash
* Zsh

Learning the command line improves efficiency and provides greater control over system administration tasks.

---

## Users and Permissions

Operating systems enforce security through user accounts and permission models.

Key concepts include:

* User Accounts
* Groups
* Authentication
* Authorization
* File Permissions
* Administrative Privileges

Proper permission management reduces the risk of unauthorized access and privilege escalation.

---

## Processes and Services

Applications execute as processes managed by the operating system.

The OS is responsible for:

* Starting processes
* Allocating resources
* Scheduling CPU time
* Terminating processes
* Monitoring system performance

Background services continuously perform essential system functions, such as networking, printing, logging, and updates.

---

# ⚖️ Windows vs Linux

| Feature            | Windows                 | Linux                    |
| ------------------ | ----------------------- | ------------------------ |
| Source Code        | Proprietary             | Open Source              |
| Enterprise Desktop | Excellent               | Moderate                 |
| Servers            | Good                    | Excellent                |
| Cybersecurity      | Widely Targeted         | Widely Used for Security |
| Command Line       | PowerShell / CMD        | Bash / Shell             |
| Package Management | Microsoft Store, Winget | APT, DNF, Pacman, etc.   |
| Customisation      | Moderate                | Extensive                |

Both operating systems are important for cybersecurity professionals.

---

# 🛠 Skills Gained

By completing this module, I developed an understanding of:

* Operating system architecture
* Windows fundamentals
* Linux fundamentals
* Command-line navigation
* File systems
* User management
* Permissions
* Process management
* Basic system administration

---

# 💼 Real-World Applications

The knowledge gained from this module directly supports:

* Linux Administration
* Windows Administration
* Security Operations Centers (SOC)
* Active Directory
* Digital Forensics
* Malware Analysis
* Penetration Testing
* Cloud Infrastructure
* DevOps
* Incident Response

Understanding operating systems enables cybersecurity professionals to investigate incidents, secure systems, and automate administrative tasks.

---

# 🗺️ Operating System Architecture

```text
User
│
▼
Applications
│
▼
Operating System
│
├── Kernel
├── File System
├── Process Manager
├── Memory Manager
├── Device Drivers
└── Security Manager
│
▼
Hardware
├── CPU
├── RAM
├── Storage
├── Network Card
└── Peripherals
```

---

# 🌐 Windows & Linux Ecosystem

```text
Operating Systems
│
├── Windows
│   ├── Desktop
│   ├── Registry
│   ├── PowerShell
│   └── Active Directory
│
└── Linux
    ├── Bash
    ├── File Permissions
    ├── Shell Utilities
    └── Open Source Ecosystem
```

---

# 🔗 Connections to Future Modules

This module provides the foundation for:

* Linux Fundamentals
* Windows Fundamentals
* Active Directory
* Bash Scripting
* PowerShell
* Digital Forensics
* Malware Analysis
* SOC Level 1
* Security Engineer
* DevOps
* Cloud Computing
* Docker
* Kubernetes

Mastering operating systems is one of the most valuable long-term investments for anyone pursuing cybersecurity.

---

# 📋 Revision Checklist

* [x] Understand the role of an operating system
* [x] Explain kernel responsibilities
* [x] Navigate Windows and Linux file systems
* [x] Understand users and permissions
* [x] Explain processes and services
* [x] Compare Windows and Linux
* [x] Understand command-line interfaces

---

# 📌 Key Takeaways

* The operating system manages communication between hardware, software, and users.
* Windows and Linux dominate enterprise computing and cybersecurity.
* The kernel is the core component responsible for managing system resources.
* File systems, permissions, and processes are fundamental concepts for securing computers.
* Command-line skills are essential for efficient system administration and cybersecurity work.
* A strong understanding of operating systems forms the foundation for advanced topics such as digital forensics, cloud security, malware analysis, and penetration testing.

---

# 📖 Further Reading

* Microsoft Learn — Windows Fundamentals
* Linux Foundation Documentation
* Ubuntu Documentation
* Red Hat Documentation
* Microsoft PowerShell Documentation
* GNU Bash Manual
* NIST Computer Security Resource Center

---

# 🏆 Module Completion

**Module:** Operating Systems Basics
**Learning Path:** Pre Security
**Platform:** TryHackMe

**Status:** ✅ Completed

---

> *"An operating system is more than software—it is the foundation upon which every secure system is built. Master the operating system, and you build the foundation for mastering cybersecurity."*
