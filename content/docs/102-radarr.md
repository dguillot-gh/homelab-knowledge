---
title: "radarr"
vmid: 102
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 1.0
disk_gb: 13.68
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 102 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 102 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 1.0 GB |
| **Disk** | 13.68 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Radarr is a popular open-source application designed to manage and organize your media collections, specifically television shows and movies. In a homelab environment, it serves as a centralized media management hub, automating the process of finding, downloading, organizing, and renaming media files directly into your chosen storage locations.

## Purpose
Radarr significantly enhances media management by automating the entire process of media acquisition and organization. It eliminates manual file searching and renaming, allowing the user to maintain perfectly sorted and accessible media libraries within the homelab infrastructure.

## Key Features
*   Automated Indexing: Scans configured folders for new media releases from various torrent trackers.
*   Series Management: Automatically organizes downloaded content into proper season and episode directories.
*   Quality Control: Integrates with indexers (like Sonarr) to ensure that media is downloaded in the desired quality and format.
*   Queue System: Provides a centralized queue for managing ongoing downloads and processing tasks.

## Operational Notes
*   Ensure adequate disk space is allocated on the host system, as media downloads can consume significant temporary space.
*   Regularly verify the configured indexers and download clients to ensure continuous operation and access to new media sources.
*   Monitor the logs periodically to troubleshoot any download failures or indexing errors that may occur during the media acquisition process.

## Suggested Tags
arr-stack
media
automation
storage
arr-stack

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:2E:3A:50,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| mp0 | `/mnt/data/,mp=/data` |
| rootfs | `TGroup1:vm-102-disk-0,size=14G` |

> Add manual notes here.
