
---
title: "Proxmox Virtual Environment (PVE) Node: pve"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

# Proxmox Virtual Environment (PVE) Node: `pve`

This document provides a detailed overview of the configuration, hardware specifications, operational health, and storage management for the central Proxmox Virtual Environment (PVE) host, designated as `pve`. This node serves as the core hypervisor, managing all resource allocation and virtualization tasks for the homelab infrastructure.

## System Overview

The host is running a customized Linux kernel optimized for virtualization and container management. It functions as the central management platform, providing the foundational services necessary for the entire virtualized environment.

## Hardware Specifications

The physical hardware configuration supports the virtualization workload and resource demands.

| Component | Specification | Details |
| :--- | :--- | :--- |
| **Processor (CPU)** | Intel(R) Core(TM) i5-8500T @ 2.10GHz | 6 Cores / 1 Socket |
| **Memory (RAM)** | 31.0 GB Total | Allocated for host operations and VM resources. |
| **Kernel** | Linux 6.17.13-3-pve #1 SMP PREEMPT_DYNAMIC PMX | Virtualization-optimized kernel. |

## Operational Health Snapshot

The following metrics represent the real-time resource utilization of the system.

| Metric | Value | Context |
| :--- | :--- | :--- |
| **CPU Utilization** | 11.5% | Current load on the CPU. |
| **Load Average** | 1.70 / 1.51 / 2.06 | Average system load over the last 1, 5, and 15 minutes, respectively. |
| **Memory Utilization** | 8.6 GB / 31.0 GB (27.7%) | Active memory usage relative to total available RAM. |
| **Root Filesystem Usage** | 29.5 GB / 64.06 GB (46.0%) | Usage of the primary root partition. |

## Storage Configuration (LVM & Filesystems)

Storage is managed using Logical Volume Management (LVM) combined with various filesystem types (NFS, LVM, Directory) to ensure data persistence and management.

### Storage Pools Summary

| Name | Type | Total Capacity | Used Space | Free Space | Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **backupnfs** | NFS | 14,708.41 GB | 9,544.12 GB | 5,164.21 GB | Large shared volume utilized for backup data (NFS). |
| **TGroup1** | LVM | 953.87 GB | 565.0 GB | 388.87 GB | Primary LVM volume pool for system and VM data. |
| **local-lvm** | LVMthin | 130.27 GB | 0.0 GB | 130.27 GB | LVMThin provisioned volume, optimized for VM storage. |
| **local** | Directory | 64.06 GB | 29.5 GB | 31.26 GB | Local filesystem storage for system files and configuration. |
| **samsung256** | LVM | 0.0 GB | 0.0 GB | 0.0 GB | Unallocated or uninitialized LVM pool. |