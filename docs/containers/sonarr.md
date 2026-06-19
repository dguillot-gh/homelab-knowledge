
---
title: "Sonarr Media Management Container"
vmid: "101"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

## Overview

This document describes the deployment and configuration details for the Sonarr media management service, deployed within an LXC container in the homelab environment. Sonarr is a critical component of the centralized media server infrastructure, responsible for the automated organization and management of digital media content.

The container utilizes a Debian operating system and is designed to isolate and efficiently run essential automation tasks. This containerization approach ensures that the Sonarr service is manageable, scalable, and easily integrated into the overall homelab automation stack.

## Container Specifications

The Sonarr container is provisioned with the following resource allocation and system details:

| Attribute | Value | Description |
| :--- | :--- | :--- |
| **VMID** | 101 | Virtual Machine ID |
| **Node** | pve | Host system |
| **Status** | running | Current operational state |
| **IP Address** | dhcp | Dynamically assigned IP |
| **Operating System** | Debian | Base OS distribution |
| **RAM** | 1024 MB | Allocated system memory |
| **CPU Cores** | 2 | Allocated processing cores |
| **Disk Space** | 3.86 GB | Dedicated storage volume |
| **Tags** | arr-stack, community-script | Deployment and stack categorization |

## Functionality

Sonarr operates as an automated media organization tool. Its primary functions include:

1.  **Monitoring:** Continuously monitors configured indexers and download clients for new content.
2.  **Organization:** Automatically sorts and organizes downloaded movies and television shows based on predefined rules.
3.  **Library Management:** Integrates downloaded content into a centralized, manageable media library.

By running Sonarr in a container, the homelab achieves a robust and isolated solution for managing media consumption, acting as a core automation script for the entire media stack.