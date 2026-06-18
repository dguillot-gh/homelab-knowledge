---
title: "audiobookshelf"
vmid: "121"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The audiobookshelf container, running on a Debian-based LXC environment, serves as a dedicated media server within the homelab setup. Allocated 2048 MB of RAM and 2 CPU cores, this container utilizes a modest amount of disk space (4.84 GB) to host the necessary software and media libraries. This setup demonstrates a cost-effective method of isolating a specific application, leveraging the efficiency of containerization to manage media tasks without consuming excessive resources on the host system.

The primary function of this container is to act as a central hub for managing personal audio content, specifically books and podcasts. By running the audiobookshelf application, it organizes, catalogs, and streams media files, making them accessible across the network. In the context of the homelab, this system fulfills the role of a personal media management service, allowing the user to centrally organize their library and enjoy their audio content on demand.

## Resources
- **VMID:** 121
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 2048 MB
- **Disk:** 4.84 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** audiobook, community-script, podcast
