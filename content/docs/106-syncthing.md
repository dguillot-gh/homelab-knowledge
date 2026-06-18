---
title: "syncthing"
vmid: 106
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 2.0
disk_gb: 15.64
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 106 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 106 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 15.64 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

Syncthing is a free, open-source, decentralized file synchronization program that allows users to securely share files and folders across multiple devices. In a homelab environment, Syncthing serves as a crucial tool for creating a robust, self-hosted media server and data redundancy solution, allowing users to maintain seamless, secure synchronization of personal files regardless of location or external cloud services.

## Purpose
This container is designed to establish a peer-to-peer file synchronization network within the homelab. It allows users to securely sync media, documents, and backups across various devices, providing an alternative to centralized cloud storage solutions. This setup significantly enhances data independence, security, and control over personal data within the home network.

## Key Features
*   Peer-to-Peer Synchronization: Facilitates direct, decentralized file sharing between connected devices without relying on a central server.
*   End-to-End Encryption: All data transferred is secured using strong encryption protocols, ensuring privacy and data security.
*   Real-time Sync: Automatically monitors directories and synchronizes changes instantly across all synchronized nodes.
*   Customizable Sharing: Offers granular control over which folders are shared with which devices and synchronization rules.

## Operational Notes
*   Ensure that the Syncthing ports (default 22000) are properly exposed on your router's firewall if you need to access the synchronization from outside your local network.
*   Configure secure, unique IDs for each device to ensure only authorized peers can synchronize data, which is essential for security.
*   Regularly check the synchronization status and logs to monitor for any connection errors or synchronization failures.

## Suggested Tags
storage, security, automation, sync, media

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:FE:4B:44,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-106-disk-0,size=16G` |

> Add manual notes here.
