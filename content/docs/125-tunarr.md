---
title: "tunarr"
vmid: 125
type: "LXC"
status: "running"
node: "pve"
cpu: 3
ram_gb: 1.98
disk_gb: 4.84
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 125 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 125 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 3 |
| **RAM** | 1.98 GB |
| **Disk** | 4.84 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

tunarr is a containerized application designed to streamline the management and streaming of media content within a homelab environment. It acts as a centralized hub, automating the process of finding, downloading, and organizing various media files from numerous indexers. Its role is to simplify media acquisition, storage, and delivery, making complex media management tasks accessible and automated for the homelab user.

## Purpose
Tunarr significantly enhances homelab productivity by automating the complex task of media indexing and downloading. It allows users to centrally manage their entire media library, ensuring that content is easily discovered, organized, and streamed across various devices.

## Key Features
*   Automated Indexing: Connects to various media indexers (like Sonarr, Radarr, Lidarr) to discover new content.
*   Media Management: Centralizes the download, renaming, and organization of movies, TV shows, and music.
*   Streamlined Workflow: Integrates various media tools into a single, cohesive automation stack.
*   Containerized Deployment: Runs efficiently as an LXC container, simplifying setup and maintenance on a Linux host.

## Operational Notes
*   Resource Allocation: Monitor the CPU and RAM usage regularly, especially during heavy indexing or download operations, to ensure adequate resources for the system.
*   Network Configuration: Ensure that all media indexers and download clients are accessible within the container's network, typically via shared network bridges or VPNs.
*   Backup Strategy: Implement a robust backup routine for the configuration files and the actual media storage directories to prevent data loss.

## Suggested Tags
media
automation
arr-stack
storage
community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:B5:BC:3D,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| mp0 | `/mnt/data/,mp=/data` |
| rootfs | `TGroup1:vm-125-disk-0,size=5G` |

> Add manual notes here.
