
---
title: "Caddy Web Server Container Documentation"
vmid: "118"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

## Overview

This document details the deployment, configuration, and operational role of the `caddy` LXC container within the homelab infrastructure. This container functions as the centralized web traffic gateway, leveraging the Caddy reverse proxy to manage HTTP communication, secure connections, and automated SSL/TLS certificate handling for internal services.

## Container Description

The `caddy` instance is deployed as an LXC container running a Debian-based operating system. Its core function is to establish a secure and stable entry point for all network services.

Caddy has been selected as the core web server solution due to its robust architecture, streamlined configuration syntax, and native capabilities for automated management of complex security protocols, including HTTP/2 and TLS/SSL termination.

## Technical Specifications

### Hardware and Resource Allocation

The following table outlines the physical resource allocation and configuration details of the container.

| Specification | Value | Details |
| :--- | :--- | :--- |
| **VMID** | 118 | Unique identifier for the virtual machine instance. |
| **Host Node** | pve | The underlying Proxmox host machine hosting the container. |
| **Status** | running | Current operational state of the container. |
| **Operating System** | Debian | Base Linux distribution utilized for the container environment. |
| **Memory (RAM)** | 512 MB | Allocated physical memory resources. |
| **Disk Space** | 19.52 GB | Total available storage capacity. |
| **CPU Cores** | 1 | Allocated processing unit. |
| **IP Address** | dhcp | Network address dynamically assigned via DHCP. |

### Container Metadata

| Metadata | Value |
| :--- | :--- |
| **Tags** | community-script, tailscale, webserver |

## Operational Context and Role

The `caddy` container plays a critical role in the homelab environment by serving as a centralized, secure gateway for network services.

The associated metadata tags define the container's integration within the broader network security and automation framework:

*   **`webserver`**: Defines the primary function of the container as an HTTP/S service provider and reverse proxy.
*   **`tailscale`**: Indicates integration with Tailscale, establishing secure, decentralized overlay networking, which enhances secure communication and access management across the network fabric.
*   **`community-script`**: Suggests that the deployment, management, or service provisioning workflow utilizes community-developed automation scripts, emphasizing a focus on self-managed and reproducible infrastructure practices.

This context confirms that the container is not merely an isolated server, but an active, secure component within an interconnected homelab ecosystem designed for managed service delivery and network security.