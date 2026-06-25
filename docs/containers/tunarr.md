
# Tunarr IPTV Media Server Deployment (LXC)

## 1. Overview

This document provides comprehensive details regarding the deployment, configuration, and operational role of the Tunarr application hosted within a Linux Container (LXC) instance on the homelab infrastructure. This architecture leverages lightweight containerization to provide a centralized, isolated, and highly resource-efficient IPTV media server solution.

### 1.1 Architecture Philosophy

The choice of an LXC container facilitates a modular deployment strategy. This isolation ensures that the IPTV service is compartmentalized, enhancing security, simplifying backup and snapshot operations, and optimizing overall resource utilization on the Proxmox host system.

## 2. Container Specifications

The following table details the technical specifications and environmental context of the Tunarr LXC container.

| Attribute | Value | Description |
| :--- | :--- | :--- |
| **Application Name** | `tunarr` | Internal identifier for the application and container. |
| **Host System** | `pve` | The underlying Proxmox Virtual Environment host. |
| **LXC ID (VMID)** | `125` | Proxmox Virtual Environment Identifier. |
| **Operational Status** | `Running` | Current operational state of the container. |
| **Operating System** | Debian | Container operating system distribution. |
| **Network Configuration** | DHCP | IP address is dynamically assigned via DHCP. |
| **Resource Allocation** | | Allocated hardware resources for the container. |
| RAM | 2 GB (2048 MB) | Allocated physical memory. |
| CPU Cores | 3 | Allocated processing units. |
| Disk Space | 4.84 GB | Allocated storage volume for the container's root filesystem. |
| **Documentation Version** | 1.0 | Current revision date. |
| **Tags** | `community-script`, `iptv` | Categorization for asset management and indexing. |

## 3. Functional Description

The primary function of this LXC container is to establish a dedicated, centralized platform for the aggregation, indexing, and distribution of IPTV media streams across the homelab network.

### 3.1 Role and Purpose

The Tunarr container serves as the core IPTV media server, performing the following critical functions:

1.  **Centralized Aggregation:** The Tunarr application indexes and aggregates disparate IPTV sources (e.g., M3U playlists, Xtream Codes feeds), creating a unified, searchable catalog of available television content.
2.  **Media Distribution:** The container acts as a dedicated media server, managing the indexing data and distributing aggregated content to client devices and other services connected within the local network.
3.  **Resource Optimization:** By operating within the lightweight LXC virtualization environment, the service effectively utilizes only 2 GB of RAM and 3 CPU cores, ensuring minimal overhead and optimal resource allocation for the Proxmox host system.

### 3.2 Deployment Context

Implementing the Tunarr service within an LXC container provides a highly manageable and secure deployment strategy. This modular approach ensures that the IPTV service is fully isolated from the host operating system, allowing for streamlined management practices, including easy snapshotting, rolling backups, and granular access control, aligning with best practices for homelab virtualization environments.