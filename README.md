# Network IDS Using Snort

## 📌 Project Overview
This project demonstrates the implementation of a **Network Intrusion Detection System (NIDS)** using **Snort**.  
The system monitors real-time network traffic, detects suspicious activities using rule-based detection, and generates alerts for potential attacks.

This project was completed as part of my **Cyber Security Internship Task** to understand practical IDS deployment and network attack detection.

---

## 🎯 Objectives
- Deploy Snort as a Network IDS
- Detect port scanning and DoS attacks
- Analyze network traffic in real-time
- Generate alerts and logs for suspicious activities

---

## ⚙️ Key Features
- Real-time packet inspection
- Rule-based intrusion detection
- Alert generation on attack detection
- Log storage for further analysis
- Practical attack simulation for testing IDS

---

## 🛠️ Tools & Technologies Used
- **VirtualBox** – Virtualization platform
- **Kali Linux** – Attacking machine
- **Ubuntu Server 20.04 LTS** – Target server
- **Snort IDS** – Intrusion Detection System
- **Nmap** – Port scanning tool
- **Slowloris** – DoS attack tool
- **SSH** – Remote access
- **Apache2** – Web service on target server

---

## 🧱 System Architecture






Kali Linux (Attacker)
|
| Network Traffic
|
Ubuntu Server (Snort IDS + Apache)





---

## 🚀 Installation & Setup Guide

### Step 1: Install VirtualBox
Follow the official Kali Linux documentation:
https://www.kali.org/docs/virtualization/install-virtualbox-host/

---

### Step 2: Install Ubuntu Server
Download Ubuntu Server ISO:
https://ubuntu.com/download/server

Create a new Virtual Machine in VirtualBox and complete the installation.

---

### Step 3: Install Required Services on Ubuntu Server

```bash
sudo apt update
sudo apt install openssh-server apache2 snort -y
