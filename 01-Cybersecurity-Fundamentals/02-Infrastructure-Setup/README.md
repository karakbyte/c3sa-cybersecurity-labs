# Module 02 – Infrastructure Setup

## Overview

This module focuses on setting up the cybersecurity lab environment required for practical security testing and hands-on exercises.

## Lab Environment

### Host System

- Operating System: Windows 64-bit
- Processor: Intel Core i5-10310U
- RAM: 8 GB
- Storage: 477 GB

## VMware Virtual Networks

The following virtual networks are available in VMware Workstation:

| Network | Type | Subnet |
|---|---|---|
| VMnet1 | Host-only | 192.168.56.0/24 |
| VMnet2 | Host-only | 192.168.229.0/24 |
| VMnet8 | NAT | 192.168.232.0/24 |

VMnet1 and VMnet2 provide separate private networks.
VMnet8 provides NAT networking for virtual machine internet access.

The lab network configuration is still in progress.
Connectivity will be tested after the virtual machines
are configured on the intended network.


### Virtualization Platform

- VMware Workstation Pro 26H1
- Host Platform: Windows

## Infrastructure Setup

The following components are being configured as part of the C3SA practical lab environment:

- VMware Workstation
- Security testing virtual machines
- Vulnerable lab environments
- Virtual networking
- Network connectivity between lab machines

## VMware Installation

VMware Workstation Pro 26H1 was installed successfully on the Windows host system.

## Installation Status

- [x] VMware Workstation installed
- [x] Metasploitable 2 virtual machine created
- [ ] Parrot OS setup and boot verified
- [ ] Windows 10 virtual machine setup completed
- [ ] Lab virtual networking configured
- [ ] Connectivity between lab machines tested
- [ ] Vulnerable lab environment verified

## Screenshots

Screenshots of the infrastructure setup will be added as the lab environment is configured.

## Learning Objectives

- Understand virtualization in cybersecurity labs
- Configure virtual machines
- Configure isolated lab networking
- Understand communication between security testing and vulnerable systems

## Security Note

All security testing performed in this repository is intended for authorized C3SA training labs and intentionally vulnerable environments.

No real systems, credentials, API keys, tokens, or confidential information should be included in this repository.

## Learning Status

**In Progress**

VMware Workstation has been installed, and the Metasploitable 2
virtual machine has been created.

Network configuration and connectivity testing are in progress.
Further updates will be added as the lab environment is completed.
