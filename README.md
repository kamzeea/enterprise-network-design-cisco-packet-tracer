Enterprise Network Design & Implementation (Cisco Packet Tracer)

Project Overview

This project demonstrates the design and implementation of a secure enterprise network infrastructure for a simulated organization (ABC Corporation). The objective was to modernize an outdated network by improving connectivity, scalability, and security across multiple departments.

The network was designed and tested using Cisco Packet Tracer, incorporating real-world networking concepts such as subnetting, routing, secure remote access, and network verification.

Full technical documentation: CT210_Case Study Documentation

*Project Objectives*

Design a scalable enterprise network architecture

Implement efficient IP addressing using VLSM

Configure secure remote access (SSH)

Enable inter-department communication

Improve network security and management

Validate connectivity through testing

*Business Scenario*

ABC Corporation required a network upgrade to:

Support a new department

Improve operational efficiency

Strengthen security controls

Ensure reliable communication between departments

The solution provides a future-ready infrastructure capable of expansion.



*Skills Demonstrated*

Networking

Network topology design

Router & switch configuration

VLAN management

Routing configuration

ARP & MAC table analysis

Security

SSH secure remote access

Password encryption

Banner MOTD implementation

Access control configuration

Infrastructure Design

Variable Length Subnet Masking (VLSM)

IP address planning

Network segmentation

Fault-tolerant topology

Tools

Cisco Packet Tracer

CLI configuration (Cisco IOS)

Network troubleshooting


*Network Architecture*

The enterprise network connects three departments:

Accounting (Subnet A)

Business Services (Subnet B)

Customer Services (Subnet C)

A central router (NetProEdge) enables communication between subnets and external connectivity.

The topology diagram (Appendix A, page 8) illustrates:

Layered switch structure

Department segmentation

Router-based interconnection

*IP Address Design*

VLSM was used to efficiently allocate IP ranges based on department size:

Subnet	Department	Hosts
Subnet A	Accounting	500
Subnet B	Business Services	100
Subnet C	Customer Services	30

(See IP Design table — page 8–9.)

Example:

Subnet A: 172.17.168.0/23

Subnet B: 172.17.170.0/25

Subnet C: 172.17.170.128/27


*Security Implementation*

Security configurations included:

Encrypted passwords

SSH Version 2 remote management

Console & VTY authentication

Automatic session timeouts

Unauthorized access warning banner

These measures ensure secure administrative access across all network devices.

(Documented in Security section — page 5.)

*Network Services Configured*

Device hostnames

IP addressing

Default gateways

SSH connectivity

Routing tables

MAC address learning

ARP resolution

✅ Connectivity Testing

Network functionality was verified using:

Ping tests between subnets

Switch communication validation

Gateway reachability tests

ISP simulation connectivity

Successful packet transmission confirmed full network operability (Appendix F, pages 38–40).


*Technical Validation*

Verification included:

MAC Address Tables

ARP Tables

Routing Tables

Interface Status Checks

Router routing table confirms inter-network communication paths (Appendix I, page 42).

*Technologies Used*

Cisco Packet Tracer

Cisco IOS CLI

IPv4 Networking

VLSM Subnetting

SSH Protocol

Enterprise Network Design Principles
