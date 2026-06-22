
# Tunarr IPTV Media Server (LXC)

## Overview

This document details the deployment, configuration, and functional role of the Tunarr application, hosted within a Linux Container (LXC) instance on the homelab infrastructure. This setup utilizes lightweight virtualization to provide a centralized, isolated, and resource-efficient IPTV media server.

### Container Specifications

The following table outlines the technical specifications and environment details of the Tunarr LXC container.

| Attribute | Value | Details |
| :--- | :--- | :--- |
| **Application Name** | `tunarr` | Internal application/container name. |
| **LXC ID (VMID)** | `125` | Proxmox Virtual Environment ID. |
| **Host System** | `pve` | Proxmox physical host system. |
| **Operational Status** | `Running` | Current operational state of the container. |
| **Network Configuration** | DHCP | IP address is dynamically assigned via DHCP. |
| **Operating System** | Debian | Container operating system distribution. |
| **Resource Allocation** | | Allocated resources for the container. |
| RAM | 2 GB (2048 MB) | Allocated physical memory. |
| CPU Cores | 3 | Allocated processing units. |
| Disk Space | 4.84 GB | Allocated storage volume. |
| **Documentation Version** | 1.0 | Current revision date. |
| **Tags** | `community-script`, `iptv` | Categorization for asset management. |

## Functional Description

The primary objective of this LXC container is to serve as a dedicated, centralized IPTV media management and distribution platform for the homelab environment.

### Role and Purpose

The Tunarr container serves as the core IPTV media server, responsible for the aggregation, indexing, and management of disparate IPTV streams. By operating within an isolated LXC environment, this setup achieves enhanced security and service isolation while optimizing resource utilization on the Proxmox host.

**Key Functions:**

1.  **Centralized Aggregation:** The Tunarr application indexes and aggregates various IPTV sources, creating a unified catalog of available television content.
2.  **Media Distribution:** The container functions as a dedicated media server, providing aggregated content to client devices and other services within the local network.
3.  **Resource Efficiency:** Leveraging the lightweight nature of LXC virtualization, the service operates efficiently using only 2 GB of RAM and 3 CPU cores, ensuring optimal resource allocation for the overall Proxmox host system.

### Deployment Context

The implementation of Tunarr within an LXC container facilitates a modular and manageable deployment strategy. This approach ensures that the IPTV service is compartmentalized, allowing for straightforward backup, snapshotting, and management, adhering to best practices for homelab virtualization.