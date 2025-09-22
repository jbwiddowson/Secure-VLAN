# 📘 Secure Cisco Switch Configuration

A comprehensive Cisco IOS switch configuration template focusing on **VLAN segmentation**, **Layer 2 security**, **QoS**, and **monitoring** for enterprise environments.

---

## 📄 Overview

This template applies **industry best practices** for:

- VLAN Security
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection (DAI)
- IP Source Guard
- Access Control Lists (ACLs)
- Logging and Monitoring
- SSH and Access Hardening

---

## 📁 Configuration Structure

| Section | Description |
|--------|-------------|
| **Initial Setup** | Hostname, domain, SSH, passwords, service hardening |
| **VLAN Creation** | Defines VLANs for departments, voice, management, DMZ |
| **SVI Setup** | VLAN interfaces for routing between VLANs |
| **Access Ports** | Port security, storm control, voice QoS, BPDU guard |
| **Trunks** | Secure trunks with allowed VLANs and root guard |
| **STP Security** | Enables Rapid-PVST, loop guard, root guard |
| **DHCP Snooping** | Protects against rogue DHCP servers |
| **DAI (ARP Inspection)** | Blocks ARP spoofing |
| **IP Source Guard** | Prevents IP spoofing on access ports |
| **ACLs** | Controls inter-VLAN access and guest restrictions |
| **QoS** | Prioritizes voice and critical traffic |
| **Monitoring** | Syslog, SNMP, SPAN configuration |
| **SSH & Access** | Secure remote access with banners and policies |
| **Verification** | Helpful post-deployment and maintenance commands |

---

## 🔐 Key Security Features

- Sticky MAC address learning
- Port security with shutdown/restrict modes
- Broadcast/multicast/unicast storm control
- DHCP snooping with trusted interfaces
- Dynamic ARP inspection (DAI)
- IP Source Guard on access ports
- ACLs for VLAN traffic filtering
- SSH v2 with RSA encryption
- Disabled unused services (HTTP, CDP, LLDP)
- SNMP (read-only)

---


