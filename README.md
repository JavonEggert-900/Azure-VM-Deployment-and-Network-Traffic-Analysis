# Azure VM Deployment and Network Traffic Analysis

<p align="center">
<img src="INSERT_HEADER_IMAGE_HERE" alt="Azure VM Networking Project Banner"/>
</p>

## Project Overview

This project demonstrates the deployment and management of Windows and Linux virtual machines within Microsoft Azure. The lab focused on configuring cloud infrastructure, analyzing live network traffic, troubleshooting connectivity issues, configuring firewall rules, establishing SSH remote access, and practicing responsible cloud resource management.

This hands-on implementation provided practical experience with the same types of cloud networking, system administration, and troubleshooting concepts used in real-world business environments.

---

# Environments and Technologies Used

* Microsoft Azure
* Azure Virtual Machines
* Azure Virtual Network (VNet)
* Azure Network Security Groups (NSGs)
* Windows 10 Virtual Machine
* Ubuntu Linux Virtual Machine
* Wireshark
* PowerShell
* SSH
* Remote Desktop Protocol (RDP)
* ICMP, SSH, DNS, and DHCP Protocols

---

# Operating Systems Used

* Windows 10
* Ubuntu Linux

---

# Project Objectives

* Deploy Windows and Linux virtual machines within Microsoft Azure
* Configure cloud networking using a shared Virtual Network
* Analyze live network traffic using Wireshark
* Configure firewall rules using Azure Network Security Groups
* Establish SSH connectivity between systems
* Practice troubleshooting and cloud resource management
* Understand business applications of cloud infrastructure and network security

---

# High-Level Deployment and Configuration Steps

1. Deploy Windows and Linux Virtual Machines in Azure
2. Configure Virtual Networking and Connectivity
3. Analyze ICMP Network Traffic Using Wireshark
4. Configure Firewall Rules Using Azure NSGs
5. SSH into the Linux Virtual Machine
6. Remove Azure Resources to Prevent Unnecessary Cloud Costs

---

# Deployment and Configuration Steps

## Step 1 — Deploy Windows and Linux Virtual Machines

<p>
<img src="<img width="1649" height="1072" alt="(1st) Lab 1 Screenshot Resource Ov copy" src="https://github.com/user-attachments/assets/f83acd96-83d0-4807-8256-c4b3975129dc" />
" height="80%" width="80%" alt="Azure Virtual Machines Running"/>
</p>

Deployed both Windows 10 and Ubuntu Linux virtual machines within Microsoft Azure and connected them through a shared Virtual Network. This simulated a real-world cloud infrastructure environment commonly used by businesses to host applications, services, and internal systems.

---

## Step 2 — Analyze Network Traffic Using Wireshark

<p>
<img src="INSERT_IMAGE_2_HERE" height="80%" width="80%" alt="Wireshark ICMP Traffic Analysis"/>
</p>

Captured and analyzed live ICMP traffic between both virtual machines using Wireshark. This demonstrated how network administrators monitor packet transmission, troubleshoot connectivity issues, and diagnose communication problems across enterprise systems.

---

## Step 3 — Configure Firewall Rules Using Azure NSGs

<p>
<img src="INSERT_IMAGE_3_HERE" height="80%" width="80%" alt="Azure NSG Firewall Configuration"/>
</p>

Configured custom Network Security Group firewall rules within Azure to block ICMP traffic between systems. This demonstrated how organizations secure cloud infrastructure by controlling inbound and outbound network communication to reduce security risks and protect sensitive systems.

---

## Step 4 — SSH into the Linux Virtual Machine

<p>
<img src="INSERT_IMAGE_4_HERE" height="80%" width="80%" alt="SSH Linux VM Connection"/>
</p>

Established an SSH connection from the Windows virtual machine directly into the Ubuntu Linux virtual machine and executed Linux commands remotely. This simulated real-world cloud administration workflows used by IT professionals to remotely manage servers and infrastructure.

---

## Step 5 — Delete Azure Resources and Practice Cost Management

<p>
<img src="INSERT_IMAGE_5_HERE" height="80%" width="80%" alt="Azure Resource Group Deletion"/>
</p>

Removed all deployed Azure resources after completing the lab to prevent unnecessary cloud charges and practice responsible cloud resource management. This reinforced the importance of infrastructure cleanup and cost optimization within cloud environments.

---

# Key Skills Demonstrated

* Cloud Infrastructure Deployment
* Azure Virtual Machine Management
* Network Troubleshooting
* Wireshark Packet Analysis
* Firewall Configuration
* SSH Remote Administration
* PowerShell Usage
* Virtual Networking
* Cloud Cost Management
* Problem Solving and Troubleshooting

---

# Business Applications

The concepts demonstrated throughout this project directly apply to real-world IT and cloud support environments. Businesses rely on cloud infrastructure, network troubleshooting, firewall security, remote administration, and cost management to maintain uptime, protect systems, support employees, and reduce operational expenses.

This project provided practical exposure to the same types of technologies and workflows used by cloud administrators, IT support specialists, and infrastructure teams in modern enterprise environments.

---

# Lessons Learned

This lab reinforced the importance of troubleshooting, persistence, and hands-on learning within cloud environments. Resolving configuration and connectivity issues throughout the project helped strengthen practical problem-solving skills while improving understanding of how networking and cloud infrastructure operate together in real-world environments.
