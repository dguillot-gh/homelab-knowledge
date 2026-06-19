
# GitHub Runner Container Documentation

## Overview

The `github-runner` container is an isolated LXC instance deployed within the Proxmox VE homelab environment. It is specifically configured to serve as a dedicated Continuous Integration (CI) runner, providing a standardized, reproducible environment for automated software delivery and execution.

This lightweight container is designed to execute automated tasks, such as pulling, building, and testing code from GitHub repositories. It adheres to containerization principles, ensuring that CI workflows are executed in an isolated and predictable manner.

## Functional Role

The primary function of this container is to act as a dedicated runner for community scripts and automated workflows. By utilizing this platform, the homelab environment can autonomously manage the software delivery pipeline, streamlining the development and deployment processes central to the system's functionality.

## Technical Specifications

| Attribute | Value |
| :--- | :--- |
| **Container Name** | `github-runner` |
| **Proxmox ID (VMID)** | 129 |
| **Node** | pve |
| **Status** | running |
| **Operating System** | Debian |
| **IP Address** | dhcp |
| **Last Updated** | 2026-06-18 14:07 UTC |
| **Tags** | ci, community-script |

### Hardware Allocation

The container is allocated the following resources:

*   **Memory (RAM):** 2048 MB
*   **CPU Cores:** 2
*   **Disk Space:** Approximately 7.78 GB

## Resource Details

*   **VMID:** 129
*   **Status:** running
*   **IP:** dhcp
*   **OS:** debian
*   **RAM:** 2048 MB
*   **Disk:** 7.78 GB
*   **Cores:** 2
*   **Node:** pve
*   **Tags:** ci, community-script