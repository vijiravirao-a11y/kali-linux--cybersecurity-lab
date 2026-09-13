# Kali Linux Virtual Machine Setup

## Project Overview

I set up a Kali Linux virtual machine using Oracle VirtualBox as the initial environment for learning cybersecurity and ethical hacking in a controlled lab environment.

## What I Set Up

* Installed and configured **Oracle VirtualBox**.
* Downloaded and imported **Kali Linux 2026.1** into VirtualBox.
* Configured Kali Linux as a virtual machine.
* Allocated system resources to the Kali VM.
* Configured the VM's network adapter to provide network connectivity.
* Troubleshot the Kali Linux network configuration.
* Verified network connectivity using commands such as `ping`.
* Checked the Kali Linux IP configuration using `ip a`.
* Configured the required network settings for the virtual machine.
* Practiced basic Linux commands inside Kali Linux.
* Installed and used **Nmap** for basic network-security learning.
* Created a working environment that can be used for future cybersecurity labs and practice.

## Tools Used

* **Oracle VirtualBox**
* **Kali Linux 2026.1**
* **Nmap**
* **Windows Host System**

## Troubleshooting

During the setup, I faced issues with:

* Kali Linux VM booting
* VirtualBox network configuration
* Internet/DNS connectivity
* Connecting the Kali VM to the required network

I worked through these configuration issues and got the Kali Linux environment running.

## Learning Outcomes

Through this setup, I learned:

1. How to create and configure a virtual machine.
2. How Kali Linux works inside VirtualBox.
3. Basic VM networking concepts.
4. How to check IP addresses and network connectivity in Linux.
5. Basic Nmap usage for cybersecurity learning.
6. How to troubleshoot VM and network configuration problems.
7. The importance of using a controlled environment for cybersecurity practice.

## Purpose

This environment will be used for **authorized cybersecurity learning, networking practice, penetration-testing labs, and future security projects**.

> **Ethical Use:** All security testing will be performed only on systems and networks that I own or have explicit permission to test.
## 🪜 Lab Setup Procedure

### Step 1: Install VirtualBox

Installed Oracle VirtualBox to create and manage the Kali Linux virtual machine.

### Step 2: Download Kali Linux

Downloaded the Kali Linux virtual machine from the official Kali Linux website.

### Step 3: Import Kali Linux into VirtualBox

Imported the Kali Linux virtual machine into VirtualBox and completed the initial VM configuration.

### Step 4: Configure VM Settings

Configured the required memory and other virtual machine settings before starting Kali Linux.

### Step 5: Configure Network

Configured the Kali Linux network adapter in VirtualBox to provide network connectivity.

### Step 6: Verify Kali Linux

Started Kali Linux and checked the system and network configuration using Linux commands.

### Step 7: Test Network Connectivity

Tested network connectivity using commands such as:

```bash
ip a
ping google.com
```

### Step 8: Install/Verify Nmap

Checked the Nmap installation and used it as part of the initial cybersecurity learning environment.

```bash
nmap --version
```

### Step 9: Basic Linux Practice

Practiced basic Linux commands and explored the Kali Linux environment to become familiar with the operating system.

---

## 🐞 Problems Encountered & Solutions

### Problem 1: Kali Linux VM Boot Issue

The Kali Linux virtual machine initially showed a boot-related error.

**Solution:**
Checked the VM configuration and the Kali Linux installation/import settings, then corrected the configuration and started the VM successfully.

### Problem 2: Network Connectivity Issue

Kali Linux initially had problems connecting to the Internet and resolving domain names.

**Solution:**
Checked the VirtualBox network adapter and Kali Linux network configuration and corrected the required settings.

### Problem 3: VirtualBox Configuration Issues

Some VirtualBox settings required troubleshooting during the initial setup.

**Solution:**
Checked the VM hardware and network configuration and adjusted the settings required for Kali Linux.

---

## 🔗 Tools & Resources

* **Oracle VirtualBox** – Used to create and run the Kali Linux virtual machine.
* **Kali Linux** – Security-focused Linux distribution used for cybersecurity learning.
* **Nmap** – Network scanning and security-testing tool.
* **7-Zip** – Used for extracting the Kali Linux virtual-machine archive, if required.

### Official Resources

* Oracle VirtualBox: https://www.virtualbox.org/
* Kali Linux: https://www.kali.org/
* Nmap: https://nmap.org/
* 7-Zip: https://www.7-zip.org/

---

## 👤 Author

**vijayalakshmi bai**
cybersecurity beginner

Interested in cybersecurity, ethical hacking, networking, and security tools.

---

## 📌 Project Information

| Category         | Details                                        |
| ---------------- | ---------------------------------------------- |
| Project          | Kali Linux Cybersecurity Lab Setup             |
| Purpose          | Cybersecurity learning and practical lab setup |
| Operating System | Kali Linux 2026.1                              |
| Virtualization   | Oracle VirtualBox                              |
| Security Tool    | Nmap                                           |
| Host OS          | Windows                                        |
| Project Type     | Cybersecurity Lab                              |
| Usage            | Authorized cybersecurity practice              |

### 🔐 Ethical Use

This laboratory is intended only for educational and authorized cybersecurity testing. Security testing should be performed only on systems and networks that you own or have explicit permission to test.

