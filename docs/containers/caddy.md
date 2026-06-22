
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

This document provides detailed information regarding the deployment, configuration, and operational role of the `caddy` LXC container within the homelab infrastructure. This container is designated as a dedicated host for serving web traffic, utilizing the Caddy reverse proxy to manage HTTP communication and automate the handling of SSL/TLS certificate management.

## Container Description

The `caddy` instance is deployed as an LXC container utilizing a Debian-based operating system. Its primary function is to establish a secure and stable entry point for internal services across the network.

Caddy has been selected as the core web server solution due to its robust architecture, simplified configuration syntax, and automatic management capabilities for complex security protocols, specifically HTTP/2 and TLS/SSL termination.

## Technical Specifications

### Hardware and Resource Allocation

| Specification | Value | Notes |
| :--- | :--- | :--- |
| **VMID** | 118 | Unique identifier for the virtual machine. |
| **Host Node** | pve | The underlying Proxmox host machine. |
| **Status** | running | Current operational state of the container. |
| **Operating System** | Debian | Base Linux distribution utilized. |
| **Memory (RAM)** | 512 MB | Allocated physical memory. |
| **Disk Space** | 19.52 GB | Total available storage space. |
| **CPU Cores** | 1 | Allocated processing unit. |
| **IP Address** | dhcp | Network address obtained via DHCP. |

### Container Metadata

| Metadata | Value |
| :--- | :--- |
| **Tags** | community-script, tailscale, webserver |

## Operational Role and Context

The `caddy` container serves a critical function in the homelab environment: providing a centralized, secure gateway for network services.

The container is integrated into a highly networked infrastructure, indicated by its associated tags:
*   **`tailscale`**: Indicates integration with secure overlay networking, allowing the container to participate in a secure, decentralized network fabric.
*   **`community-script`**: Suggests the use of community-developed automation scripts for deployment, management, or service provisioning.
*   **`webserver`**: Defines its primary role as an HTTP/S service provider.

This context confirms that the container is positioned not merely as an isolated server, but as an active component within a secure, interconnected homelab ecosystem designed for managed service delivery.