---
title: "jellyfin"
vmid: "100"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This LXC container, named jellyfin, serves as a dedicated media server within the homelab environment. It is built upon a Debian operating system and is provisioned with 3072 MB of RAM and 2 CPU cores, ensuring sufficient resources for media transcoding and serving. The container utilizes dynamic DHCP addressing, integrating seamlessly into the local network structure, and is allocated 78.19 GB of disk space to store extensive media libraries and configuration files.

The primary function of this container is to host the Jellyfin application, an open-source platform for managing and streaming multimedia content. Its role in the homelab is critical for centralizing media management, allowing the user to organize, store, and stream video and audio content to various devices across the home. This setup transforms the container into a centralized media hub, making large collections easily accessible and streamable throughout the network.

## Resources
- **VMID:** 100
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 3072 MB
- **Disk:** 78.19 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** community-script, media
