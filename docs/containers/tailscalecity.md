
# tailscalecity LXC Container Documentation

## Metadata

| Field | Value |
| :--- | :--- |
| **Container Name** | `tailscalecity` |
| **VMID** | `114` |
| **Node** | `pve` |
| **Status** | `running` |
| **IP Address** | DHCP Assigned |
| **Last Updated** | 2026-06-18 14:07 UTC |
| **Type** | `system_container` |

---

## Overview

The `tailscalecity` container is a highly optimized, lightweight LXC instance deployed within the homelab environment. It is designed to serve as a foundational, secure node intended for hosting specialized services or tools while minimizing system resource consumption.

The core purpose of this container is to provide a standardized, secure, and easily deployable platform for specific tasks. By leveraging community-provided deployment scripts, the setup process is streamlined, allowing administrators to quickly provision a minimal Debian environment ready for targeted application deployment.

Crucially, this container is configured with the `tailscale` network tag, enabling integration into a secure, private mesh network. This integration ensures the container can securely access and communicate with other resources across the homelab network via the Tailscale overlay network.

## System Specifications

### General Information

*   **Container Name:** `tailscalecity`
*   **Operating System:** Debian
*   **Container Type:** LXC
*   **Host Node:** `pve`

### Hardware Resources

This container is provisioned with minimal resources to maximize efficiency.

*   **Virtual Machine ID (VMID):** 114
*   **Status:** Running
*   **CPU Cores:** 1
*   **RAM Allocation:** 1024 MB (1 GB)
*   **Disk Space:** 9.75 GB

### Network and Deployment Details

*   **Network Configuration:** DHCP
*   **Security/Networking Tag:** `tailscale` (Enables private mesh networking)
*   **Deployment Tags:** `community-script`, `os`