---
title: "audiobookshelf"
vmid: 121
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 2.0
disk_gb: 4.84
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 121 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 121 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 4.84 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

This container runs Audiobookshelf, a powerful media server designed to organize, manage, and stream personal audio content. In a homelab environment, it serves as a dedicated media repository and streaming service, centralizing large personal audio libraries and providing easy, accessible access across various devices within the network.

## Purpose
Audiobookshelf’s primary role in a homelab is to establish a centralized, self-hosted media management solution, eliminating reliance on external, subscription-based services. It allows the user to control and organize their entire audio collection directly on their home network, enhancing privacy and control over personal media consumption.

## Key Features
*   **Centralized Library Management:** Organizes local audio files into a cohesive, searchable library.
*   **Multi-Device Streaming:** Allows seamless playback of audio content across various devices via web interfaces and mobile apps.
*   **Metadata Management:** Automatically pulls and displays rich metadata (covers, titles, artists) for enhanced browsing.
*   **Local File Hosting:** Stores all media locally, ensuring data sovereignty and offline access.

## Operational Notes
*   **Storage Configuration:** Ensure the underlying storage volume is configured with sufficient space and is appropriately mounted to avoid resource contention.
*   **Regular Backups:** Since this holds important media, implement a regular backup schedule for the configuration and the actual media files to safeguard against data loss.
*   **File Structure:** Organize audio files within the designated volume following clear naming conventions to facilitate future organization and automation.

## Suggested Tags
media
storage
productivity
automation
audiobookshelf

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:84:99:59,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| mp0 | `/mnt/data/,mp=/data` |
| rootfs | `TGroup1:vm-121-disk-0,size=5G` |

> Add manual notes here.
