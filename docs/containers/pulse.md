
---
title: "pulse"
vmid: "123"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

# Pulse Container Overview

The `pulse` container is a specialized, lightweight Virtual Machine (VM) provisioned within the homelab environment, designed for specific operational tasks rather than general-purpose server roles.

## General Description

This container operates as a Debian-based LXC, optimized for resource efficiency and integration into the overall infrastructure. Its configuration is tailored to function as a specialized agent or execution environment for homelab management tools.

## Technical Specifications

| Attribute | Value | Notes |
| :--- | :--- | :--- |
| **VMID** | 123 | Unique identifier within the Proxmox environment. |
| **Node** | pve | Host machine location. |
| **Status** | running | Current operational state. |
| **Operating System** | Debian | Base operating system. |
| **Memory (RAM)** | 1024 MB | Allocated memory. |
| **CPU Cores** | 1 | Allocated processing core. |
| **Disk Space** | ~3.86 GB | Total utilized disk space. |
| **IP Configuration** | DHCP | Dynamic IP assignment via local network. |
| **Tags** | community-script, monitoring, proxmox | Defines the intended functional role. |

## Functional Role

The `pulse` container is explicitly designated for operational functions, primarily serving as a specialized monitoring agent or a containerized execution environment. This role is indicated by its associated tags, suggesting its primary purpose is to facilitate advanced oversight and management of the broader homelab infrastructure through the execution of community-developed scripts and Proxmox tools.