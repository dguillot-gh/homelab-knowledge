---
title: "openwebui"
vmid: "130"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The LXC container named openwebui serves as a dedicated environment for hosting an Open WebUI instance. Running on a Debian base with significant allocated resources, including 16GB of RAM and 3 CPU cores, this container is configured to provide a stable and performant platform for running complex applications. Its configuration reflects a focus on integrating community-developed scripts, suggesting it utilizes specialized tools for its operation and setup within the homelab infrastructure.

Functionally, this container acts as a critical interface layer for interacting with large language models (LLMs) or other AI services. Its role in the homelab is to provide a centralized, user-friendly graphical interface, abstracting the complexity of the underlying AI services. By running Open WebUI, the container allows users to manage, chat with, and control various AI functionalities directly through a web-based application, enhancing the homelab's capability for local AI deployment and accessibility.

## Resources
- **VMID:** 130
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 16384 MB
- **Disk:** 58.76 GB
- **Cores:** 3
- **Node:** pve
- **Tags:** ai, community-script, interface
