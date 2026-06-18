---
title: "sonarr"
vmid: 101
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

**Status:** Running | **VMID:** 101 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 101 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 1.0 GB |
| **Disk** | 3.86 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Sonarr is a powerful, open-source application designed to automatically manage your media libraries by downloading and organizing content from various indexers. In a homelab environment, Sonarr acts as a crucial automation tool, centralizing media management, eliminating the manual effort required for finding, downloading, and organizing movies and TV shows. It forms a core component of a self-hosted media stack, providing structure and organization to personal media collections.

## Purpose
Sonarr’s primary function is to automate the process of finding, downloading, and organizing media content from various sources. In a homelab, it allows users to centralize their media assets, ensuring that collections are consistently updated and structured without manual intervention.

## Key Features
*   Automated Indexing: Scans configured indexers to find new media titles.
*   Download Management: Facilitates the downloading of media files from sources.
*   Series Organization: Automatically organizes downloaded content into specified folders based on series and season.
*   Template Support: Allows for custom configuration and automation of the entire media pipeline.

## Operational Notes
*   Ensure proper configuration of your indexers and download clients (like Radarr or Prowler) before starting the Sonarr service to prevent configuration drift.
*   Monitor disk space regularly, as media downloads can consume significant storage space quickly.
*   Keep the Sonarr container updated to ensure access to the latest features and security patches.

## Suggested Tags
arr-stack
media
automation
storage
community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:3E:91:87,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| mp0 | `/mnt/data/,mp=/data` |
| rootfs | `TGroup1:vm-101-disk-0,size=4G` |

> Add manual notes here.
