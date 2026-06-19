
# databasus

This document provides detailed information regarding the `databasus` container, a dedicated database server deployed within the homelab environment.

## Overview

The `databasus` container is configured to host a PostgreSQL database instance. It is implemented using a Debian base operating system and leverages containerization technology (LXC) to ensure isolation and simplified management of core data services.

The primary objective of this setup is to provide a robust, self-contained database service. This container is likely provisioned and managed using community-developed setup scripts, which facilitates easy deployment, maintenance, and integrated backup strategies within the homelab infrastructure. By isolating the database workload, it ensures that critical data services are separated and efficiently organized alongside other homelab services (e.g., backup and data storage).

## Container Specifications

| Attribute | Detail |
| :--- | :--- |
| **Name** | `databasus` |
| **Virtual Machine ID (VMID)** | 116 |
| **Node** | pve |
| **Status** | running |
| **IP Address** | dhcp |
| **Last Updated** | 2026-06-18 14:07 UTC |
| **Type** | docs |

### Hardware & Resource Allocation

| Resource | Specification |
| :--- | :--- |
| **Operating System** | Debian |
| **RAM** | 2048 MB (2 GB) |
| **CPU Cores** | 2 |
| **Disk Space** | 7.78 GB |

### Deployment Tags

The following tags are associated with this container, indicating its functional role and deployment methodology:
*   `backup`
*   `community-script`
*   `database`
*   `postgresql`