---
title: "pulse"
vmid: "123"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The container named pulse, provisioned as VMID 123, serves as a dedicated lightweight system within the homelab environment. Running a Debian operating system, this LXC is configured with 1024 MB of RAM and 1 CPU core, utilizing approximately 3.86 GB of disk space. Its network configuration is dynamic, receiving an IP address via DHCP, making it easily integrated into the local network infrastructure.

This container is explicitly tagged with community-script, monitoring, and proxmox roles, indicating its primary function is operational rather than serving as a general-purpose server. Given the associated links to community scripts and Proxmox tools, pulse likely functions as a specialized monitoring agent or a containerized execution environment for running various community-developed scripts, enabling advanced oversight and management of the overall homelab infrastructure.

## Resources
- **VMID:** 123
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 3.86 GB
- **Cores:** 1
- **Node:** pve
- **Tags:** community-script, monitoring, proxmox
