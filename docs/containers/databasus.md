
# databasus: PostgreSQL Container Documentation

This document provides detailed specifications and operational information for the `databasus` container, which hosts a dedicated PostgreSQL database server within the homelab environment.

## Overview

The `databasus` container serves as an isolated instance for running a PostgreSQL database. It is deployed using Linux Containers (LXC) based on a Debian operating system, which ensures strong isolation, streamlined management, and efficient integration into the overall homelab infrastructure.

The primary objective of this setup is to provide a robust, isolated database service. By containerizing the database workload, this configuration facilitates simplified deployment, maintenance, and the integration of automated backup strategies, allowing critical data services to be organized alongside other homelab services (such as backup and storage).

## Container Specifications

### General Information

| Attribute | Detail |
| :--- | :--- |
| **Name** | `databasus` |
| **Host Node** | `pve` |
| **Virtual Machine ID (VMID)** | 116 |
| **Status** | running |
| **IP Address** | DHCP |
| **Last Updated** | 2026-06-18 14:07 UTC |
| **Container Type** | docs |

### Resource Allocation

The following section details the allocated hardware resources for the container instance.

| Resource | Specification |
| :--- | :--- |
| **Operating System** | Debian |
| **Memory (RAM)** | 2048 MB (2 GB) |
| **CPU Cores** | 2 |
| **Disk Space** | 7.78 GB |

### Deployment Tags

The following tags are associated with the container, indicating its functional role and deployment methodology:

*   `backup`
*   `community-script`
*   `database`
*   `postgresql`