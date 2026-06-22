
# Argus Container Documentation

## Overview

The `argus` container is a dedicated, lightweight Linux environment deployed within the homelab infrastructure. It is specifically configured to serve as a centralized hub for monitoring tools and automated scripts, ensuring comprehensive system health, security management, and operational oversight for the Proxmox environment.

## System Specifications

This section details the deployment and physical attributes of the `argus` container.

### Deployment Details

| Attribute | Value |
| :--- | :--- |
| **Name** | `argus` |
| **VMID** | 120 |
| **Host Node** | `pve` |
| **Status** | Running |
| **IP Assignment** | DHCP |
| **Last Updated** | 2026-06-18 14:07 UTC |
| **Container Type** | Documentation Host |

### Operating System & Resources

The container utilizes a minimal Debian Linux distribution, optimized for low resource consumption while maintaining robust monitoring capabilities.

| Specification | Detail |
| :--- | :--- |
| **Operating System** | Debian |
| **Memory (RAM)** | 512 MB |
| **CPU Cores** | 1 |
| **Disk Space** | 2.88 GB |

## Functional Role

The primary function of the `argus` container is to act as the central monitoring and automation hub for the Proxmox-based homelab infrastructure.

1.  **System Monitoring (`watcher` Role):** The container is designated as a `watcher`, actively tracking system events, real-time resource usage, and security alerts across the entire infrastructure. It provides passive health checks and operational status monitoring.
2.  **Automation Repository:** `argus` serves as a repository for custom `community-script`s, streamlining the execution of automated tasks required for maintaining system health, performing routine diagnostics, and operational oversight.
3.  **Centralized Oversight:** By consolidating monitoring tools and automated scripts, the container enables efficient, centralized visibility into the performance and operational status of all Proxmox system components.

## Resource Summary

| Metric | Value |
| :--- | :--- |
| **Host System** | pve |
| **Status** | Running |
| **Operating System** | Debian |
| **Memory Allocation** | 512 MB |
| **CPU Allocation** | 1 Core |
| **Storage Utilization** | 2.88 GB |
| **Tags** | `community-script`, `watcher` |