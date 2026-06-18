---
title: "caddy"
vmid: 118
type: "LXC"
status: "running"
node: "pve"
cpu: 1
ram_gb: 0.5
disk_gb: 19.52
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 118 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 118 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 1 |
| **RAM** | 0.5 GB |
| **Disk** | 19.52 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Caddy is a modern, open-source web server that emphasizes simplicity and automatic security management, making it an excellent choice for managing services within a homelab environment. It functions primarily as a reverse proxy, handling incoming web traffic and automatically managing TLS/SSL certificates using protocols like Let's Encrypt. In a homelab context, Caddy serves as a centralized entry point, allowing you to easily expose internal services securely to the outside world while ensuring all traffic is encrypted.

## Purpose
Caddy’s main purpose in a homelab is to provide a robust, automated, and secure front-end for internal services. It simplifies the complex task of setting up HTTPS and reverse proxying, allowing users to focus on deploying applications rather than managing complex security certificates.

## Key Features
*   Automatic HTTPS/TLS: Caddy automatically provisions and renews SSL certificates, eliminating manual certificate management.
*   Reverse Proxying: It efficiently routes incoming web requests to the correct internal services running on other containers or VMs.
*   Simple Configuration: It uses a clean, easy-to-read configuration file that facilitates quick setup and maintenance.
*   HTTP/2 Support: Caddy natively supports modern HTTP protocols, ensuring high-performance and secure communication.

## Operational Notes
*   Ensure proper port mapping in your configuration file to allow external access to the services you are proxying.
*   Since Caddy manages TLS, monitor its logs closely for any certificate errors or failed connection attempts, as these often indicate network or service issues.
*   Leverage its ability to handle multiple sites and subdomains from a single configuration to streamline your overall network setup.

## Suggested Tags
reverse-proxy
webserver
networking
security
automation
reverse-proxy

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:3C:3D:F6,ip=dhcp,ip6=auto,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-118-disk-0,size=20G` |

> Add manual notes here.
