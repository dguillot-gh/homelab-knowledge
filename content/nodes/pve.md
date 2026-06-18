---
title: "Node: pve"
updated: "2026-06-18 14:07 UTC"
type: "docs"
---

The system is configured as a Proxmox Virtual Environment (PVE) node, serving as the central hypervisor in the homelab environment. Running a customized Linux kernel (version 6.17.13-3-pve) optimized for virtualization tasks, this machine is responsible for managing and allocating resources to various virtual machines and containers. The hostname pve clearly identifies its role as the core management platform controlling the virtualized infrastructure.

The underlying hardware provides a solid foundation for virtualization. The system utilizes a 6-core Intel Core i5-8500T processor clocked at 2.10GHz, offering sufficient processing power for running multiple VMs concurrently. Memory capacity is substantial, with 31.0 GB of total RAM installed, currently with 8.6 GB actively utilized by the operating system, leaving ample resources available for guest operating systems.

## Health Snapshot
- **CPU Usage:** 11.5%
- **Load Avg (1/5/15):** 1.70 / 1.51 / 2.06
- **Memory:** 8.6 / 31.0 GB (27.7%)
- **Root FS:** 29.5 / 64.06 GB (46.0%)

## Hardware
- **CPU:** Intel(R) Core(TM) i5-8500T CPU @ 2.10GHz
- **Cores / Sockets:** 6 / 1
- **Kernel:** Linux 6.17.13-3-pve #1 SMP PREEMPT_DYNAMIC PMX 6.17.13-3 (2026-03-31T21:50Z)

## Storage Pools
| Name | Type | Total | Used | Free |
|---|---|---:|---:|---:|
| TGroup1 | lvm | 953.87 GB | 565.0 GB | 388.87 GB |
| samsung256 | lvm | 0.0 GB | 0.0 GB | 0.0 GB |
| local-lvm | lvmthin | 130.27 GB | 0.0 GB | 130.27 GB |
| local | dir | 64.06 GB | 29.5 GB | 31.26 GB |
| backupnfs | nfs | 14708.41 GB | 9544.12 GB | 5164.21 GB |
