---
title: "yubal"
vmid: 124
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 2.0
disk_gb: 46.15
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 124 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 124 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 46.15 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

yubal is an LXC container designed to serve as a dedicated hub for media management and custom scripting within the homelab environment. Its primary role is to centralize audio and visual assets, allowing for organized streaming and automated management of personal media collections. This container acts as a focused environment for running community-developed scripts related to media handling and organization.

## Purpose
This container is primarily useful for centrally managing and serving media files (music and media) across the network. It provides a dedicated, isolated space for running custom automation scripts that streamline media organization and playback tasks.

## Key Features
*   Runs as a lightweight LXC container, optimizing resource usage on the host system.
*   Dedicated storage for organizing music and media collections (46.15 GB allocated).
*   Execution environment for community-scripted automation tasks.
*   Optimized for media streaming and file management within the homelab.

## Operational Notes
*   Monitor the resource usage closely, as the 2.0 GB RAM allocation is sufficient, but heavy processing scripts can cause resource contention.
*   Establish a consistent backup routine for the container's disk space, especially given the media focus.
*   Ensure that necessary permissions are configured to allow scripts access to the media storage and network resources.

## Suggested Tags
media
automation
storage
community-script
music

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:C8:5F:4F,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-124-disk-0,size=47G` |

> Add manual notes here.
