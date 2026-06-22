
# Homelab Infrastructure Documentation

**Status:** Auto-generated
**Last Updated:** 2026-06-18

## 1. Infrastructure Overview

This document serves as the central repository for the inventory, configuration, and operational details of the self-hosted homelab infrastructure. The environment is primarily managed through the Proxmox Virtual Environment (PVE) hypervisor, utilizing Linux Containers (LXC) for workload distribution and isolation.

### 1.1 Resource Inventory

The following table summarizes the current state and allocation of the virtualized resources within the homelab environment:

| Resource Type | Count | Description |
| :--- | :--- | :--- |
| **Proxmox Nodes (VM Hosts)** | 1 | Primary virtualization host managing all workloads. |
| **LXC Containers** | 28 | Linux Containers provisioned and running on the Proxmox host. |

## 2. Documentation Navigation

The full documentation is organized into two primary sectional directories, providing detailed information on the virtualization hosts and containerized workloads.

*   [Nodes Documentation](./nodes/index.md)
    *   Details configuration, operational status, and settings for all Proxmox virtualization hosts.
*   [Containers Documentation](./containers/index.md)
    *   Provides detailed specifications, configuration files, and operational status for all running LXC Containers.