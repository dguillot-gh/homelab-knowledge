
# GitHub Runner Container Documentation

## Overview

The `github-runner` container is an isolated Lightweight Virtual Machine (LXC) instance deployed within the Proxmox Virtual Environment (PVE) homelab infrastructure. This container is specifically configured to serve as a dedicated Continuous Integration (CI) runner, providing a standardized, reproducible, and isolated environment for automated software delivery and execution.

This setup adheres strictly to containerization principles, ensuring that all CI/CD workflows are executed in a predictable and isolated manner, minimizing environmental drift.

## Functional Role

The primary function of this container is to act as a dedicated execution agent for automated workflows. It is utilized to pull code from GitHub repositories, execute automated build, test, and deployment scripts, thereby autonomously managing the software delivery pipeline central to the homelab system's functionality.

## Technical Specifications

### Container Identification

| Attribute | Value |
| :--- | :--- |
| **Container Name** | `github-runner` |
| **Proxmox ID (VMID)** | 129 |
| **Host Node** | `pve` |
| **Operating System** | Debian |
| **Current IP Address** | DHCP |
| **Status** | Running |
| **Tags** | `ci`, `community-script` |
| **Last Updated** | 2026-06-18 14:07 UTC |

### Hardware Allocation

The container is provisioned with the following allocated resources:

| Resource | Specification |
| :--- | :--- |
| **Memory (RAM)** | 2048 MB |
| **CPU Cores** | 2 |
| **Disk Space** | Approximately 7.78 GB |

## Detailed Resource Summary

| Parameter | Value |
| :--- | :--- |
| **VMID** | 129 |
| **Status** | Running |
| **Operating System** | Debian |
| **IP Address** | DHCP |
| **RAM** | 2048 MB |
| **CPU** | 2 Cores |
| **Disk Usage** | 7.78 GB |
| **Node** | pve |
| **Tags** | ci, community-script |