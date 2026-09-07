# Secure SME Network Infrastructure (NET2201)

## Overview
This repository contains the network architecture, configuration files, and documentation for a multi-building Small-to-Medium Enterprise (SME) network project. The project transitions an organization away from an insecure flat network topology by implementing robust segmentation, redundant trunking, and hardened device controls.

## Key Contributions & Role
* **Role**: Team Leader & Network Engineer (Led a team of 4 members)
* **VLAN & IP Addressing Architecture**: Formulated the subnet allocation scheme, gateway assignments, and departmental VLAN segmentation.
* **Project Execution & Management**: Developed project roadmaps, task checklists, and timelines to ensure strict milestone adherence.
* **Implementation & Hardening**: Supervised end-to-end integration, including LACP EtherChannel trunking and SSH device hardening.
* **Troubleshooting & Verification**: Directed debugging workflows for cabling faults, encapsulation mismatches, and multi-subnet connectivity issues.

## Network Architecture Highlights
* **Routing & Switching**: Layer 3 Inter-VLAN routing (Router-on-a-Stick) utilizing Cisco routers and switches.
* **Resiliency**: LACP EtherChannel configured for link aggregation and redundancy.
* **Services**: Centralized DHCP server configuration for dynamic IP allocation across departments.
* **Security**: SSH management access configuration and port security implementation.

## Repository Contents
* `configs/`: Text files containing CLI configuration commands for routers and switches.
* `SME_Network_Architecture.pkt`: The working Cisco Packet Tracer simulation file.
