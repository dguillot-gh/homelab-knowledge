---
title: "homepage"
vmid: "117"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The container named homepage (VMID 117) serves as a key component in the homelab environment, running a Debian operating system with 4096 MB of RAM and 2 CPU cores. This setup provides a stable, lightweight platform for hosting specific services. The container is tagged with community-script and dashboard, indicating its primary function is not a general server but rather the execution of specialized software or a graphical interface.

The role of this LXC is to act as a centralized dashboard or runner for community scripts, specifically leveraging resources from projects like community-scripts.org. By hosting this container, the homelab user gains an easily accessible point of control or monitoring for various automated scripts, simplifying management and providing a cohesive overview of operational data within the Proxmox environment.

## Resources
- **VMID:** 117
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 4096 MB
- **Disk:** 5.82 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** community-script, dashboard
