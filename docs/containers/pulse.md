
---
title: "pulse" Container Documentation
vmid: "123"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

# Pulse Container: Infrastructure Execution Environment

The `pulse` container is a specialized, lightweight Linux Container (LXC) provisioned within the homelab environment. It is specifically engineered to serve as a dedicated, resource-efficient execution environment for managing and executing specialized infrastructure tasks and monitoring agents.

## Overview

This container is not designed for general-purpose server duties, but rather functions as a specialized agent responsible for executing community-developed scripts and leveraging Proxmox management tools. Its architecture prioritizes maximum resource efficiency and seamless integration into the overall homelab operational workflow.

## Technical Specifications

The following table details the precise configuration and resource allocation of the `pulse` container.

| Attribute | Value | Detail |
| :--- | :--- | :--- |
| **Container ID (VMID)** | 123 | Unique identifier within the Proxmox virtualization environment. |
| **Host Node** | pve | The physical or virtual host machine location. |
| **Operational Status** | running | Current operational state of the container. |
| **Base Operating System** | Debian | The underlying Linux distribution. |
| **Memory Allocation** | 1024 MB | Dedicated system memory (RAM). |
| **CPU Allocation** | 1 Core | Allocated processing core. |
| **Disk Utilization** | ~3.86 GB | Total utilized disk space within the container. |
| **Network Configuration** | DHCP | Dynamic IP assignment via the local network DHCP server. |
| **Assigned Tags** | community-script, monitoring, proxmox | Functional roles assigned for infrastructure management. |

## Functional Role

The primary function of the `pulse` container is to act as a dedicated execution engine for advanced homelab operations. Its defined role is to facilitate the oversight and management of the broader infrastructure through specialized execution.

By assigning tags such as `community-script`, `monitoring`, and `proxmox`, the container is positioned as an execution environment responsible for running specific scripts and utilizing Proxmox management tools, thereby serving as an integrated monitoring and task execution agent.