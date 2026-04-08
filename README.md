# ISEA Linux Server Environment Labs
BRG-27-labs
## BRG-27 Labs

Author: Hasha  
Module: ISEA – Server Environment Labs  

---

# 1. Overview
This repository contains the practical lab work completed for the ISEA module. The labs demonstrate fundamental Linux server administration skills including command-line navigation, file and directory management, permission configuration, SSH service installation, file searching, text processing, and basic automation using Bash scripting and cron scheduling.
# Overview

This repository documents the practical laboratory activities completed for the ISEA (Introduction to Server Environments and Architectures) module.

The purpose of these labs is to develop foundational skills in:

The activities were completed using a virtual Linux environment and documented with screenshots to provide evidence of successful execution.
- Linux server administration  
- cloud services and infrastructure  
- scripting and automation  
- server configuration and security  

Ubuntu Linux was installed and configured within a virtualized environment using Oracle VirtualBox. Throughout the lab sessions, command-line tools and system administration techniques were used to explore how Linux servers operate in real-world IT environments.

All commands executed, configurations applied, and observations made during the lab sessions are documented in this repository.

---

# 2. Lab Environment
# Lab Environment

The lab exercises were performed using the following tools:
The lab environment consisted of the following tools and technologies:

- Ubuntu Linux
- Oracle VirtualBox
- Linux Terminal
- Linux Terminal (Bash Shell)
- GitHub for documentation and version control

This environment allowed safe experimentation with Linux system administration commands and scripting techniques.
The Linux operating system was installed in a virtual machine created using VirtualBox, allowing experimentation with server configurations without affecting the host system.

---

# 3. Lab 1 – Linux Command Line and File Management
# Lab 1 – Linux Setup and Basic Commands

## Session 1a – Setting Up Linux

## Objectives
The objective of Lab 1 was to understand basic Linux command-line operations and system administration tasks.
The first session focused on preparing the working environment and installing Ubuntu Linux.

## Tasks Performed
Activities included:

- Navigating directories using `pwd`, `ls`, and `cd`
- Creating and managing files and directories
- Modifying file permissions using `chmod`
- Installing and managing SSH services
- Searching for files using the `find` command
- Searching text content using `grep`
- Creating a GitHub account and repository to document lab progress
- Installing Oracle VirtualBox
- Downloading the Ubuntu ISO image
- Creating and configuring a virtual machine
- Installing Ubuntu using the guided installation process

This session established the Linux environment used for all remaining lab exercises.

---

## Lab 1 Evidence
## Session 1b – Exploring Linux

### Linux Navigation Commands
Commands used to navigate directories and display file structures.
This session introduced the Linux command-line interface and basic filesystem navigation.

![Linux Navigation](screenshots/lab1_navigation.png)
Commands explored included:

---
pwd  
ls  
cd  
mkdir  
touch  

These commands allowed navigation through directories, creation of files and folders, and exploration of the Linux filesystem.

### File Permission Management
Changing file permissions using the `chmod` command.
Important directories examined included:

![File Permissions](screenshots/lab1_chmod.png)
/home  
/etc  
/var  

The `man` command was also used to access manual pages for learning how Linux commands work.

---

### SSH Installation
Installing and enabling the SSH service.
# Lab 2 – Linux Services and Automation

![SSH Installation](screenshots/lab1_ssh.png)
## Session 2a – Total Cost of Ownership (TCO)

---
This session explored the concept of Total Cost of Ownership when deploying server infrastructure.

### File Searching
Using the `find` command to locate files in directories.
A comparison was made between:

![Find Command](screenshots/lab1_find.png)
- cloud infrastructure
- on-premises servers

Factors considered included:

- hardware costs
- software licensing
- maintenance expenses
- operational costs

Cost projections were used to understand how organizations evaluate long-term infrastructure decisions.

---

### Text Searching
Using `grep` to search for text patterns in files.
## Session 2b – Cloud Services and Bash Scripting

