---
title: "ironclaw"
vmid: 115
type: "LXC"
status: "running"
node: "pve"
cpu: 2
ram_gb: 2.0
disk_gb: 7.78
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 115 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 115 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 7.78 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

ironclaw is a specialized container environment designed to serve as a central hub for automation, security monitoring, and AI-driven community scripts within a personal homelab. It acts as an agile platform for running essential services that manage infrastructure tasks, enhance overall system security, and facilitate complex, custom scripting projects.

## Purpose
ironclaw is primarily useful for consolidating specialized security tools, automation scripts, and AI agents into a single, manageable environment. It allows the homelabber to centralize complex tasks, improve operational efficiency, and experiment with cutting-edge community-developed solutions.

## Key Features
*   Runs as an LXC container, offering lightweight resource consumption and easy management.
*   Dedicated environment for hosting security agents and monitoring tools.
*   Platform for executing community-developed AI and automation scripts.
*   Optimized setup for running specialized agent services.

## Operational Notes
*   Regularly review the container logs to ensure all security agents and automation scripts are running without errors.
*   Ensure the container is regularly updated to benefit from the latest community scripts and security patches.
*   Since this is an agent-based system, verify network connectivity to ensure communication with other homelab services is functioning correctly.

## Suggested Tags
security
automation
agent
ai
community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:F0:C2:92,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-115-disk-0,size=8G` |

> Add manual notes here.
