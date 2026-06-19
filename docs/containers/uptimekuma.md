
---
title: "Uptime Kuma Monitoring Service"
vmid: "109"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "monitoring_service"
---

## Overview

The Uptime Kuma container (VMID 109) is deployed as a dedicated monitoring service within the homelab environment. This container serves the crucial function of providing a centralized, visually accessible dashboard for tracking the real-time status and availability of various services across the network infrastructure. By hosting the Uptime Kuma application, it facilitates proactive infrastructure maintenance and ensures the stability of the entire homelab setup.

The deployment leverages a lean and efficient virtualization approach, utilizing LXC technology on the Proxmox VE (PVE) node for optimal resource sharing.

## Technical Specifications

| Attribute | Detail |
| :--- | :--- |
| **VMID** | 109 |
| **Status** | Running |
| **Node** | pve |
| **Operating System** | Debian |
| **Resource Allocation** | 1 CPU Core |
| **Memory (RAM)** | 1024 MB |
| **Disk Space** | 11.73 GB |
| **IP Address** | DHCP |
| **Tags** | community-script, monitoring |

## Deployment Details

The container is built upon a lightweight Debian operating system to minimize overhead. The allocated resources are carefully balanced to ensure the application functions efficiently while maintaining minimal impact on the host system. The assigned disk space provides sufficient capacity for the Uptime Kuma application binaries and the storage of historical monitoring data.