This session introduced cloud infrastructure and server automation.

Activities included:

- creating a cloud server instance using AWS or Azure
- connecting to the server using SSH
- updating system packages and configuring the environment

![Grep Command](screenshots/lab1_grep.png)
Basic Bash scripting concepts were introduced, including:

- creating `.sh` script files
- using `echo`
- conditional statements
- loops
- setting script execution permissions using `chmod`

Automation helps reduce repetitive system administration tasks.

---

# 4. Lab 2 – Bash Scripting and Automation
# Lab 3 – DNS and Server Automation

## Session 3a – DNS and Digital Certificates

This session explored Domain Name System (DNS) configuration and server security.

Activities included:

## Objectives
The purpose of Lab 2 was to introduce shell scripting and task automation in Linux.
- configuring DNS records
- linking domain names to server IP addresses
- verifying DNS propagation using `dig` and `nslookup`

## Tasks Performed
Digital certificates were also explored using Let's Encrypt and Certbot to enable HTTPS encryption.

- Creating Bash scripts
- Assigning execution permissions to scripts
- Running shell scripts in the terminal
- Understanding task automation
- Introduction to cron scheduling
This demonstrated how servers secure communication between users and web services.

---

## Lab 2 Evidence
## Session 3b – Server Automation

### Bash Script Example
Example of a simple Bash script created during the lab.
This session focused on automating server administration tasks using Bash scripts and cron jobs.

![Bash Script](screenshots/lab2_script.png)
Scripts were created to automate tasks such as:

- system updates
- maintenance tasks
- log file generation

The cron scheduler was used to run scripts automatically using:

crontab -e

Automation improves efficiency and reliability in server management.

---

### Script Execution
Running the script in the Linux terminal.
# Lab 4 – Additional Server Services and Reflection

## Session 4a – Additional Server Services

An additional Linux server service was installed and configured to extend server functionality.

![Script Execution](screenshots/lab2_execution.png)
Possible services include:

- MySQL
- Docker
- FTP
- Jenkins
- Samba

The process involved installing the service, configuring basic settings, and verifying that the service operates correctly.

---

### Cron Job Scheduling
Demonstration of scheduling tasks using cron.
## Session 4b – Documentation and Reflection

The final session focused on documenting lab activities and reflecting on the learning experience.

The GitHub repository was updated with:

- command explanations
- screenshots of terminal outputs
- descriptions of tasks performed

![Cron Job](screenshots/lab2_cron.png)
This documentation demonstrates completion of the lab activities and highlights the technical skills gained throughout the module.

Key skills developed include:

- Linux command-line management
- server configuration
- scripting automation
- cloud infrastructure concepts

These skills are relevant to careers in system administration, cloud engineering, and DevOps.

---

# 5. Conclusion
# Evidence

The ISEA labs provided practical experience with Linux system administration and scripting. Through these activities, key concepts such as command-line operations, file permission management, service configuration, and automation using Bash scripting were successfully implemented.
Screenshots of terminal commands and outputs are included to demonstrate the successful completion of the lab activities.

These skills are essential for managing Linux server environments and form the foundation for more advanced system administration and cybersecurity practices.
These screenshots provide visual proof of command execution and system configuration.

---

# 6. Repository Structure
# Repository Structure

BRG-27-labs
│
├── README.md
├── reflective-journal.md
└── screenshots
    ├── lab1_commands.png
    ├── ssh_service.png
    ├── file_permissions.png
    └── scripting_example.png

---

## Key Learning Outcomes

Through completing these labs, I developed practical skills in Linux server administration and automation.

Key concepts learned include:

- Navigating the Linux filesystem using command-line tools
- Managing Linux services such as SSH
- Understanding and modifying file permissions
- Searching files and content using `find` and `grep`
- Automating server tasks using Bash scripts
- Understanding cloud infrastructure and server deployment concepts
