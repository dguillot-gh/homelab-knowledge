---
title: "tunarr"
vmid: "125"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The tunarr LXC is a Debian-based container running within the homelab environment, utilizing 2 GB of RAM and 3 CPU cores. This container is specifically provisioned to host the Tunarr application, a well-known media server utility. The configuration suggests a resource-efficient setup, leveraging the LXC virtualization to isolate the services while keeping the footprint manageable within the Proxmox environment.

The primary role of this container is to function as a centralized IPTV media server. By running Tunarr, this LXC aggregates various IPTV streams, organizes them, and makes them accessible to other devices or clients within the homelab. This setup allows for the centralized management and smooth distribution of television content, serving as a dedicated media backbone for streaming services within the home network.

## Resources
- **VMID:** 125
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 2024 MB
- **Disk:** 4.84 GB
- **Cores:** 3
- **Node:** pve
- **Tags:** community-script, iptv
