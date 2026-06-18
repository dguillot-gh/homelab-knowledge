---
title: "homelable"
vmid: 113
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

**Status:** Running | **VMID:** 113 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 113 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 7.78 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

homelable is a dedicated LXC container designed to serve as a central hub for various essential homelab services, focusing heavily on networking, monitoring, and data visualization. It acts as a foundational platform for deploying custom community scripts and lightweight services necessary to manage and automate the operation of the home lab environment.

## Purpose
This container is useful for centralizing critical infrastructure tasks, allowing users to deploy essential monitoring tools and network services efficiently. It serves as an ideal starting point for managing data streams and providing visual oversight of the entire homelab setup.

## Key Features
*   Lightweight LXC container optimized for resource efficiency.
*   Centralized point for deploying community scripts and automation tools.
*   Integrated services for network management and real-time system monitoring.
*   Provides visualization capabilities for tracking homelab performance and data flow.

## Operational Notes
*   Ensure adequate network configuration is set up prior to deploying network services, as this container is heavily focused on networking.
*   Regularly review the monitoring dashboard to ensure all deployed scripts and services are running optimally and reporting correctly.
*   Given its role in data handling, implement scheduled backups for any persistent data generated within the container.

## Suggested Tags
monitoring, networking, visualization, automation, community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:3E:96:2F,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-113-disk-0,size=8G` |

> Add manual notes here.
