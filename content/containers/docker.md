---
title: "docker"
vmid: "119"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This LXC container, named "docker," serves as a foundational environment within the homelab, running a Debian operating system. Allocated 4096 MB of RAM and 3 CPU cores, it utilizes 136.74 GB of disk space. This setup provides a stable, dedicated operating system base specifically configured to host containerized applications, making it the central platform for managing various services and projects within the environment.

Given its explicit tagging with "docker" and "community-script," the primary role of this container is to act as the core engine for deploying and managing Docker-based services. It likely runs various automated scripts or community-developed tools, facilitating the setup, execution, and isolation of services. Furthermore, the inclusion of the "tailscale" tag indicates that this container is also leveraged for secure, private networking and access management across the homelab infrastructure.

## Resources
- **VMID:** 119
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 4096 MB
- **Disk:** 136.74 GB
- **Cores:** 3
- **Node:** pve
- **Tags:** community-script, docker, tailscale
