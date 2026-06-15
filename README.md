# Network Packet Analysis Using Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates **Network Packet Analysis using Cisco Packet Tracer**, a powerful network simulation tool used for designing, configuring, and troubleshooting computer networks. The project focuses on analyzing packet flow between devices, understanding protocol behavior, and monitoring network communication using simulation mode.

The objective is to provide hands-on experience with network packet transmission, routing, switching, and troubleshooting in a simulated environment.

---

## 🎯 Objectives

- Design and configure a network topology using Cisco Packet Tracer.
- Analyze packet flow between network devices.
- Understand the working of TCP/IP protocols.
- Study packet encapsulation and de-encapsulation.
- Observe routing and switching operations.
- Troubleshoot network connectivity issues.
- Gain practical networking and cybersecurity knowledge.

---

## 🛠️ Tools and Technologies

| Tool | Purpose |
|--------|---------|
| Cisco Packet Tracer | Network Simulation |
| TCP/IP Protocol Suite | Communication |
| Routers | Packet Routing |
| Switches | Network Switching |
| PCs/End Devices | Network Communication |
| ICMP | Connectivity Testing |
| DNS | Name Resolution |
| HTTP | Web Communication |

---

## 🏗️ Network Topology

The network consists of:

- Router(s)
- Switch(es)
- End Devices (PCs)
- Servers (Optional)

### Sample Topology

---

## ⚙️ Configuration Steps

### 1. Create Network Topology

- Add routers, switches, and PCs.
- Connect devices using appropriate cables.

### 2. Configure IP Addresses

Example:

| Device | IP Address | Subnet Mask |
|----------|------------|-------------|
| Router0 | 192.168.1.1 | 255.255.255.0 |
| PC0 | 192.168.1.10 | 255.255.255.0 |
| PC1 | 192.168.1.11 | 255.255.255.0 |

### 3. Configure Router

```bash
enable
configure terminal
interface gigabitEthernet0/0
ip address 192.168.1.1 255.255.255.0
no shutdown
exit
