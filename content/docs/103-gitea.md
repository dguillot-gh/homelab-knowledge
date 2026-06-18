---
title: "gitea"
vmid: 103
type: "LXC"
status: "running"
node: "pve"
cpu: 1
ram_gb: 1.0
disk_gb: 7.78
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 103 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 103 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 1 |
| **RAM** | 1.0 GB |
| **Disk** | 7.78 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

gitea is a self-hosted, open-source Git service that functions as a complete platform for version control, issue tracking, and project management. In a homelab environment, gitea serves as a crucial tool for centralizing the management of personal projects, scripts, and configurations, providing a private, self-controlled alternative to commercial platforms like GitHub or GitLab.

## Purpose
gitea provides a robust platform for self-managing development workflows and version control within the homelab. It allows users to host their private repositories and manage project progress entirely on local infrastructure, fostering a sense of control and security over sensitive data.

## Key Features
*   Self-hosted Git repository management for tracking code changes and project history.
*   Integrated issue tracking and project board functionality for managing tasks and collaborations.
*   Simple, clean web interface for easy access and management of repositories and user accounts.
*   Support for workflow automation via hooks and scripting integration.

## Operational Notes
*   Due to its lightweight nature, monitor the 1.0 GB RAM usage; ensure adequate resources are available for other services running on the same host.
*   Implement regular backups of the repository data and configuration files to protect against data loss.
*   Leverage the community-script tags to integrate gitea with other homelab automation tools for advanced workflow management.

## Suggested Tags
development, productivity, automation, git, community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:FA:B0:E8,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-103-disk-0,size=8G` |

> Add manual notes here.
