
```markdown
# Docker Host Container Documentation

## Overview
This LXC container, named `docker`, serves as the foundational platform for containerized services and automated tooling within the homelab environment. It operates on a dedicated Debian operating system, providing a stable and isolated environment specifically designed for hosting and managing Docker-based applications and infrastructure services.

## Container Specifications

| Attribute | Value | Details |
| :--- | :--- | :--- |
| **VMID** | 119 | Unique identifier for the virtual machine. |
| **Node** | pve | Host system. |
| **Status** | running | Current operational state. |
| **IP Address** | dhcp | Dynamically assigned IP address. |
| **OS** | Debian | Operating System running within the container. |
| **RAM** | 4096 MB | Allocated memory. |
| **CPU Cores** | 3 | Allocated processing cores. |
| **Disk Space** | 136.74 GB | Total allocated disk space. |
| **Last Updated** | 2026-06-18 14:07 UTC | Timestamp of the last documented update. |

## Role and Functionality
The `docker` container is explicitly configured to function as the core engine for managing containerized services and secure networking within the homelab infrastructure.

### Primary Functions
1.  **Container Orchestration:** Serves as the primary host environment for deploying, running, and managing Docker containers.
2.  **Script Execution:** Functions as a dedicated environment for executing community-developed scripts and automation tools.
3.  **Secure Networking:** Leverages networking tools (indicated by the `tailscale` tag) to establish secure, private network access and identity management across the homelab.

### Tags
*   `docker`: Designates the container's core function as a Docker environment.
*   `community-script`: Indicates the container hosts automated scripts or community tools.
*   `tailscale`: Identifies the container's role in providing secure network connectivity.
```