
# Prowlarr Documentation

## Overview

Prowlarr is a specialized media management service deployed within the homelab environment, utilizing an LXC container architecture. Its primary function is to automate the indexing, discovery, and organization of various media sources. Prowlarr serves as a critical component in the overall media management stack, streamlining the process of locating, tracking, and centrally organizing desired media content.

The service operates on a lightweight Debian operating system and is designed for efficient performance. It integrates seamlessly into the existing network topology by dynamically obtaining its IP address via DHCP.

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

The following hardware and storage resources are allocated to the Prowlarr container:

*   **VMID:** 104
*   **CPU Cores:** 2
*   **RAM:** 1024 MB
*   **Disk Space:** 3.86 GB
*   **Tags:** `arr-stack`, `community-script`

## Functional Role

Prowlarr functions as an automated media indexer and manager. Its core responsibility is to monitor disparate upstream media sources, such as torrent trackers or dedicated media indexers, to facilitate automated discovery and centralized organization.

By operating under the `arr-stack` tag, Prowlarr streamlines the upstream process of file acquisition and tracking. This automated workflow significantly enhances the efficiency of media acquisition and organization, serving as a foundational element for the homelab's media management system.