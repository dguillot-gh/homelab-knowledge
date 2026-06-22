
# databasus

This document provides detailed specifications and operational information for the `databasus` container, a dedicated PostgreSQL database server deployed within the homelab environment.

## Overview

The `databasus` container is configured to host a self-contained PostgreSQL database instance. It is deployed using containerization technology (LXC) based on a Debian operating system, ensuring strong isolation and simplified management of core data services.

The primary objective of this setup is to provide a robust, isolated database service. This container is provisioned and managed utilizing community-developed setup scripts, facilitating streamlined deployment, maintenance, and the integration of automated backup strategies within the overall homelab infrastructure. By isolating the database workload, this setup ensures critical data services are efficiently organized alongside other homelab services (such as backup and storage).

## Container Specifications

### General Information

| Attribute | Detail |
| :--- | :--- |
| **Name** | `databasus` |
| **Virtual Machine ID (VMID)** | 116 |
| **Host Node** | pve |
| **Status** | running |
| **IP Address** | dhcp |
| **Last Updated** | 2026-06-18 14:07 UTC |
| **Container Type** | docs |

### Resource Allocation

This section details the allocated hardware resources for the container instance.

| Resource | Specification |
| :--- | :--- |
| **Operating System** | Debian |
| **Memory (RAM)** | 2048 MB (2 GB) |
| **CPU Cores** | 2 |
| **Disk Space** | 7.78 GB |

### Deployment Tags

The following tags are associated with the container, indicating its functional role, deployment methodology, and associated services:

*   `backup`
*   `community-script`
*   `database`
*   `postgresql`