---
title: "uptimekuma"
vmid: 109
type: "LXC"
status: "running"
node: "pve"
cpu: 1
ram_gb: 1.0
disk_gb: 11.73
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 109 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 109 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 1 |
| **RAM** | 1.0 GB |
| **Disk** | 11.73 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

This document details the deployment and usage of the uptimekuma monitoring system running on VMID 109.

uptimekuma is a comprehensive and user-friendly monitoring dashboard designed to provide a holistic overview of the health and performance of your homelab infrastructure. It aggregates data from various sources, allowing users to visualize system metrics, service statuses, and resource utilization in a single, cohesive interface. In a homelab environment, uptimekuma serves as the central control panel, transforming complex raw metrics into actionable insights necessary for effective system management and proactive troubleshooting.

## Purpose
This container provides an easy-to-read interface for centralized system monitoring. It allows users to quickly assess the operational status of all services, applications, and underlying infrastructure from a single dashboard. This greatly reduces the time spent manually checking logs and metrics, making homelab management more efficient and less stressful.

## Key Features
*   Centralized Dashboard: Provides a beautiful, intuitive interface for viewing system health and service status.
*   Multi-Source Integration: Connects with various monitoring tools (like Prometheus and various exporters) to aggregate diverse data streams.
*   Real-time Visualization: Displays dynamic graphs and metrics, offering immediate insight into system performance.
*   Service Overview: Offers a clear, organized view of all configured services, making it easy to track dependencies.

## Operational Notes
*   Ensure necessary monitoring components (like Prometheus) are running and accessible before attempting to configure uptimekuma.
*   Since uptimekuma relies on external data sources, periodically check the application logs for any connection errors or failed metric pulls if the dashboard data appears stale.
*   Given its role as a monitoring tool, ensure sufficient resources (RAM/CPU) are allocated to the VM to handle data processing efficiently, especially as more metrics are added over time.

## Suggested Tags
monitoring
automation
networking
development
productivity

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:8C:8D:A1,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-109-disk-0,size=12G` |

> Add manual notes here.
