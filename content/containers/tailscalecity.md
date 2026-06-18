---
title: "tailscalecity"
vmid: "114"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The container named tailscalecity is a Debian-based LXC running in the homelab environment. It functions as a foundational system, utilizing minimal resources (1 GB RAM and 1 core) to host specific services or tools defined by community scripts. The inclusion of the tailscale tag indicates that this container is primarily configured for secure, mesh networking, allowing access to the homelab resources securely and privately via the tailscale network overlay.

This container's role in the homelab is centered on providing an easily deployable and secure platform for specific tasks. By leveraging community scripts, it streamlines the setup process, allowing the administrator to quickly spin up a lightweight Debian environment ready for specialized functions. Essentially, it serves as a foundational, secure node for running targeted applications while integrating seamlessly into the broader, secure network infrastructure of the homelab.

## Resources
- **VMID:** 114
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 9.75 GB
- **Cores:** 1
- **Node:** pve
- **Tags:** community-script, os, tailscale
