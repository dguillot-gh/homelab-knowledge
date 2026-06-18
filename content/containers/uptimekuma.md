---
title: "uptimekuma"
vmid: "109"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The uptimekuma container, identified as VMID 109, serves as a dedicated monitoring service within the homelab environment. It is based on a lightweight Debian operating system, allocated 1024 MB of RAM and 1 CPU core, ensuring minimal resource usage while providing essential functionality. The container utilizes approximately 11.73 GB of disk space, providing ample storage for the application and its associated monitoring data. This setup demonstrates a lean and efficient approach to virtualization, leveraging LXC technology for efficient resource sharing.

Functionally, this container runs the Uptime Kuma application, a popular open-source tool designed for system monitoring. Its primary role in the homelab is to provide a centralized, visually accessible dashboard for tracking the status and availability of various services running on the network. By hosting this monitoring script, uptimekuma allows the user to easily observe the health of their infrastructure, making it crucial for proactive maintenance and ensuring the stability of the entire homelab setup.

## Resources
- **VMID:** 109
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 1024 MB
- **Disk:** 11.73 GB
- **Cores:** 1
- **Node:** pve
- **Tags:** community-script, monitoring
