
---
title: "radarr"
vmid: "102"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

# Radarr Media Management Service

This document details the configuration and operational specifications of the `radarr` LXC container, a dedicated service deployed within the homelab environment for automated media management.

## Overview

The `radarr` container functions as the central media indexing service, utilizing the Radarr application to organize, monitor, and manage collections of movies and television series. It is designed to automate the process of media discovery and organization, significantly reducing manual effort in managing the personal media library.

## Technical Specifications

The container operates on a Debian-based operating system and is provisioned with specific resource allocations for optimal performance within the virtualization host.

| Specification | Detail |
| :--- | :--- |
| **Container Name** | `radarr` |
| **Operating System** | Debian |
| **Virtualization Type** | LXC Container |
| **Host Node** | pve |
| **Status** | Running |
| **Memory (RAM)** | 1024 MB |
| **CPU Cores** | 2 |
| **Disk Space** | 13.68 GB |
| **Network Configuration** | DHCP |
| **Tags** | `arr-stack`, `community-script` |

## Functional Description

Radarr's primary role in this homelab setup is to serve as the automated indexer for the media library. It performs the following key functions:

1.  **Media Indexing:** Scans configured media sources (e.g., torrent trackers, file shares) for new content.
2.  **Organization:** Organizes discovered media based on defined criteria (e.g., series, movies, quality, release year).
3.  **Automation:** Automates the process of monitoring, downloading, and organizing media files, ensuring the media library remains consistently updated and organized.

## Resource Details

*   **VMID:** 102
*   **Status:** Running
*   **IP Address:** DHCP
*   **OS:** Debian
*   **RAM:** 1024 MB
*   **Disk:** 13.68 GB
*   **CPU:** 2 Cores
*   **Node:** pve
*   **Tags:** arr-stack, community-script