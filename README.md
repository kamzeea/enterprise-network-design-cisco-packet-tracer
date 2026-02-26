# Enterprise Network Design & Implementation (Cisco Packet Tracer)

## Project Overview

This project showcases the design and implementation of a **secure enterprise network infrastructure** for a simulated organization, **ABC Corporation**. It focuses on modernizing an outdated network to improve **connectivity**, **scalability**, and **security** across multiple departments.

The network was built and tested in **Cisco Packet Tracer**, applying real-world concepts such as **subnetting**, **routing**, **secure remote access**, and **network verification**.

Full technical documentation: **CT210_Case Study Documentation**

---

## Project Objectives

- Design a **scalable** enterprise network architecture  
- Implement efficient IP addressing using **VLSM**  
- Configure **secure remote access (SSH)**  
- Enable reliable **inter-department communication**  
- Improve **network security** and management  
- Validate end-to-end connectivity through **testing**

---

## Business Scenario

**ABC Corporation** required a network upgrade to:

- Support a new department and future growth  
- Improve operational efficiency and uptime  
- Strengthen security controls for administrative access  
- Ensure reliable communication between departments  

The solution delivers a **future-ready, modular infrastructure** capable of expansion with minimal redesign.

---

## Skills Demonstrated

**Networking & Design**

- Enterprise **network topology** design  
- **Router** and **switch** configuration  
- **VLAN** planning and management  
- **Routing** configuration and verification  
- **ARP** and **MAC table** analysis  

**Security**

- **SSH**-based secure remote access  
- **Password encryption** and authentication  
- **Banner MOTD** for unauthorized access warnings  
- Basic **access control** configuration  

**Infrastructure Design**

- **Variable Length Subnet Masking (VLSM)**  
- **IP address planning** and subnet allocation  
- **Network segmentation** by department  
- **Fault-tolerant** topology design  

**Tools & Troubleshooting**

- **Cisco Packet Tracer**  
- **Cisco IOS CLI** configuration  
- Network **troubleshooting** and diagnostics  

---

## Network Architecture

The enterprise network connects three departments:

- **Accounting (Subnet A)**  
- **Business Services (Subnet B)**  
- **Customer Services (Subnet C)**  

A central router, **NetProEdge**, provides:

- Inter-subnet routing between departments  
- Connectivity to an upstream **ISP** for external access  

The topology diagram (Appendix A, page 8) illustrates:

- A layered **switch** structure  
- Department-based **segmentation**  
- **Router-based** interconnection

---

## IP Address Design

**VLSM** was used to efficiently allocate IP ranges based on department size:

| Subnet   | Department        | Hosts |
|---------|-------------------|-------|
| Subnet A | Accounting        | 500   |
| Subnet B | Business Services | 100   |
| Subnet C | Customer Services | 30    |

Example address plan:

- **Subnet A:** `172.17.168.0/23`  
- **Subnet B:** `172.17.170.0/25`  
- **Subnet C:** `172.17.170.128/27`  

(Full IP design: IP Design table — pages 8–9.)

---

## Security Implementation

Security configurations included:

- **Encrypted passwords** on network devices  
- **SSH Version 2** for secure remote management  
- **Console** and **VTY** authentication  
- **Automatic session timeouts**  
- **Unauthorized access warning banner (MOTD)**  

These measures ensure secure administrative access across all network devices (see Security section — page 5).

---

## Network Services Configured

- Device **hostnames**  
- **IP addressing** on interfaces  
- **Default gateways** for end devices  
- **SSH connectivity** for management  
- **Routing tables** configuration  
- **MAC address** learning  
- **ARP** resolution  

---

## Connectivity Testing ✅

Network functionality was verified using:

- **Ping tests** between subnets  
- **Switch communication** validation  
- **Gateway reachability** tests  
- **ISP simulation** connectivity  

Successful packet transmission confirmed full network operability (Appendix F, pages 38–40).

---

## Technical Validation

Verification steps included:

- Reviewing **MAC address tables**  
- Checking **ARP tables**  
- Validating **routing tables**  
- Checking **interface status**  

The router’s **routing table** confirms inter-network communication paths (Appendix I, page 42).

---

## Technologies Used

- **Cisco Packet Tracer**  
- **Cisco IOS CLI**  
- **IPv4 networking**  
- **VLSM subnetting**  
- **SSH protocol**  
- **Enterprise network design principles**

---

## Key Outcomes

- Secure **multi-department** network  
- Efficient IP utilization via **VLSM**  
- Successful **inter-subnet routing**  
- **Encrypted** remote administration  
- Verified **end-to-end connectivity**
