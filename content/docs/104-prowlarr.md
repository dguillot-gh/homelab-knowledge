---
title: "prowlarr"
vmid: 104
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 1.0
disk_gb: 3.86
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 104 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 104 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 1.0 GB |
| **Disk** | 3.86 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Prowlarr is a popular, self-hosted application that acts as a centralized indexer manager, primarily designed to integrate various media indexers (like Prowlarr, Lidarr, Sonarr) into a single dashboard. In a homelab environment, it plays a critical role in automating the discovery, indexing, and management of content from various sources, significantly reducing manual effort in managing media libraries and ensuring content is consistently available across different services.

## Purpose
Prowlarr is invaluable in a homelab for automating the management of media indexers and ensuring content organization. It centralizes the complex process of finding, managing, and downloading media assets, allowing users to automate content acquisition from diverse sources without manual intervention. This setup promotes a centralized, reproducible workflow for media management.

## Key Features
*   Centralized Indexer Management: Manages multiple indexers (e.g., torrent trackers) in one place.
*   Automated Discovery: Automatically discovers and manages media sources based on user-defined criteria.
*   Integration with Arr-Stack: Seamlessly integrates with the broader automation framework to manage workflows.
*   Simplified Workflow: Provides a unified interface for indexing, searching, and monitoring content sources.

## Operational Notes
*   Ensure all required indexers and downstream applications (like Radarr or Sonarr) are running and correctly configured before starting Prowlarr.
*   Verify that the container has sufficient network access to reach all required indexer sources; firewall rules must be checked if downloads fail.
*   Regularly check the application logs for errors, especially during indexer synchronization, to troubleshoot any connection or parsing issues.

## Suggested Tags
arr-stack, media, automation, storage, reverse-proxy

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:EB:21:2F,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-104-disk-0,size=4G` |

> Add manual notes here.
