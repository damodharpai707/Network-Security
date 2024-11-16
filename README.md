# 🌐 SEED Labs - Network Security

![SEED Labs Banner]() 

📚 **Welcome to the SEED Labs - Network Security Repository!**  
This repository contains lab exercises designed to provide hands-on experience in network security concepts, using the SEED Labs framework. You will explore ARP attacks, firewalls, and advanced network configurations in a virtual lab environment.

---

## 📋 Table of Contents

- [🚀 Introduction](#-introduction)
- [🧪 Lab Descriptions](#-lab-descriptions)
  - [1️⃣ ARP Cache Poisoning Attack](#1️⃣-arp-cache-poisoning-attack)
  - [2️⃣ Firewall Exploration](#2️⃣-firewall-exploration)
  - [3️⃣ Lab Setup Instructions](#3️⃣-lab-setup-instructions)
- [🛠️ Prerequisites](#️-prerequisites)
- [📖 Usage](#-usage)
- [✅ Deliverables](#-deliverables)
- [🔗 References](#-references)

---

## 🚀 Introduction

The **SEED Labs - Network Security** repository focuses on building practical skills in network security.  
You will learn:
- The vulnerabilities of the Address Resolution Protocol (ARP) and how they can be exploited.
- Configuring and managing both stateless and stateful firewalls using `iptables`.
- Setting up a secure virtual lab using **VirtualBox** and **Docker** containers.

---

## 🧪 Lab Descriptions

### 1️⃣ ARP Cache Poisoning Attack
> **Focus:** Exploiting ARP protocol vulnerabilities to conduct attacks.

📌 **Key Topics**:
- Understanding the ARP protocol and its weaknesses.
- Conducting ARP cache poisoning attacks.
- Implementing Man-in-the-Middle (MITM) attacks.
- Using tools like **Scapy** for packet crafting and **Wireshark** for network analysis.

📄 Detailed steps and explanations are provided in [`Lab_ARP Cache Poisoning Attack.pdf`](./Lab_ARP%20Cache%20Poisoning%20Attack.pdf).

---

### 2️⃣ Firewall Exploration
> **Focus:** Implementing and exploring firewalls using Linux and `iptables`.

📌 **Key Topics**:
- Writing a stateless firewall using Linux kernel modules.
- Configuring a stateful firewall with `iptables`.
- Connection tracking and rule setups.
- Advanced concepts like load balancing and traffic limitation.

📄 Refer to [`Lab_Firewall Exploration.pdf`](./Lab_Firewall%20Exploration.pdf) for instructions and tasks.

---

### 3️⃣ Lab Setup Instructions
> **Focus:** Configuring the environment for SEED Labs.

📌 **Key Steps**:
- Setting up **VirtualBox** with the SEED Ubuntu 20.04 VM.
- Installing and configuring Docker containers for experiments.
- Preparing a complete lab setup for network security tasks.

📄 Check out [`Lab_Setup.pdf`](./Lab_Setup.pdf) for a detailed guide.

---

## 🛠️ Prerequisites

### 🔧 **Hardware Requirements**
- **RAM:** 8 GB  
- **Disk Space:** 40 GB free  
- **Processor:** 2 GHz, 4+ cores  

### 💻 **Software Requirements**
- [Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads)  
- [SEED Ubuntu 20.04 VM](https://seedsecuritylabs.org/labsetup.html)

---

## 📖 Usage

1. **Clone the repository**:
   `git clone https://github.com/yourusername/seed-labs-network-security.git
   cd seed-labs-network-security`

2. **Set up the lab environment** by following the instructions in [`Lab_Setup.pdf`](./Lab_Setup.pdf).

3. **Complete the labs** as outlined in the provided PDFs and document your results with text and screenshots.

---

## ✅ Deliverables

Each lab report should include:
- **Title** and **author(s)**.  
- **Table of contents**.  
- **Step-by-step documentation** with results (text + screenshots).  
- **Reflection**:
  - Purpose of the lab.
  - Learnings and objectives achieved.
  - Challenges faced and feedback.

---

## 🔗 References

- 📘 **SEED Labs Documentation**: [SEED Labs 2.0](https://seedsecuritylabs.org/labs.html)  
- 🖥️ **VirtualBox**: [Oracle VirtualBox](https://www.virtualbox.org/)  
- 🛠️ **SEED Ubuntu VM**: [Setup Guide](https://seedsecuritylabs.org/labsetup.html)
