---
title: "flaresolverr"
vmid: "105"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The flaresolverr container is a running LXC instance provisioned on a Debian operating system within the homelab environment. It utilizes 512 MB of RAM and 1 CPU core, operating with a small disk allocation of 3.86 GB. This setup demonstrates a lightweight, dedicated environment often used for running specific services or automation tools. The container is accessible via DHCP and is tagged with arr-stack and community-script, indicating its role in managing software applications and executing custom scripts for system management.

Based on its name and associated tags, the flaresolverr container likely serves as an automated utility or solver for specific infrastructure tasks. Its association with "arr-stack" suggests it is involved in setting up or managing applications that require service replication, commonly seen in containerized environments like Docker. Functioning as a community script executor, this container probably runs custom scripts to simplify complex deployment or troubleshooting processes, acting as a specialized automation engine for the homelab infrastructure.

## Resources
- **VMID:** 105
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 512 MB
- **Disk:** 3.86 GB
- **Cores:** 1
- **Node:** pve
- **Tags:** arr-stack, community-script
