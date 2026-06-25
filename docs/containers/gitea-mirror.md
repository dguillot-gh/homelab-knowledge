
---
title: "Gitea Mirror Service"
vmid: "107"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

# Gitea Mirror Service Documentation

## 1. Introduction

The `gitea-mirror` container is a dedicated Linux Container (LXC) deployed within the homelab infrastructure. Its primary role is to establish and maintain robust, synchronized, and read-only mirrors of primary Gitea Git repositories. This service leverages community-developed scripts to efficiently manage the data mirroring process, significantly enhancing data redundancy, availability, and access across the homelab environment.

## 2. Service Overview

The core functionality of the `gitea-mirror` service is to create synchronized copies of critical Git repository data. This architecture is designed to provide high availability for code management services by ensuring that mirror data is consistently available and accessible, thereby mitigating risks associated with single points of failure.

The service operates as a specialized synchronization layer, allowing for reliable data access and serving as an alternative access point for source code management.

## 3. Container Specifications

### 3.1 General Details

This section details the foundational information and configuration of the container instance.

| Attribute | Value | Description |
| :--- | :--- | :--- |
| **Container Name** | `gitea-mirror` | The designated name of the container. |
| **Container Type** | LXC Container | The underlying virtualization technology. |
| **Host Node** | `pve` | The physical Proxmox host where the container resides. |
| **Container ID (VMID)** | 107 | The unique identifier assigned by the hypervisor. |
| **Current Status** | Running | The operational state of the container. |
| **IP Addressing** | DHCP | The IP address assignment method. |
| **Last Updated** | 2026-06-18 14:07 UTC | Timestamp of the last modification to this configuration. |
| **Tags** | `community-script`, `gitea`, `mirror` | Categorization tags for inventory and management purposes. |

### 3.2 Resource Allocation

The resource allocation defines the hardware resources dedicated to the operation of the mirroring service.

| Resource | Specification | Details |
| :--- | :--- | :--- |
| **CPU Cores** | 2 | Allocated processing power for mirroring and synchronization tasks. |
| **RAM** | 2 GB (2048 MB) | Allocated memory for the operating system and mirroring processes. |
| **Storage Size** | 5.82 GB | Total allocated disk space for container data, including repository mirrors and system files. |