---
title: "jellyfin"
vmid: 100
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 3.0
disk_gb: 78.19
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 100 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 100 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 3.0 GB |
| **Disk** | 78.19 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Jellyfin is an open-source, free, and open-source media server that allows users to organize, store, and stream their multimedia collections (movies, TV shows, music, photos) directly to devices across any platform. In a homelab environment, it serves as a centralized hub for managing personal media, allowing users to take control of their content delivery, avoid reliance on commercial streaming services, and practice self-hosting by managing media infrastructure entirely within their own network.

## Purpose
Jellyfin provides a centralized platform for managing and streaming personal media files, eliminating the need for external streaming services. It allows the homelab owner to control the entire media experience, including library management and quality control, ensuring media is accessible securely within the private network.

## Key Features
*   **Universal Streaming:** Supports various streaming protocols (Plex, Emby, Web), allowing access to media from smart TVs, mobile devices, and web browsers.
*   **Media Management:** Offers a robust interface for organizing, tagging, and cataloging media libraries.
*   **Hardware Transcoding:** Utilizes CPU resources to automatically transcode video streams in real-time, ensuring media is playable regardless of the client device's format.
*   **Self-Hosted Control:** Provides complete control over the media server, storage, and access permissions, keeping data private within the homelab.

## Operational Notes
*   Ensure sufficient CPU resources are allocated to the VM to handle heavy transcoding tasks smoothly, especially when multiple streams are active simultaneously.
*   Mount the media storage volume (disk) directly into the container for optimal performance and easy access to the media files.
*   Implement regular backup procedures for the media library and server configuration to protect against data loss.

## Suggested Tags
media
storage
backup
networking
automation

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:60:8F:89,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| mp0 | `/mnt/data/,mp=/data` |
| rootfs | `TGroup1:vm-100-disk-0,size=80G` |

> Add manual notes here.
