
---
title: "radarr"
vmid: "102"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

# Radarr Media Management Service

This document provides a comprehensive overview and operational specification for the `radarr` container, a dedicated service deployed within the homelab environment for automated media management.

## Overview

The `radarr` container serves as the central media indexing and management service. Utilizing the Radarr application, its primary function is to automate the discovery, organization, and monitoring of personal media collections, specifically movies and television series. This setup significantly reduces manual overhead associated with managing large media libraries, ensuring consistency and automated organization.

## Technical Specifications

The `radarr` service is deployed within an LXC container environment on the virtualization host. The following details outline the container's configuration and resource allocation.

| Specification | Detail |
| :--- | :--- |
| **Service Name** | `radarr` |
| **Virtualization Type** | LXC Container |
| **Host Node** | pve |
| **Status** | Running |
| **Operating System** | Debian |
| **Container ID (VMID)** | 102 |
| **Network Configuration** | DHCP |
| **Resource Allocation** | |
| Memory (RAM) | 1024 MB |
| CPU Cores | 2 |
| Disk Space | 13.68 GB |
| **Tags** | `arr-stack`, `community-script` |

## Functional Description

Radarr executes a workflow designed to maintain an organized and up-to-date media library through automated processes. Its core functions include:

1.  **Media Indexing:** Continuously scans configured media sources (e.g., torrent trackers, remote file shares) to discover new content.
2.  **Organization:** Implements rules to categorize and organize discovered media based on user-defined criteria, such as series, movies, quality ratings, and release years.
3.  **Automation:** Automates the entire process of monitoring sources, managing download queues, and organizing final files, thereby ensuring the media library remains consistently updated and properly structured.

## System Resources Summary

| Resource | Value |
| :--- | :--- |
| **Host Node** | pve |
| **Container ID** | 102 |
| **OS** | Debian |
| **RAM** | 1024 MB |
| **CPU** | 2 Cores |
| **Disk Space** | 13.68 GB |
| **Network** | DHCP |
| **Tags** | `arr-stack`, `community-script` |