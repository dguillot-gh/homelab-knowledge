---
title: "lidarr"
vmid: 127
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 1.0
disk_gb: 23.54
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 127 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 127 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 1.0 GB |
| **Disk** | 23.54 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Lidarr is a powerful, open-source application that serves as a media management hub, specifically designed for organizing and automating the downloading, renaming, and organizing of media files based on user-defined indexes. In a homelab environment, it is critical for setting up automated pipelines for acquiring and managing large volumes of media, seamlessly integrating torrent and usenet sources into a cohesive library system.

## Purpose
Lidarr automates the entire workflow of media acquisition and organization, eliminating the need for manual file sorting and management. It is essential for creating a centralized, automated media library that functions as the backbone of a personal media server in a homelab setup.

## Key Features
*   Automated Media Indexing: Scans configured indexers (like Prowlarr or Sonarr) to discover new media files.
*   Renaming and Organization: Automatically renames downloaded files according to established organizational rules.
*   Source Integration: Connects directly to torrent and usenet indexers to pull content.
*   Library Management: Provides a central dashboard for managing the status and location of all media series and movies.

## Operational Notes
*   **Check Indexers Regularly:** Ensure that the configured indexers are functioning correctly and successfully updating. A broken indexer will halt your media pipeline.
*   **Monitor Disk Space:** Since Lidarr handles large media files, consistently monitor the disk usage of this container to prevent filling up your storage volume.
*   **Manage Queue Backlogs:** If you experience slow progress, check the activity logs to ensure that the download/ingestion process is not stalled due to network or configuration issues.

## Suggested Tags
arr-stack
media
automation
torrent
storage

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:6F:FA:AD,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| mp0 | `/mnt/data/,mp=/data` |
| rootfs | `TGroup1:vm-127-disk-0,size=24G` |

> Add manual notes here.
