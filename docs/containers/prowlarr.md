
# Prowlarr Documentation

## Overview

Prowlarr is an LXC container deployed within the homelab environment, dedicated to managing and automating the indexing and management of media sources. It functions as a critical component in the media management stack, designed to simplify the process of discovering, tracking, and organizing desired media content.

The container utilizes a lightweight Debian operating system and is provisioned with sufficient resources for its automation tasks. It integrates seamlessly into the existing network topology by obtaining its network address via DHCP.

## Technical Specifications

| Attribute | Value |
| :--- | :--- |
| **Service Name** | prowlarr |
| **Container Type** | LXC |
| **Node Host** | pve |
| **Operating System** | Debian |
| **Status** | Running |
| **IP Configuration** | DHCP |
| **Last Updated** | 2026-06-18 14:07 UTC |

## Resource Allocation

The container is allocated the following resources:

*   **VMID:** 104
*   **CPU Cores:** 2
*   **RAM:** 1024 MB
*   **Disk Space:** 3.86 GB
*   **Tags:** `arr-stack`, `community-script`

## Functional Role

Prowlarr operates as an indexer and manager, responsible for monitoring various media sources (such as torrent trackers or media indexers) to facilitate automated discovery and organization. Its presence, defined by the `arr-stack` tag, signifies its role in automating the upstream process of finding and tracking desired files, thereby streamlining the workflow for media consumption within the homelab.