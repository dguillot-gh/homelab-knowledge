
---
title: "Navidrome Media Server"
vmid: "122"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

## Overview

The Navidrome container (VMID 122) is a dedicated, lightweight LXC environment deployed within the homelab infrastructure. This container is specifically designed and configured to host the Navidrome application, providing an isolated and stable environment for media management and streaming services.

By leveraging LXC technology, this setup ensures that the media server operates independently from the host system, optimizing resource usage and ensuring dedicated management of music libraries and streaming protocols.

## Purpose

The primary function of this container is to serve as a dedicated music streaming and management system. Its isolation provides the following benefits:

*   **Stability:** The media server operates independently, reducing potential conflicts with the host system.
*   **Efficiency:** Allocating dedicated resources for the application ensures predictable performance.
*   **Modularity:** Facilitates easy management and updates for the media server component.

## System Specifications

| Attribute | Detail |
| :--- | :--- |
| **VMID** | 122 |
| **Status** | Running |
| **Node** | pve |
| **Operating System** | Debian |
| **RAM Allocation** | 1024 MB |
| **CPU Cores** | 2 |
| **Disk Space** | 35.35 GB |
| **IP Address** | DHCP |
| **Tags** | community-script, music |