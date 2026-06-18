---
title: "flaresolverr"
vmid: 105
type: "LXC"
status: "running"
node: "pve"
cpu: 1
ram_gb: 0.5
disk_gb: 3.86
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 105 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 105 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 1 |
| **RAM** | 0.5 GB |
| **Disk** | 3.86 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

flaresolverr is a specialized LXC container designed to host community-developed scripts and tools focused on media management automation. In a homelab environment, it serves as a centralized hub for automating the organization, downloading, and management of digital media files, greatly reducing manual effort in content curation.

## Purpose
This container provides a dedicated, lightweight environment for running complex automation scripts essential for managing media libraries. It allows the homelab user to implement a scalable, automated workflow for media acquisition and organization without cluttering the host system.

## Key Features
*   Centralized automation hub for media file management.
*   Utilizes community-developed scripts for efficient sorting and organization.
*   Operates efficiently within a lightweight LXC container environment.
*   Facilitates the seamless integration of media acquisition tasks.

## Operational Notes
*   Monitor resource usage closely, especially CPU and RAM, as automation tasks can spike during processing.
*   Implement regular backups of the container's configuration and any downloaded media to ensure data integrity.
*   Keep the container's dependencies updated regularly to maintain compatibility with evolving community scripts.

## Suggested Tags
arr-stack
automation
development
media
reverse-proxy

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:74:17:A9,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-105-disk-0,size=4G` |

> Add manual notes here.
