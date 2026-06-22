
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

## Introduction

The `gitea-mirror` container is a dedicated LXC environment deployed within the homelab infrastructure. Its primary function is to provide robust, redundant synchronization services for Git repositories, operating as a specialized service that leverages community-developed scripts to manage data mirroring efficiently.

## Service Overview

The core purpose of the `gitea-mirror` container is to establish a synchronized, read-only mirror of primary Gitea Git repositories. This implementation is designed to enhance data redundancy and ensure high availability across the homelab environment. By maintaining a synchronized copy, the service provides critical data accessibility and acts as an alternative access point, significantly improving the reliability and availability of self-hosted code management services.

## Container Specifications

### General Details

| Attribute | Value |
| :--- | :--- |
| **Container Name** | `gitea-mirror` |
| **Container Type** | LXC Container |
| **Operating System** | Debian |
| **Host Node** | `pve` |
| **Current Status** | Running |
| **IP Addressing** | DHCP |
| **Container ID (VMID)** | 107 |
| **Last Updated** | 2026-06-18 14:07 UTC |
| **Tags** | `community-script`, `gitea`, `mirror` |

### Resource Allocation and Storage

| Resource | Specification | Details |
| :--- | :--- | :--- |
| **CPU Cores** | 2 | Allocated for mirroring operations. |
| **RAM** | 2 GB (2048 MB) | Allocated for system operation and mirroring processes. |
| **Storage Size** | 5.82 GB | Total allocated disk space for container data. |