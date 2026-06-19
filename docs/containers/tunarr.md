
# Tunarr IPTV Media Server (LXC)

## Overview

This documentation details the configuration and purpose of the Tunarr container, deployed as an LXC instance within the homelab environment. This setup utilizes lightweight virtualization to host the Tunarr application, serving as a centralized IPTV media server.

### Container Specifications

| Attribute | Value | Notes |
| :--- | :--- | :--- |
| **Title** | tunarr | Application/Container Name |
| **LXC ID (VMID)** | 125 | Proxmox Virtual Environment ID |
| **Host Node** | pve | Proxmox Host System |
| **Status** | Running | Current operational state |
| **IP Address** | DHCP | Assigned dynamically via DHCP |
| **OS** | Debian | Container Operating System |
| **Resource Allocation** | | |
| RAM | 2 GB (2048 MB) | Allocated memory |
| CPU Cores | 3 | Allocated processing units |
| Disk Space | 4.84 GB | Allocated storage |
| **Last Updated** | 2026-06-18 14:07 UTC | Documentation revision date |
| **Tags** | `community-script`, `iptv` | Categorization |

## Functional Description

The primary function of this LXC container is to host and manage the Tunarr application, establishing a centralized IPTV media server for the homelab.

### Role and Purpose

The Tunarr container aggregates and organizes various IPTV streams, providing a unified media backbone for television content. This setup facilitates centralized management and smooth distribution of streaming services across the home network.

By operating as an isolated LXC instance, the configuration leverages virtualization techniques to ensure resource efficiency and service isolation while maintaining a manageable footprint within the Proxmox environment.

### System Functionality

1.  **Centralized Aggregation:** The container runs the Tunarr utility, which is responsible for indexing, managing, and organizing disparate IPTV streams.
2.  **Media Distribution:** It acts as a media server, making the aggregated television content accessible to other devices and clients within the homelab network.
3.  **Resource Efficiency:** The use of LXC virtualization allows the Tunarr service to operate efficiently by utilizing only 2 GB of RAM and 3 CPU cores, optimizing resource usage on the Proxmox host.