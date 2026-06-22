
# homelable System Documentation

## Overview

The `homelable` container is an LXC instance deployed within the homelab environment. It serves as a dedicated, lightweight platform designed for specialized system operations, scripting workflows, and the deployment of essential services.

Built upon a stable Debian base, this container is optimized for stability and efficiency, leveraging the open-source nature of Debian and integration with community-driven tools.

Functionally, `homelable` acts as a centralized hub for monitoring, network management, and data visualization across the entire homelab infrastructure. It facilitates the execution of community scripting workflows, allowing users to easily track system metrics, network performance, and the operational status of various services running on the host system.

## System Specifications

The following details outline the current status, hardware allocation, and location of the container.

### General Details

| Attribute | Value |
| :--- | :--- |
| **Container Name** | `homelable` |
| **VMID** | 113 |
| **Host Node** | pve |
| **Operating System** | Debian |
| **Container Type** | LXC |
| **Status** | Running |
| **IP Address** | DHCP |
| **Last Updated** | 2026-06-18 14:07 UTC |

### Hardware Allocation

| Specification | Value |
| :--- | :--- |
| **RAM** | 2048 MB |
| **CPU Cores** | 2 |
| **Disk Space** | 7.78 GB |

## Deployment Tags

The container is categorized by its primary functional roles, facilitating easy identification of its purpose:

*   `community-script`
*   `monitoring`
*   `network`
*   `visualization`