
# GitHub Runner Container Documentation

## Overview

The `github-runner` container is an isolated Lightweight Virtual Machine (LXC) instance deployed within the Proxmox Virtual Environment (PVE) homelab infrastructure. This container is specifically configured to serve as a dedicated Continuous Integration (CI) runner, providing a standardized, reproducible, and isolated execution environment for automated software delivery and testing.

This deployment adheres strictly to containerization principles, ensuring that all CI/CD workflows are executed in a predictable and isolated manner, thereby minimizing environmental drift across the homelab system.

## Functional Role

The primary function of this container is to act as a dedicated execution agent for automated workflows. It is utilized to interact with GitHub repositories, pull source code, and execute automated build, test, and deployment scripts. This runner is central to autonomously managing the software delivery pipeline functionality of the homelab system.

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

### Resource Allocation

The container is provisioned with the following hardware resources:

| Resource | Specification |
| :--- | :--- |
| **Memory (RAM)** | 2048 MB |
| **CPU Cores** | 2 |
| **Disk Space** | Approximately 7.78 GB |

## Resource Summary

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