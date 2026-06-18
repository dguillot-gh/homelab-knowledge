---
title: "jellyseerr"
vmid: "108"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The jellyseerr container is a Debian-based LXC running within the homelab environment, provisioned with 2048 MB of RAM and 2 CPU cores. This container utilizes a dedicated 31.2 GB disk space, providing a stable and dedicated environment for hosting specialized services. The setup is tagged with community-script, indicating it likely relies on external scripts or community configurations for its installation and operation, ensuring a streamlined deployment process for this specific application.

This container serves as a dedicated media and home automation interface within the homelab. Its primary function is to run the Jellyseerr application, which acts as a centralized control panel for managing smart home devices and media collections. By hosting this service in a lightweight LXC, it efficiently utilizes resources while providing essential functionality for managing interconnected smart home systems and media assets.

## Resources
- **VMID:** 108
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 2048 MB
- **Disk:** 31.2 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** community-script
