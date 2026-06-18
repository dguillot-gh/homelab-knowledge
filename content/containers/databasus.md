---
title: "databasus"
vmid: "116"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The container named databasus, running on a Debian base and utilizing 2GB of RAM, serves as a dedicated database server within the homelab environment. This setup is clearly designed to host a PostgreSQL instance, as indicated by its associated tags and references to community scripts. The container is configured with 2 CPU cores and sufficient disk space to manage the necessary database files and operational data.

The primary role of the databasus container is to provide a robust, self-contained database service, likely managed and provisioned using community-developed setup scripts. By isolating the database workload into an LXC container, it facilitates easy deployment, management, and potential backup strategies within the homelab. This setup ensures that core data services are separated and easily maintained, allowing for efficient organization of services like backup and data storage.

## Resources
- **VMID:** 116
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 2048 MB
- **Disk:** 7.78 GB
- **Cores:** 2
- **Node:** pve
- **Tags:** backup, community-script, database, postgresql
