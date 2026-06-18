---
title: "caddy"
vmid: "118"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

This LXC container, named caddy, is deployed within the homelab environment, providing a dedicated instance for running a web server. Operating on a Debian base, the container utilizes 512 MB of RAM and approximately 19.52 GB of disk space, configured with a single CPU core. The primary application within this container is Caddy, a popular and modern web server known for automatically handling SSL/TLS certificates and providing simple, robust configuration management for HTTP traffic.

Caddy’s role in the homelab is to serve as a crucial entry point and internal service provider. Due to its configuration and associated tags, it is likely used to host internal services or expose specific project resources securely to the local network. The inclusion of tags like tailscale and community-script indicates that this setup is integrated into a more complex, networked infrastructure, leveraging secure overlay networking and community-developed scripts to manage and secure the services hosted by this container.

## Resources
- **VMID:** 118
- **Status:** running
- **IP:** dhcp
- **OS:** debian
- **RAM:** 512 MB
- **Disk:** 19.52 GB
- **Cores:** 1
- **Node:** pve
- **Tags:** community-script, tailscale, webserver
