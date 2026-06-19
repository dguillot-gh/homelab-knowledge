
---
title: "homepage"
vmid: "117"
node: "pve"
status: "running"
ip: "dhcp"
updated: "2026-06-18 14:07 UTC"
type: "lxc"
---

## Overview

The `homepage` container (VMID 117) is a specialized Lightweight Virtual Machine (LXC) deployed within the homelab environment. It is designed to serve as a centralized hub or execution environment for managing and monitoring community-based scripts.

This container runs a stable Debian operating system and is provisioned with 4096 MB of RAM and 2 CPU cores, providing an efficient platform for running specialized applications rather than general server functions.

## Purpose

The primary role of this LXC is to act as a centralized dashboard and runner, specifically facilitating the execution and management of community scripts, drawing resources from projects such as `community-scripts.org`. By hosting this container, the homelab user gains an easily accessible point of control and monitoring for automated scripts, simplifying management and providing a cohesive operational overview within the Proxmox environment.

## Technical Specifications

| Attribute | Detail |
| :--- | :--- |
| **VMID** | 117 |
| **Node** | pve |
| **Status** | running |
| **Operating System** | Debian |
| **Memory (RAM)** | 4096 MB |
| **CPU Cores** | 2 |
| **IP Address** | DHCP |
| **Disk Usage** | 5.82 GB |
| **Tags** | community-script, dashboard |