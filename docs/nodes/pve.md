
---
title: "Proxmox Virtual Environment (PVE) Node: pve"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

# Proxmox Virtual Environment (PVE) Node: `pve`

This document details the configuration, hardware specifications, operational status, and storage management for the central Proxmox Virtual Environment (PVE) host, designated as `pve`. This node serves as the core hypervisor and management platform, responsible for orchestrating all resource allocation and virtualization tasks within the homelab infrastructure.

## System Overview

The `pve` host operates on a customized Linux kernel optimized for virtualization and container management. It functions as the central control plane, providing the foundational services necessary for the entire virtualized environment, including VM and container management, networking, and storage provisioning.

## Hardware Specifications

The physical configuration provides the necessary resources for hosting the virtualization workload.

| Component | Specification | Details |
| :--- | :--- | :--- |
| **Processor (CPU)** | Intel(R) Core(TM) i5-8500T @ 2.10GHz | 6 Cores / 1 Socket |
| **Memory (RAM)** | 31.0 GB Total | Allocated for host operations, hypervisor processes, and VM resources. |
| **Kernel** | Linux 6.17.13-3-pve #1 SMP PREEMPT_DYNAMIC PMX | Virtualization-optimized kernel customized for PVE. |

## Operational Health Snapshot

The following metrics represent the current resource utilization and system load on the host.

| Metric | Value | Context |
| :--- | :--- | :--- |
| **CPU Utilization** | 11.5% | Current percentage of CPU time being utilized by processes. |
| **Load Average** | 1.70 / 1.51 / 2.06 | Average system load over the last 1, 5, and 15 minutes, respectively. |
| **Memory Utilization** | 8.6 GB / 31.0 GB (27.7%) | Active memory usage relative to the total installed RAM. |
| **Root Filesystem Usage** | 29.5 GB / 64.06 GB (46.0%) | Usage of the primary root partition. |

## Storage Configuration (LVM & Filesystems)

Storage is managed using a combination of Logical Volume Management (LVM) and various filesystem types (NFS, Directory) to ensure robust data persistence and flexible management of virtual machine storage.

### Storage Pools Summary

The following table summarizes the configuration of all defined storage volumes and pools:

| Pool Name | Type | Total Capacity | Used Space | Free Space | Purpose / Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **backupnfs** | NFS | 14,708.41 GB | 9,544.12 GB | 5,164.21 GB | Large shared volume dedicated to external backup data via NFS protocol. |
| **TGroup1** | LVM Volume Group | 953.87 GB | 565.0 GB | 388.87 GB | Primary Logical Volume pool for host system files and general VM data storage. |
| **local-lvm** | LVMThin | 130.27 GB | 0.0 GB | 130.27 GB | LVMThin provisioned volume, optimized for high-performance VM disk storage. |
| **local** | Directory | 64.06 GB | 29.5 GB | 31.26 GB | Local filesystem storage for system configuration, logs, and host files. |
| **samsung256** | LVM Volume Group | 0.0 GB | 0.0 GB | 0.0 GB | Uninitialized or unallocated LVM pool, reserved for future expansion. |