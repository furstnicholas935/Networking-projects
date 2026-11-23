
# Enterprise Network Architecture & Engineering Lab

**Cisco Modeling Labs (CML) | Enterprise Routing | Switching | WAN | Network Security**

---

## 1. Project Overview

This repository documents the design, implementation, and validation of a simulated enterprise network built using Cisco Modeling Labs (CML).

The project is intended to demonstrate practical network engineering skills through the development of a multi-site enterprise environment incorporating redundant infrastructure, dynamic routing, network segmentation, WAN connectivity, security controls, and centralized network services.

Rather than focusing solely on individual protocol configurations, the project emphasizes **network architecture, design decisions, operational resilience, troubleshooting, and technical documentation.**

### Project Objectives

- Design a scalable, multi-site enterprise network architecture.
- Implement redundant campus switching and routing infrastructure.
- Configure and validate enterprise routing protocols.
- Develop secure WAN connectivity between geographically separated sites.
- Implement network segmentation and access-layer security.
- Deploy centralized network infrastructure services.
- Document technical design decisions and operational procedures.
- Validate network behavior under normal and failure conditions.

---

## 2. Network Architecture

The simulated enterprise environment consists of a headquarters campus, WAN edge infrastructure, ISP connectivity, and a remote branch location.

### Core Components

| Component | Description |
|-----------|-------------|
| Headquarters | Redundant core and access switching infrastructure |
| WAN Edge | Dual enterprise edge routers |
| Service Provider | Simulated ISP infrastructure |
| Branch Office | Remote routing and switching environment |
| Infrastructure Server | Ubuntu Linux server providing DHCP, DNS, and NTP |
| Security | Layer 2 security controls and network segmentation |

### Network Topology

*Network topology diagram will be added here.*

The architecture is designed to support redundant connectivity, controlled network segmentation, and centralized infrastructure services.

---

## 3. Technologies Implemented

## Layer 2 - Enterprise Switching

- VLAN segmentation and IEEE 802.1Q trunking
- Multiple Spanning Tree (MST)
- EtherChannel
- DHCP Snooping
- Dynamic Arp Inspection (DAI)
- Port Security

## Layer 3 - Enterprise Routing

- Open Shortest Path First (OSPF)
- Border Gateway Protocol (BGP)
- Inter-VLAN routing
- IP SLA and object tracking

## WAN and Network Security

- Enterprise WAN edge architecture
- IKEv2 and IPsec configuration
- WAN redundancy and failover design

## Network Infrastructure Services

- Kea DHCP
- BIND9 DNS
- Chrony NTP
- Linux server administration

---
## 4. Design Documentation

This repository contains High-Level Design (HLD) and Low-Level Design (LLD) documenting covering the enterprise network architecture.

| Document | Description |
|----------|-------------|
| HLD-001 | Enterprise Network Archetecture|
| LLD-001 | Physical and Logical Topology |
| LLD-002 | Campus Switching and VLAN design |
| LLD-003 | Enterprise Routing - OSPF and BGP |
| LLD-004 | WAN Connectivity and VPN Architecture | 
| LLD-005 | Infrastructure Services |
| LLD-006 | Network Security |
| LLD-007 | High Availability and Failover |

Documentation will be published incrementally as each section is completed and validates

---

## 5. Networ Valdidation and Testing

The Project includes operational verification and troubleshooting procedures to demonstrate network functionality

Validation areas include:

- OSPF neighbor adjacency and routing table verification
- BGP peering and route advertisement verification
- MST root bridge and topology verification
- EtherChannel operational status
- DHCP address assignment and DNS resolution
- WAN connectivity and failover testing
- Network security feature verification

Test evidence and results will be added as validation is completed.

---

## 6. Design Decisions

A primary objective of this project is to demonstrate the reasoning behind architectural and configuration decisions.

Examples include:

- Distributing MST root bridge responsibilities across redundant core switches.
- Using OSPF for internal enterprise routing.
- Using BGP for external routing and WNA connectivity.
- Implementing centeralized infrastructure services.
- Applying Layer 2 security mechanisms to access-layer switching.
- Designing for resilience through redundant infrastructure and path selection.

Detailed explanation are provided within the corresponding LLD documents.

---

## 7. Project Status

Status: Active - Documentation and Validation

The initial network architecture and major protocol copnfigurations have been developed. Current work focuses on formal design documentation, operational verification,
and testing

Planned enhancements and incomplete implemetations will be documented separately from verified functionality

---

## 8. Lab Enviroment

- **Platform**: Cisco Modeling Labs(CML)
- **Network OS**: Cisco IOS / IOS XE (depending on node)
- **Server OS**: Ubuntu Linux and Alpine Linux
- **Diagramming**: Draw.io
- **Version Control**: Git Hub

---

## 9. Disclaimer

This project is an independently developed educational network engineering lab.

All network infrastructure is simulated, and the configurations are intended for learning, testing, and
portfollio demonstration purposes. The enviroment does not represent a producion deployment.

---
**PROJECT FOCUS**: Enterprise Network engineering | Network Architecture | Routing & Switching | Network Security | High Availability
