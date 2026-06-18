---
title: "github-runner"
vmid: "129"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The github-runner container is an LXC instance running a Debian operating system, configured within the homelab environment. Allocated 2048 MB of RAM and 2 CPU cores, this container utilizes approximately 7.78 GB of disk space, providing sufficient resources for running complex build processes. It serves as a foundational, lightweight platform designed specifically for executing automated tasks in an isolated manner, adhering to the principles of containerization within the Proxmox VE setup.

This specific LXC is dedicated to Continuous Integration (CI) workflows, evidenced by its naming and tags. It functions as a dedicated runner for community scripts, allowing the homelab environment to autonomously pull, build, and test code directly from GitHub repositories. Its primary role is to provide a standardized, reproducible environment for automated software delivery, streamlining the development and deployment processes that are central to the homelab's functionality.

## Resources
- **VMID:** 129
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 2048 MB
- **Disk:** 7.78 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** ci, community-script
