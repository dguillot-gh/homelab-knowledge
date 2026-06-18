---
title: "databasus"
vmid: 116
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

**Status:** Running | **VMID:** 116 | **Type:** LXC

## At a Glance

| Property | Value |
|---|---|
| **VMID** | 116 |
| **Type** | LXC |
| **Status** | running |
| **CPU Cores** | 2 |
| **RAM** | 2.0 GB |
| **Disk** | 7.78 GB |
| **Auto Start** | Yes |
| **Tags** | ## Suggested Tags |

This documentation describes the `databasus` container/VM, a dedicated environment for running a PostgreSQL database instance within the homelab. It serves as a persistent, isolated location for storing critical application data, enabling the deployment and management of various services that require robust relational data management.

## Purpose
This instance provides a reliable and isolated environment for hosting a PostgreSQL database. It is essential in a homelab for practicing database administration, learning data persistence, and serving as the backend for various home automation or development projects.

## Key Features
*   **PostgreSQL Database:** Provides a robust, open-source relational database system for data storage and management.
*   **Data Persistence:** Ensures that all stored data remains intact and accessible, regardless of container lifecycle.
*   **Resource Efficiency:** Runs efficiently within a lightweight LXC container environment, optimizing resource usage on the host machine.
*   **Application Backend:** Serves as a foundational data store for connecting external services and applications deployed in the homelab.

## Operational Notes
*   **Regular Backups are Mandatory:** Since this holds critical data, configure an automated backup routine immediately to ensure data safety against hardware failure or accidental deletion.
*   **Monitor Resource Usage:** Keep an eye on CPU and RAM consumption, especially during peak usage times, to ensure the database remains responsive and does not impact other homelab services.
*   **Secure Access:** Implement strong access controls (e.g., using SSL/TLS and restricted network access) to protect the sensitive data stored within the database.

## Suggested Tags
database, backup, storage, development, community-script

## Network

| Interface | Config |
|---|---|
| net0 | `name=eth0,bridge=vmbr0,hwaddr=BC:24:11:0E:70:76,ip=dhcp,type=veth` |

## Storage

| Device | Config |
|---|---|
| rootfs | `TGroup1:vm-116-disk-0,size=8G` |

> Add manual notes here.
