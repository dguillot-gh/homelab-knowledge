---
title: "gitea-mirror"
vmid: 107
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 2.0
disk_gb: 5.82
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 107 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 107 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 5.82 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

gitea-mirror is a self-hosted synchronization service designed to mirror remote Git repositories, making external code management fully accessible and controlled within the homelab environment. It acts as a local hub, pulling and storing remote repositories so that developers and collaborators can access essential code resources quickly and securely without relying on external hosting services.

## Purpose
This container serves as a local, resilient backup and synchronization system for essential code repositories. It eliminates external dependencies by providing local access to code, ensuring that critical development assets remain available regardless of external service status.

## Key Features
*   **Repository Mirroring:** Efficiently mirrors remote Git repositories to local storage.
*   **Self-Hosted Access:** Provides a fully controlled, local interface for accessing and managing code.
*   **Synchronization:** Ensures that local copies of repositories are up-to-date with remote sources.
*   **Resource Efficiency:** Runs efficiently within an LXC container environment, optimizing resource usage.

## Operational Notes
*   Always ensure sufficient disk space on the host volume, as mirroring large repositories will consume significant storage.
*   Schedule regular backups of the mirrored data to a separate, long-term storage solution to prevent data loss.
*   Monitor CPU and RAM usage periodically to ensure the mirroring process remains stable and does not introduce performance bottlenecks.

## Suggested Tags
development, productivity, storage, automation, backup

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:CC:D4:E0,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-107-disk-0,size=6G` |

> Add manual notes here.
