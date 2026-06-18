---
title: "shelfmark"
vmid: 126
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

**Status:** Running | **VMID:** 126 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 126 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 7.78 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

This container, shelfmark, serves as a dedicated platform for housing community-driven scripts and educational resources within the homelab environment. Its primary role is to centralize knowledge, automate repetitive tasks, and provide easy access to useful scripts and ebooks, enhancing the overall productivity and self-learning experience of the homelab owner.

## Purpose
shelfmark is designed to act as a centralized repository for useful automation scripts and educational materials. It allows the homelab owner to easily deploy, manage, and access community-developed solutions without needing to manually set up complex environments. This significantly speeds up the learning curve and the implementation of complex automation projects.

## Key Features
*   Centralized repository for community scripts and educational ebooks.
*   Lightweight LXC container setup for efficient resource utilization.
*   Dedicated space for managing automation and development tools.
*   Easy access and deployment of pre-written scripts.

## Operational Notes
*   Ensure that system updates are regularly applied to maintain the security and compatibility of the scripts stored within.
*   Monitor the disk space regularly, as the storage of scripts and ebooks can grow over time.
*   Use this environment to test new automation workflows before deploying them to production systems.

## Suggested Tags
automation
development
productivity
community-script
storage

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:6B:5A:5F,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-126-disk-0,size=8G` |

> Add manual notes here.
