
---
title: "tailscalecity" LXC Container
vmid: "114"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "system_container"
---

## Overview

The `tailscalecity` container is a lightweight, Debian-based LXC instance deployed within the homelab environment. It serves as a foundational, secure node designed to host specific services or tools, leveraging minimal system resources to maximize efficiency.

The primary function of this container is to provide an easily deployable and secure platform for specialized tasks. By utilizing community-provided scripts, the setup process is streamlined, allowing administrators to quickly provision a minimal Debian environment ready for targeted application deployment.

Crucially, the inclusion of the `tailscale` tag indicates that this container is configured for secure, private mesh networking. This integration allows the container to securely access and communicate with other resources across the homelab network via the Tailscale overlay network.

## System Specifications

### General Information
*   **Container Name:** `tailscalecity`
*   **Operating System:** Debian
*   **Container Type:** LXC
*   **Homelab Node:** pve

### Hardware Resources
*   **Virtual Machine ID (VMID):** 114
*   **Status:** Running
*   **IP Address:** DHCP Assigned
*   **CPU Cores:** 1
*   **RAM Allocation:** 1024 MB (1 GB)
*   **Disk Space:** 9.75 GB

### Network and Tags
*   **Network Configuration:** DHCP
*   **Security/Networking Tag:** `tailscale`
*   **Deployment Tag:** `community-script`, `os`