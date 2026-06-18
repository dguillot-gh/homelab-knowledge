---
title: "sonarr"
vmid: "101"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This LXC container, named sonarr, serves as a dedicated media management service running on a Debian operating system within the homelab environment. The container is provisioned with 1024 MB of RAM and 2 CPU cores, providing adequate resources for its automated operations. It utilizes a dynamically assigned IP address and a dedicated disk space of 3.86 GB, ensuring stable operation. The container is tagged with arr-stack and community-script, indicating it is deployed using community scripts and is part of an automated media stack.

Sonarr is a core component of the homelab's media server infrastructure, specializing in the automated organization of digital content. Its primary role is to monitor various indexers and download clients, automatically sorting and organizing downloaded movies and television shows into a central library. By running Sonarr in a container, the setup ensures that this essential automation task is isolated, manageable, and efficiently deployed, acting as a critical automation script for managing media consumption within the homelab.

## Resources
- **VMID:** 101
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 3.86 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** arr-stack, community-script
