
# Lidarr Media Management Server Documentation

## 📄 Overview

The Lidarr service is deployed as a dedicated container within the homelab environment, utilizing the lightweight and efficient LXC virtualization technology. It runs on a Debian operating system, providing an isolated, streamlined, and highly stable environment for hosting critical media management functionalities.

This container is managed directly by the underlying Proxmox infrastructure, ensuring effective resource isolation and optimized utilization of host resources.

### System Resources and Isolation

The container is allocated specific hardware resources to ensure stable operation and performance, adhering to best practices for virtualization:

*   **Memory (RAM):** 1024 MB
*   **CPU Cores:** 2
*   **Disk Space:** 23.54 GB

This configuration ensures that the Lidarr application and its dependencies are securely isolated, contributing to an efficient and stable homelab setup.

## ⚙️ Functionality

Lidarr functions as a centralized media management solution, automating and streamlining the process of organizing, indexing, and tracking personal media libraries. Its core purpose is to automate the location, sorting, and management of media files sourced from diverse networks.

### Media Acquisition Workflow

The container is configured to support diverse media acquisition methods, enabling comprehensive management of assets sourced through various protocols:

*   **Protocol Integration:** Supports integration with both torrent and usenet acquisition protocols.
*   **Workflow Automation:** Facilitates the integration of media acquisition and organization workflows, consolidating diverse Peer-to-Peer (P2P) and usenet sources into a single, centralized management system.

## 📊 Technical Specifications

| Attribute | Value | Description |
| :--- | :--- | :--- |
| **Service** | Lidarr | Centralized media management system |
| **Virtualization** | LXC / Proxmox | Containerized environment |
| **Operating System** | Debian | Base Operating System for the container |
| **Proxmox ID (VMID)** | 127 | Identifier within the Proxmox environment |
| **Network Address** | DHCP | Dynamically assigned IP address |
| **Status** | Running | Service is currently operational |
| **Allocated RAM** | 1024 MB | Allocated memory for the container |
| **CPU Cores** | 2 | Allocated CPU resources |
| **Disk Space** | 23.54 GB | Allocated disk partition |
| **Tags** | `arr`, `community-script`, `torrent`, `usenet` | System categorization and metadata |