---
title: "navidrome"
vmid: 122
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 1.0
disk_gb: 35.35
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 122 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 122 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 1.0 GB |
| **Disk** | 35.35 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Navidrome is a self-hosted media server application designed for organizing, managing, and streaming personal music libraries across a network. In a homelab environment, it serves as a centralized media hub, allowing users to access their music collections remotely and integrate seamlessly with other media management tools, transforming raw music files into an accessible, organized, and personalized streaming experience.

## Purpose
This container provides a dedicated, lightweight service for managing audio files and streaming them to other devices within the network. It allows the homelab owner to centralize music storage and access, eliminating the need for external streaming services.

## Key Features
*   Centralized Music Library: Organizes all music files into an easily browsable structure.
*   Streaming Capability: Enables remote playback of music to connected devices.
*   Metadata Management: Automatically handles album art and artist information for rich media display.
*   Self-Hosted Control: Provides full control over media files and streaming settings within the homelab.

## Operational Notes
*   Resource Allocation: Since this is a media server, monitor the CPU and RAM usage, especially during peak streaming times, to ensure adequate performance.
*   File Organization: Ensure your music files are organized in a logical directory structure before configuring Navidrome to avoid clutter.
*   Updates: Regularly check for updates to the Navidrome container to ensure you are running the latest version with the newest features and security patches.

## Suggested Tags
media
storage
music
automation
reverse-proxy

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:96:7A:7E,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| mp0 | `/mnt/data/,mp=/data` |
| rootfs | `TGroup1:vm-122-disk-0,size=36G` |

> Add manual notes here.
