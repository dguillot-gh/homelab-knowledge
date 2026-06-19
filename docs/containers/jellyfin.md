
---
title: "Jellyfin Media Server LXC"
vmid: "100"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

# Jellyfin Media Server (LXC Container)

## Overview
This documentation describes the configuration and function of the `jellyfin` LXC container, which is deployed as a dedicated media server within the homelab environment. This container is designed to centralize multimedia management, streaming, and transcoding for the entire local network.

## Functionality
The primary purpose of this container is to host the Jellyfin application—an open-source platform for organizing, managing, and streaming multimedia content (video and audio). By centralizing media operations, this server acts as a hub, making large media libraries accessible and streamable to various devices across the home network.

## Architecture and Specifications
The container is built upon the lightweight LXC technology and utilizes a Debian operating system. The allocated resources ensure sufficient performance for demanding media processing tasks, including real-time transcoding.

### Resource Allocation
| Specification | Detail |
| :--- | :--- |
| **Node** | pve |
| **VMID** | 100 |
| **Status** | Running |
| **Operating System** | Debian |
| **RAM** | 3072 MB |
| **CPU Cores** | 2 |
| **Disk Space** | 78.19 GB |
| **IP Addressing** | DHCP |

## Deployment Details
The container utilizes dynamic DHCP addressing, ensuring seamless integration into the local network structure without static IP configuration.

### Tags
* community-script
* media