NETWORKWALKS-MUSA-B084-WK1-PM1-CYBERSECURITY-LAB-SETUP
🔐 Cybersecurity Lab Setup
Building an isolated virtual lab for penetration testing and ethical hacking practice

           



![Cybersecurity](https://img.shields.io/badge/Project-Cybersecurity-404040?style=flat-square)
![VirtualBox](https://img.shields.io/badge/VirtualBox-Virtualization-0070C0?style=flat-square)
![Kali Linux](https://img.shields.io/badge/OS-Kali%20Linux-E87500?style=flat-square)
![Network Security](https://img.shields.io/badge/Focus-Network%20Security-238F89?style=flat-square)
![NetworkWalks](https://img.shields.io/badge/Program-NetworkWalks-404040?style=flat-square)

## 📌 Project Overview

This project focuses on setting up a virtual cybersecurity lab using **Oracle VirtualBox and Kali Linux** as part of the Cybersecurity Program at NetworkWalks (Batch B084).

The aim was to create a controlled environment for learning cybersecurity concepts, understanding virtual machine networking, and preparing for practical security testing exercises.

The lab uses a private NAT Network to provide network connectivity within the virtual environment.

## 🎯 Project Objectives

- Install and configure VirtualBox.
- Import and configure Kali Linux.
- Create a private NAT Network.
- Configure Kali Linux network settings.
- Verify IP configuration and network connectivity.
- Test DNS resolution.
- Create a VM snapshot for recovery.
- Document the lab setup process.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Oracle VirtualBox | Virtualization platform |
| Kali Linux | Cybersecurity learning environment |
| NAT Network | Virtual network configuration |
| Windows Host | Main operating system |

## 🏗️ Lab Setup & Configuration

### Step 1: Install and Configure VirtualBox

I installed Oracle VirtualBox to create and manage virtual machines for my cybersecurity learning environment.

### Step 2: Create a Private NAT Network

A private NAT Network was created in VirtualBox to provide network connectivity for the virtual machine.

**Network Configuration**

- Network Type: NAT Network
- Network Name: NatNetwork

**Screenshot 1: VirtualBox Network Configuration**

![VirtualBox Network Configuration](screenshots/01-virtualbox-network-config.png)

### Step 3: Import and Configure Kali Linux

Kali Linux was imported into VirtualBox and configured as the main virtual machine for the cybersecurity lab.

The VM network adapter was connected to the private NAT Network.

### Step 4: Configure Kali Linux IP Address

I checked and configured the network settings in Kali Linux to establish network communication.

The configuration included:

- IPv4 Address
- Subnet Mask
- Default Gateway
- DNS Server

**Screenshot 2: Kali Linux IP Configuration**

![Kali Linux IP Configuration](screenshots/02-kali-ip-configuration.png)

### Step 5: Verify Kali Linux Network Settings

I checked the network settings to confirm that Kali Linux was connected to the configured virtual network.

**Screenshot 3: Kali Linux Network Settings**

![Kali Linux Network Settings](screenshots/03-kali-network-settings.png)

## 🔎 Lab Verification

The network configuration and connectivity were tested to confirm that the virtual machine could communicate through the configured network.

The verification activities included:

- Checking IP configuration.
- Testing network connectivity.
- Testing DNS resolution.

## 💡 What I Learned

Through this hands-on project, I gained practical experience in:

1. **Virtualization:** Understanding how virtual machines work using VirtualBox.
2. **Network Configuration:** Learning how to configure virtual network adapters.
3. **NAT vs. NAT Network:** Understanding how NAT Network supports communication between connected virtual machines.
4. **IP Configuration:** Learning about IP addresses, gateways, and DNS settings.
5. **Documentation:** Recording technical configurations and documenting practical work.

## 🔐 Connecting Data Analytics with Cybersecurity

As someone developing skills in Data Science and Healthcare Data Analytics, I am also exploring cybersecurity to understand how to identify threats and protect systems that collect, process, and store data.

My goal is to combine data analytics knowledge with cybersecurity skills to support the secure and responsible use of data, particularly sensitive healthcare information.

## ⚠️ Security & Ethical Considerations

This lab is intended for educational purposes and authorized cybersecurity practice only.

All security testing should be performed on systems that I own or have explicit permission to test.

## 🔗 Tools & Learning Resources

- [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Kali Linux Official Website](https://www.kali.org/get-kali/)
- [Kali Linux Documentation](https://www.kali.org/docs/)
- [Wireshark Documentation](https://www.wireshark.org/docs/)
- [TryHackMe](https://tryhackme.com/)

## 🙏 Acknowledgment

Special thanks to **Sir Waqas Karim (CCIE)** and the **NetworkWalks team** for their guidance, support, and the opportunity to gain practical cybersecurity experience.

## 👤 Author
Musa Kichuri
LinkedIn: [https://www.linkedin.com/in/musa-kichuri-15871a180/
**Project:** Cybersecurity & Penetration Testing Lab Setup  
**Program:** NetworkWalks Cybersecurity Program  
**Batch:** B084  
**Project Week:** Week 01

---

*Continuously learning, practicing, and building skills in Data Science, Healthcare Analytics, and Cybersecurity.* 🚀
