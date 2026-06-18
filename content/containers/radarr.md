---
title: "radarr"
vmid: "102"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This LXC container, named radarr, serves as a dedicated service within the homelab environment, running on a Debian operating system. Configured with 1024 MB of RAM and 2 CPU cores, the container utilizes a 13.68 GB disk space to host its applications. It is currently running and is assigned an IP address via DHCP, integrating seamlessly into the network infrastructure. The container is categorized with tags such as arr-stack and community-script, indicating it is part of a curated set of automated media management tools deployed for ease of system configuration.

The primary function of this container is to operate Radarr, a popular application used for organizing and managing movies and TV shows. In the context of the homelab, Radarr acts as the central indexer, monitoring media sources and ensuring that collections of films and television series are properly organized and ready for consumption. This service is crucial for automating media management, freeing up manual effort and establishing a robust, automated media library within the personal network.

## Resources
- **VMID:** 102
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 13.68 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** arr-stack, community-script
