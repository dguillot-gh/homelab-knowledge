---
title: "gitea-mirror"
vmid: "107"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This LXC container, named gitea-mirror, is a Debian-based environment deployed within the homelab infrastructure. It is configured with 2GB of RAM, 2 CPU cores, and approximately 5.82 GB of storage, providing sufficient resources to run specialized services. The container is utilized to host a synchronization service, leveraging community scripts to manage the mirroring process.

The primary function of the gitea-mirror container is to act as a redundant mirror for a Gitea instance. Its role in the homelab is to create a synchronized, read-only copy of Git repositories, ensuring data redundancy and accessibility. This setup allows the homelab owner to maintain synchronized backups or alternative access points for code repositories, enhancing the overall reliability and availability of the self-hosted services.

## Resources
- **VMID:** 107
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 2048 MB
- **Disk:** 5.82 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** community-script, gitea, mirror
