
# tailscalecity LXC Container Documentation

## 📄 Overview

The `tailscalecity` container is a highly optimized and lightweight LXC instance deployed within the homelab environment. It is engineered to serve as a foundational, secure, and resource-efficient node designed for hosting specialized services or tools.

The primary purpose of this container is to establish a standardized and easily deployable platform. By leveraging community-provided deployment scripts, the setup process is streamlined, allowing administrators to quickly provision a minimal Debian operating environment ready for targeted application deployment.

Crucially, this container is integrated with the `tailscale` network tag. This integration enables the container to securely access and communicate with other resources across the homelab via the Tailscale overlay network, facilitating secure, private mesh networking.

## ⚙️ System Specifications

### General Information

| Field | Value | Description |
| :--- | :--- | :--- |
| **Container Name** | `tailscalecity` | Unique identifier for the LXC container. |
| **Operating System** | Debian | Base operating system for the container. |
| **Container Type** | `system_container` | Specifies the container type within the LXC structure. |
| **Host Node** | `pve` | The Proxmox Virtual Environment host where the container resides. |

### Hardware Resources

The container is provisioned with minimal resources to maximize system efficiency and resource availability for other services.

*   **Virtual Machine ID (VMID):** 114
*   **Current Status:** Running
*   **CPU Allocation:** 1 Core
*   **RAM Allocation:** 1024 MB (1 GB)
*   **Disk Space:** 9.75 GB

### Network and Deployment Configuration

| Setting | Value | Details |
| :--- | :--- | :--- |
| **Network Configuration** | DHCP | IP address is dynamically assigned by the DHCP server. |
| **Security Tag** | `tailscale` | Enables integration into the Tailscale private mesh network, facilitating secure peer-to-peer communication. |
| **Deployment Tags** | `community-script`, `os` | Tags indicating the use of community deployment methods and the base operating system. |