---
title: "prowlarr"
vmid: "104"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This LXC container, named prowlarr, serves as a dedicated environment for running specialized media management services within the homelab infrastructure. It is provisioned on a Debian operating system, utilizing 1024 MB of RAM and two CPU cores, providing sufficient resources for its intended operations. The container is running successfully and is configured to obtain its network address via DHCP, integrating smoothly into the existing network topology managed by the hypervisor.

Based on its naming and associated tags, prowlarr functions as a critical component in the automated management of media sources and indexing for the homelab. It is likely running an indexer application, responsible for monitoring and managing various sources (such as torrent trackers or media indexers) to facilitate the discovery and organization of media content. Its presence, tagged as part of an "arr-stack," indicates that it plays a key role in automating the upstream process of finding and tracking desired files, significantly simplifying the workflow for media consumption.

## Resources
- **VMID:** 104
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 3.86 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** arr-stack, community-script
