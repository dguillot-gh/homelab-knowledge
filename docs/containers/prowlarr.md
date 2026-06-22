
# Prowlarr Documentation

## Overview

Prowlarr is a dedicated service deployed as an LXC container within the homelab environment. Its primary function is to manage and automate the indexing and organization of various media sources. Prowlarr serves as a critical component in the overall media management stack, designed to simplify the process of discovering, tracking, and organizing desired media content.

The container utilizes a lightweight Debian operating system and is provisioned with the necessary resources to perform its automation tasks efficiently. It integrates into the existing network topology by obtaining its IP address dynamically via DHCP.

## Technical Specifications

| Attribute | Value |
| :--- | :--- |
| **Service Name** | prowlarr |
| **Container Type** | LXC |
| **Host Node** | pve |
| **Operating System** | Debian |
| **Status** | Running |
| **IP Configuration** | DHCP |
| **Last Updated** | 2026-06-18 14:07 UTC |

## Resource Allocation

The container is allocated the following hardware and storage resources:

*   **VMID:** 104
*   **CPU Cores:** 2
*   **RAM:** 1024 MB
*   **Disk Space:** 3.86 GB
*   **Tags:** `arr-stack`, `community-script`

## Functional Role

Prowlarr functions as a media indexer and manager. Its core responsibility is to monitor disparate media sources, such as torrent trackers or dedicated media indexers, to facilitate automated discovery and centralized organization.

By operating within the `arr-stack` tag, Prowlarr streamlines the upstream process of finding and tracking desired files. This automated workflow significantly enhances the efficiency of media acquisition and organization within the homelab environment.