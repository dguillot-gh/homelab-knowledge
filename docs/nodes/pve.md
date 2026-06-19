
---
title: "Node: pve"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

# Proxmox Virtual Environment (PVE) Node: pve

This document details the configuration, hardware specifications, health status, and storage management of the central Proxmox Virtual Environment (PVE) node, identified as `pve`. This machine serves as the core hypervisor for the homelab environment, responsible for managing and allocating resources to all virtual machines and containers.

## System Overview

The operating system is a customized Linux kernel optimized for virtualization tasks. This node functions as the central management platform, providing the foundation for the entire virtualized infrastructure.

## Hardware Specifications

The underlying hardware provides the necessary foundation for virtualization and resource allocation.

*   **Processor (CPU):** Intel(R) Core(TM) i5-8500T @ 2.10GHz
*   **Cores / Sockets:** 6 Cores / 1 Socket
*   **Kernel:** Linux 6.17.13-3-pve #1 SMP PREEMPT_DYNAMIC PMX 6.17.13-3 (2026-03-31T21:50Z)
*   **Memory (RAM):** 31.0 GB Total

## Health Snapshot

The following metrics provide a real-time assessment of the system's current resource utilization.

| Metric | Value | Notes |
| :--- | :--- | :--- |
| **CPU Usage** | 11.5% | Current load on the CPU. |
| **Load Average (1/5/15 min)** | 1.70 / 1.51 / 2.06 | Average load over the last 1, 5, and 15 minutes. |
| **Memory Utilization** | 8.6 GB / 31.0 GB (27.7%) | Active memory usage relative to total capacity. |
| **Root File System Usage** | 29.5 GB / 64.06 GB (46.0%) | Usage of the root partition. |

## Storage Pools

The node utilizes several storage pools managed via LVM and NFS for data persistence and backup.

| Name | Type | Total Capacity | Used Space | Free Space | Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **backupnfs** | NFS | 14,708.41 GB | 9,544.12 GB | 5,164.21 GB | Large NFS volume for backups. |
| **TGroup1** | LVM | 953.87 GB | 565.0 GB | 388.87 GB | Primary LVM volume pool. |
| **local-lvm** | LVMthin | 130.27 GB | 0.0 GB | 130.27 GB | LVMThin provisioned volume. |
| **local** | Directory | 64.06 GB | 29.5 GB | 31.26 GB | Local filesystem storage. |
| **samsung256** | LVM | 0.0 GB | 0.0 GB | 0.0 GB | Unallocated or uninitialized LVM pool. |