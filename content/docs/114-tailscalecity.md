---
title: "tailscalecity"
vmid: 114
type: "LXC"
status: "running"
node: "pve"
cpu: 1
ram_gb: 1.0
disk_gb: 9.75
onboot: "1"
tags: "## Suggested Tags"
updated: "2026-04-28 22:01 UTC"
---

**Status:** Running | **VMID:** 114 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 114 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 1 |
| **RAM** | 1.0 GB |
| **Disk** | 9.75 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

This container, tailscalecity, serves as a dedicated instance for running Tailscale, providing secure, zero-config networking and mesh capabilities across the homelab environment. Its primary role is to establish a secure overlay network, allowing devices to communicate securely regardless of physical location, which is crucial for segmented and secure homelab setups.

## Purpose
This instance is essential for securely connecting all homelab devices into a private, encrypted network. It facilitates secure peer-to-peer communication and simplifies network management by providing a unified access point for all services running on the host.

## Key Features
*   Provides a secure, zero-configuration VPN/overlay mesh network for all homelab devices.
*   Simplifies device discovery and access management across the network.
*   Implements strong, end-to-end encryption for all network traffic.
*   Acts as a central node for secure networking within the home lab environment.

## Operational Notes
*   Ensure that all critical services are running on the Tailscale network before attempting to access them remotely.
*   Keep the Tailscale service updated regularly to ensure the latest security patches and feature enhancements.
*   Use Tailscale's subnet routing capabilities to ensure that traffic flows efficiently and securely between internal machines.

## Suggested Tags
networking, security, automation, tailscale, community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:65:C8:8A,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-114-disk-0,size=10G` |

> Add manual notes here.
