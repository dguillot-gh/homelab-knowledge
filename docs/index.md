
# Homelab Infrastructure Documentation

**Document Scope:** This document serves as the centralized inventory, configuration specifications, and operational details for the self-hosted homelab infrastructure.

**Status:** Auto-generated
**Last Updated:** 2026-06-18

## 1. Infrastructure Overview

The homelab environment is built upon a virtualization framework designed for efficient resource allocation, isolation, and workload management. The architecture is primarily managed by the Proxmox Virtual Environment (PVE) hypervisor, utilizing Linux Containers (LXC) for workload distribution and isolation at the operating system level.

### 1.1 System Architecture

| Component | Role | Description |
| :--- | :--- | :--- |
| **Proxmox Host** | Hypervisor/Host | The primary physical machine running the virtualization layer and managing all workloads. |
| **LXC Containers** | Workload Isolation | Isolated Linux containers provisioned and running directly on the Proxmox host, ensuring minimal overhead and strong isolation. |

### 1.2 Resource Inventory

The following table summarizes the current state and allocation of the virtualized resources within the homelab environment:

| Resource Type | Count | Description |
| :--- | :--- | :--- |
| **Proxmox Nodes (VM Hosts)** | 1 | Primary virtualization host managing the entire infrastructure. |
| **LXC Containers** | 28 | Provisioned and operational Linux Containers running within the environment. |

## 2. Documentation Navigation

This documentation is structured into two primary sectional directories, providing detailed, granular information on the virtualization hosts and the containerized workloads.

*   [Nodes Documentation](./nodes/index.md)
    *   Details the configuration, operational status, hardware settings, and networking configurations for all Proxmox virtualization hosts.
*   [Containers Documentation](./containers/index.md)
    *   Provides detailed specifications, configuration files, volume mappings, resource allocations, and operational status for all running LXC Containers.