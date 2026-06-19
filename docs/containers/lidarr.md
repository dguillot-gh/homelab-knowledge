
title: "lidarr"
vmid: "127"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

## Overview

The Lidarr service is deployed as a dedicated container within the homelab environment, utilizing the LXC virtualization technology with Debian as its operating system. This setup provides an efficient and lightweight environment for hosting media management functionalities. The container is managed by the underlying Proxmox infrastructure, demonstrating effective resource isolation and utilization.

The container is allocated 1024 MB of RAM and 2 CPU cores, with a dedicated disk partition of 23.54 GB reserved for its operations. This configuration ensures that the media application and its dependencies are isolated, contributing to a streamlined and efficient homelab setup.

## Functionality

Lidarr serves as a centralized media management solution, designed to organize, index, and track personal media libraries. Its primary function is to automate the process of locating, sorting, and managing media files sourced from various networks.

The container is specifically configured to integrate various acquisition methods, including torrent and usenet protocols, allowing it to effectively manage media assets sourced through P2P and usenet channels. This automation integrates various media acquisition and organization workflows into a single, centralized system.

## Resources

| Attribute | Value |
| :--- | :--- |
| **VMID** | 127 |
| **Node** | pve |
| **Status** | running |
| **IP Address** | dhcp |
| **Operating System** | Debian |
| **Memory (RAM)** | 1024 MB |
| **CPU Cores** | 2 |
| **Disk Space** | 23.54 GB |
| **Tags** | arr, community-script, torrent, usenet |