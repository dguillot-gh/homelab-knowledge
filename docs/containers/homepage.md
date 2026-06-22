
# `homepage` LXC Container Documentation

## Summary

This document provides details regarding the configuration, purpose, and technical specifications of the `homepage` Lightweight Virtual Machine (LXC) deployed within the homelab environment.

---

## Overview

The `homepage` container (VMID 117) serves as a dedicated, resource-efficient execution environment. It is designed to function as a centralized hub and execution platform for managing and monitoring community-based scripts, drawing functionality from external projects such as `community-scripts.org`.

This container is optimized for specialized task execution rather than general server operations, providing a stable and focused environment for automated management tasks within the Proxmox infrastructure.

## Purpose

The primary function of this LXC is to act as a centralized dashboard and runner. By hosting this container, the homelab user gains an easily accessible point of control and monitoring for automated scripts. This simplifies management, centralizes operational oversight, and provides a cohesive view of community-driven systems within the Proxmox environment.

## Technical Specifications

### General Configuration

| Attribute | Detail |
| :--- | :--- |
| **Container Name** | `homepage` |
| **VMID** | 117 |
| **Node** | `pve` |
| **Container Type** | LXC |
| **Status** | running |
| **IP Configuration** | DHCP |
| **Last Updated** | 2026-06-18 14:07 UTC |

### Resource Allocation

The container is provisioned with specific resource limits tailored for specialized scripting tasks:

| Resource | Specification |
| :--- | :--- |
| **Operating System** | Debian |
| **Memory (RAM)** | 4096 MB |
| **CPU Cores** | 2 |
| **Disk Usage** | 5.82 GB |

### Tags

The container is categorized with the following tags for easier management and identification:
*   `community-script`
*   `dashboard`