
# Homelab Infrastructure Documentation

**Status:** Auto-generated
**Last Updated:** 2026-06-18

## Infrastructure Overview

This document provides an inventory and navigation structure for the self-hosted homelab infrastructure, primarily managed using Proxmox Virtual Environment (PVE) and Linux Containers (LXC).

### Current Resource Inventory

The following table summarizes the current state of the virtualized resources:

| Resource Type | Count | Notes |
| :--- | :--- | :--- |
| **Proxmox Nodes (VM Hosts)** | 1 | Primary virtualization host. |
| **LXC Containers** | 28 | Linux Containers running on the Proxmox host. |

## Documentation Navigation

The complete documentation is organized into the following sectional directories:

*   [Nodes Documentation](./nodes/index.md)
    *   *Details information regarding Proxmox virtualization hosts and configuration.*
*   [Containers Documentation](./containers/index.md)
    *   *Details information regarding all running LXC Containers and their configurations.*