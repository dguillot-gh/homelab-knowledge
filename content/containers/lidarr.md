---
title: "lidarr"
vmid: "127"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The lidarr container, running as an LXC with Debian as its operating system, serves as a dedicated media management service within the homelab environment. Allocated 1024 MB of RAM and two CPU cores, this container utilizes a specific disk partition of 23.54 GB to host its operations. This setup demonstrates effective resource utilization, isolating the media application and its dependencies into a lightweight, efficient container environment managed by the underlying Proxmox infrastructure.

Functionally, this container is deployed to manage and organize media assets. Given its associated tags, including torrent and usenet, the lidarr instance is primarily responsible for indexing, organizing, and tracking media files sourced from various networks. Its role is crucial for automating the process of finding, sorting, and managing a personal media library, integrating P2P and usenet acquisition methods into a centralized, automated system within the homelab.

## Resources
- **VMID:** 127
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 23.54 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** arr, community-script, torrent, usenet
