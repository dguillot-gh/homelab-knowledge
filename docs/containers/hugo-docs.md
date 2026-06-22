
# `hugo-docs` Container Documentation

This document provides a detailed overview, specifications, and configuration details for the `hugo-docs` container utilized within the homelab environment.

## Overview

The `hugo-docs` container serves as a dedicated, isolated Linux environment provisioned using the LXC containerization framework. Its primary functions are twofold: system administration practice and knowledge sharing.

This environment is specifically configured to:
1. Host static website documentation, typically generated using the Hugo static site generator.
2. Act as a controlled testing environment for deploying, configuring, and managing Debian-based operating systems.

The container facilitates community-driven system administration objectives by providing a sandboxed environment where users can safely practice container management and operating system practices without impacting the host infrastructure.

## Container Specifications

### General Information

| Attribute | Value | Description |
| :--- | :--- | :--- |
| **Container Name** | `hugo-docs` | The unique identifier for the container. |
| **Container Type** | Documentation/Testing Environment | Defines the primary use case of the environment. |
| **Operating System** | Debian | The base Linux distribution running inside the container. |
| **Containerization Framework** | LXC | The underlying containerization technology utilized. |
| **Host Node** | `pve` | The Proxmox Virtual Environment host platform. |
| **Status** | Running | Current operational state of the container. |
| **IP Assignment** | DHCP | Dynamic IP assignment from the network. |
| **Virtual Machine ID (VMID)** | `128` | The unique identifier within the host system. |

### Resource Allocation

The container is provisioned with the following defined hardware and storage resources:

| Resource | Allocated Value |
| :--- | :--- |
| **CPU Cores** | 1 |
| **RAM** | 1048 MB |
| **Disk Space** | 19.52 GB |

## Configuration Metadata

The following YAML metadata describes the current configuration and status of the container:

```yaml
title: "hugo-docs"
vmid: "128"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"