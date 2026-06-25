
# Docker Host Container Documentation

## Overview

The `docker` container serves as the foundational operating environment for all containerized services, infrastructure management, and automated tooling within the homelab infrastructure. Hosted within an LXC container, it provides a stable, isolated, and dedicated platform specifically designed for the deployment, management, and execution of Docker-based applications and associated services.

## Container Specifications

The following table details the technical specifications and operational details of the container:

| Attribute | Value | Description |
| :--- | :--- | :--- |
| **Name** | `docker` | Internal designation of the container. |
| **VMID** | 119 | Unique identifier for the underlying Proxmox Virtual Environment instance. |
| **Host System** | `pve` | The parent Proxmox Virtual Environment host system. |
| **Status** | `running` | Current operational state of the container. |
| **IP Address** | `dhcp` | IP address assigned dynamically via DHCP. |
| **Operating System** | Debian | The operating system running within the container environment. |
| **Memory (RAM)** | 4096 MB | Allocated physical memory resources. |
| **CPU Cores** | 3 | Allocated processing cores. |
| **Disk Space** | 136.74 GB | Total allocated disk storage. |
| **Last Updated** | 2026-06-18 14:07 UTC | Timestamp of the last modification or documentation update. |

## Role and Functionality

The primary function of the `docker` container is to act as the central orchestration engine and networking hub for the entire homelab infrastructure.

### Core Functions

1.  **Container Orchestration:** Serves as the core host environment for deploying, managing, and running all Docker containers and associated services.
2.  **Automation and Scripting:** Provides a dedicated, isolated execution environment for running community-developed scripts, infrastructure management tasks, and automated tooling.
3.  **Secure Networking Hub:** Integrates networking functionalities (e.g., utilizing `tailscale`) to establish secure, private network access, identity management, and secure connectivity across the entire homelab infrastructure.

### Metadata and Tags

The following tags define the specific roles and capabilities associated with this container:

*   `docker`: Designates the container's primary role as a Docker host environment.
*   `community-script`: Indicates the container's function as a repository for automated scripts and community tools.
*   `tailscale`: Identifies the container's role in facilitating secure network communication and identity management.