
---
title: "gitea-mirror"
vmid: "107"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "documentation"
---

# Gitea Mirror Service

The `gitea-mirror` container is a dedicated LXC environment deployed within the homelab infrastructure, designed to provide redundant synchronization services for Git repositories. It operates as a specialized service leveraging community-developed scripts to manage data mirroring efficiently.

## Overview

The primary function of the `gitea-mirror` container is to act as a redundant mirror for a primary Gitea instance. Its role is to create a synchronized, read-only copy of Git repositories, which significantly enhances data redundancy and ensures accessibility across the homelab environment. This setup supports the ability to maintain synchronized backups or alternative access points for critical code repositories, thereby improving the overall reliability and availability of self-hosted services.

## Container Specifications

| Attribute | Value |
| :--- | :--- |
| **Name** | gitea-mirror |
| **Type** | LXC Container |
| **Operating System** | Debian |
| **Host Node** | pve |
| **Status** | Running |
| **IP Address** | DHCP |
| **Resource Allocation** | |
| CPU Cores | 2 |
| RAM | 2 GB (2048 MB) |
| Storage | 5.82 GB |
| **Tags** | community-script, gitea, mirror |