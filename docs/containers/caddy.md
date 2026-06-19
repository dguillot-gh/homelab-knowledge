
---
title: "Caddy Web Server Container"
vmid: "118"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

## Overview

This document details the configuration and role of the `caddy` LXC container deployed within the homelab environment. This container serves as a dedicated instance for hosting a modern web server, utilizing Caddy to manage HTTP traffic and automated TLS/SSL certificate handling.

## Container Description

The `caddy` container is an LXC instance running on a Debian base operating system. It is configured to provide a stable and secure entry point for internal services within the network.

Caddy is selected for this deployment due to its strengths as a robust web server, offering simplified configuration and automated management of complex security protocols, specifically SSL/TLS.

## Technical Specifications

### Resources
| Specification | Value |
| :--- | :--- |
| **VMID** | 118 |
| **Node** | pve |
| **Status** | running |
| **Operating System** | Debian |
| **Memory (RAM)** | 512 MB |
| **Disk Space** | 19.52 GB |
| **CPU Cores** | 1 |
| **IP Address** | dhcp |
| **Tags** | community-script, tailscale, webserver |

## Operational Role

The `caddy` container functions as a critical service provider within the homelab infrastructure. Its deployment is designed to facilitate secure internal networking and service exposure.

The associated tags (`tailscale` and `community-script`) indicate that this container is integrated into a broader, networked infrastructure that leverages secure overlay networking (such as Tailscale) and community-developed scripts for managing and securing hosted services. This positioning ensures that the web server operates within a context of secure, interconnected homelab operations.