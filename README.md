##ENRTERPRISE NETWORK ARCHITECTURE & ENGINEERING LAB##

Cisco Modeling Labs(CML) | Enterprise Routing | Switching | WAN | Network Security

1. Project Overview

This Repository documents the design, implementation, and validation of a simulated enterprise network built using Cisco Modeling Labs(CML)

The project is intended to demonstrate practical network engineering skills through the development of a multi-site enterprise enviroment
incorporating redundant infrastructure, dynamic routing, network segmentation, WAN connectivity, security controls, and centralized network services.

Rather than focusing soley on individual protocol configurations, the project emphasizes network architecture, design decissions, operational resilience,
troubleshooting, and technical documentation.

Project Objectives
-Design a scalable, multi-site enterprise network architecture.
-Implement redundant campus switching and routing infrastructure.
-Configure and validate enterpriise routing protocols.
-Develope secure WAN connectivity between geographically seperated sites.
-Implement network segmentation and access-layer security.
-Deploy centralized network infrastructure services.
-Document technical design decisions and operational procedures.
-Validate network behavior under normal failure conditions.

2. Network Architecture

The simulated enterprise enviroment consists of a headquarters campus, WAN edge infrastructure, ISP connectivity, and a remote branch location.

CORE COMPONENTS
COMPONENT                            DESCRIPTION
----------------------------------------------------------------------------------------
Headquarters                         Redundant core and access switching infrastructure.
WAN Edge                             Dual enterprise edge routers.
Service Provider                     Simulated ISP infrastructure.
Branch Office                        Remote routing and switching enviroment.
Infrastructure Server                Ubuntu Linux server provifing DHCP, DNS, and NTP.
Security                             Layer 2 security controls and network segmentation.

Network Topology
[INTSERT HERE]

The architecture is designed to support redundant connectivity, controlled network segmentation, and centeralized infrastructure services.

3. TECHNOLOGIES IMPLEMENTED
