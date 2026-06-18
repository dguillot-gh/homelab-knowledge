---
title: "gitea"
vmid: "103"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This container, named gitea, is a lightweight Linux container utilizing a Debian operating system, provisioned within a homelab environment. It is configured with 1024 MB of RAM and a single CPU core, allocating 7.78 GB of disk space. This setup demonstrates efficient resource management, utilizing the LXC technology to host a specific application service in a containerized format, ensuring minimal overhead while providing a dedicated execution environment for the service.

Based on its name and associated tags, the gitea container is clearly set up to run the Gitea application, which functions as a self-hosted Git repository and collaboration platform. Its role within the homelab is to serve as a central source control management system, allowing the user to host private code repositories, manage projects, and facilitate collaborative development entirely within the private network infrastructure. The inclusion of the git tag further confirms its core function as a dedicated Git service.

## Resources
- **VMID:** 103
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 7.78 GB
- **Cores:** 1
- **Node:** pve
- **Tags:** community-script, git
