---
title: "homelable"
vmid: "113"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The homelable container is a Debian-based LXC instance running within the homelab environment, allocated 2048 MB of RAM and 2 CPU cores. This container serves as a dedicated platform for running specialized scripts and services, leveraging its open-source nature and integration with community tools. Its configuration indicates it is optimized for a specific functional role, providing a stable and lightweight environment for complex system operations.

This container is primarily deployed for monitoring, network management, and data visualization tasks. By leveraging its tags, homelable acts as a centralized hub for tracking system metrics and network performance across the homelab. It facilitates the deployment of community-scripting workflows, allowing users to easily manage and visualize the operational status of the network and other services running on the host system.

## Resources
- **VMID:** 113
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 2048 MB
- **Disk:** 7.78 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** community-script, monitoring, network, visualization
