# B084-WK1-CYBERSECURITY-LAB-SETUP
My Week 1 practical project: Setting up a Cybersecurity and Ethical Hacking Lab using VirtualBox and Kali Linux.
# 🔐 Cybersecurity Lab Setup – Week 1

**Program:** Cybersecurity Training – NetworkWalks  
**Batch:** B082  
**Project:** Cybersecurity & Ethical Hacking Lab Setup  
**Author:** Musa kichuri

## 1. Project Overview

This project involved setting up a virtual laboratory for learning cybersecurity and ethical hacking.

I used Oracle VirtualBox to run Kali Linux as a virtual machine on my computer. The aim was to prepare a practical environment where I can learn Linux, networking, security tools, and perform authorized security testing.

## 2. Project Objectives

The main objectives of this practical exercise were to:

- Install and prepare Oracle VirtualBox.
- Download and extract the Kali Linux virtual machine package.
- Import Kali Linux into VirtualBox.
- Configure the virtual machine settings.
- Explore VirtualBox network configuration.
- Prepare a virtual environment for future cybersecurity exercises.
- Understand the basic differences between NAT and NAT Network.

## 3. System and Lab Configuration

| Component | Configuration |
|---|---|
| Host Operating System | Windows |
| Host RAM | 8 GB |
| Storage | 1 TB SSD |
| Virtualization Software | Oracle VirtualBox |
| Guest Operating System | Kali Linux |
| Virtual Network | NAT Network |
| Kali Linux RAM | NAT Network |

## 4. Lab Setup Process

### Step 1: Installing Oracle VirtualBox

I installed Oracle VirtualBox on my Windows computer to create and manage virtual machines.

### Step 2: Downloading and Extracting Kali Linux

I downloaded the Kali Linux VirtualBox image and extracted the downloaded package to access the virtual machine files.

### Step 3: Importing Kali Linux

I added the Kali Linux virtual machine to Oracle VirtualBox and checked that it could start successfully.

### Step 4: Configuring the Virtual Machine

I reviewed the virtual machine settings, including memory allocation, processor settings, and network adapter configuration.

### Step 5: Virtual Network Configuration

I explored the available VirtualBox networking options and worked on setting up a NAT Network for the cybersecurity lab.

**My network configuration:**

- Network Name: NAT Network
- Network Type: NAT Network
- IPv4 Prefix: 10.0.0.0/24
- DHCP: Enabled

### Step 6: Testing the Kali Linux Environment

I used Linux terminal commands to inspect the network configuration and check connectivity.

Commands used:

```bash
ip addr Displayed the network interface and assigned IP address.
ip route Displayed the default route and gateway.
ping -c 4 8.8.8.8 Successfully received replies from the destination, confirming internet connectivity.
getent hosts google.com Successfully resolved the domain name to an IP address, confirming DNS resolution.
```

**Results:** The Kali Linux virtual machine was able to connect to the network and access the internet.

## 5. What I Learned

Through this practical exercise, I gained experience in:

1. Understanding virtualization and how virtual machines work.
2. Installing and running Kali Linux using VirtualBox.
3. Understanding virtual machine hardware and network settings.
4. Learning the differences between NAT and NAT Network.
5. Using basic Linux commands to inspect network configuration.
6. Preparing a controlled environment for cybersecurity practice.

## 6. Challenges Encountered

During the setup, I experienced some challenges locating and configuring the network settings in VirtualBox.

I worked through the VirtualBox settings, identified the NAT Network configuration option, and continued setting up my virtual lab.

This helped me understand the VirtualBox interface and become more familiar with virtual networking.

## 7. Importance of This Project

Setting up this laboratory provides a foundation for future practical cybersecurity exercises, including network analysis, vulnerability assessment, and ethical hacking.

All security testing activities will be conducted in controlled environments and on systems where I have permission to perform testing.

## 8. Conclusion

Successfully setting up Kali Linux in VirtualBox was an important first step in my cybersecurity learning journey.

I look forward to building on this knowledge through more practical exercises and developing the skills needed to pursue a career as a Cybersecurity Analyst.

## 9. Project Evidence

The screenshots below show my actual lab setup and configuration.

- Kali Linux running in VirtualBox.
- Virtual machine configuration.
- Network configuration.
- Terminal and connectivity verification.

## 10. Acknowledgement

I appreciate NetworkWalks and my mentor, Waqas Karim, for the guidance and learning opportunity provided through this cybersecurity training program.

**Training:** NetworkWalks Cybersecurity Program  
**Batch:** B084  
**Week:** 01
