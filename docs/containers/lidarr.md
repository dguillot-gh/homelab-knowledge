
# Lidarr Media Management Server

## 📄 Overview

The Lidarr service is deployed as a dedicated container within the homelab environment, leveraging the lightweight and efficient LXC virtualization technology. It operates on a Debian operating system, providing an isolated and streamlined environment for hosting critical media management functionalities. This container is managed directly by the underlying Proxmox infrastructure, ensuring effective resource isolation and optimized utilization of host resources.

### System Configuration

The container is allocated specific hardware resources to ensure stable operation and performance:

*   **Memory (RAM):** 1024 MB
*   **CPU Cores:** 2
*   **Disk Space:** 23.54 GB

This configuration ensures that the media application and its dependencies are securely isolated, contributing to a highly efficient and stable homelab setup.

## ⚙️ Functionality

Lidarr serves as a centralized media management solution, designed to automate and streamline the process of organizing, indexing, and tracking personal media libraries. Its core function is to automate the process of locating, sorting, and managing media files sourced from various networks.

### Media Acquisition Workflow

The container is specifically configured to integrate diverse media acquisition methods, enabling comprehensive management of assets sourced through various protocols:

*   **Protocol Integration:** Supports integration with both torrent and usenet acquisition protocols.
*   **Automation:** Facilitates the integration of media acquisition and organization workflows, consolidating diverse P2P and usenet sources into a single, centralized system.

## 📊 Technical Specifications

| Attribute | Value | Notes |
| :--- | :--- | :--- |
| **Service** | Lidarr | Centralized media management system |
| **Virtualization** | LXC / Proxmox | Containerized environment |
| **Operating System** | Debian | Base OS for the container |
| **VMID** | 127 | Proxmox Virtual Machine ID |
| **IP Address** | DHCP | Dynamically assigned IP address |
| **Status** | Running | Service is currently operational |
| **Memory (RAM)** | 1024 MB | Allocated memory for the container |
| **CPU Cores** | 2 | Allocated CPU resources |
| **Disk Space** | 23.54 GB | Allocated disk partition |
| **Tags** | `arr`, `community-script`, `torrent`, `usenet` | Categorization for management |