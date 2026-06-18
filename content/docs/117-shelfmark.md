---
title: "shelfmark"
vmid: 117
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 2.0
disk_gb: 7.78
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 117 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 117 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 7.78 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

shelfmark is a lightweight LXC container designed to host community scripts and reference material within a homelab environment. Its primary role is to serve as a centralized repository for self-developed automation tasks and knowledge resources, simplifying the setup and management of complex homelab projects. It acts as a knowledge hub, allowing users to easily deploy and run pre-configured scripts without requiring extensive manual setup.

## Purpose
This container is useful for housing specific community-developed scripts and ebook resources, centralizing custom automation workflows within the homelab. It provides a portable and isolated environment for running complex tools and managing project-specific documentation.

## Key Features
*   Runs as a lightweight LXC container, minimizing overhead and maximizing resource efficiency.
*   Dedicated space for storing community-developed scripts and ebook documentation.
*   Provides an isolated environment for running specific automation tasks.
*   Optimized for resource efficiency, utilizing only 2.0 GB of RAM and 2 CPU cores.

## Operational Notes
*   Ensure regular backups of the container's configuration and script files to prevent data loss.
*   Monitor CPU and RAM usage periodically to ensure the container is not overburdened by automated processes.
*   Keep the container image and associated scripts updated to maintain compatibility and security.

## Suggested Tags
automation, development, productivity, storage, community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:BE:D2:1F,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-117-disk-0,size=8G` |

> Add manual notes here.
