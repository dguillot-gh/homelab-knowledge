
# Container Services Overview

This document provides an inventory and detailed overview of the services and applications deployed within the homelab environment. These services are containerized using a combination of LXC and Docker technologies, ensuring modularity, strong isolation, scalability, and ease of management.

## Core Infrastructure

The following services form the foundational infrastructure necessary for the operation, networking, and automation of the homelab environment.

| Service | Category | Purpose | Description |
| :--- | :--- | :--- | :--- |
| **Docker** | Infrastructure | Container Engine | The core platform utilized for running, deploying, and orchestrating all containerized applications, providing essential isolation and resource management. |
| **Databasus** | Data Storage | Persistent Storage | Primary database instance responsible for persistent storage of application data, configuration files, and operational metadata across the environment. |
| **Ansible** | Automation | Configuration Management | Used for system automation, configuration management, infrastructure setup, and deployment orchestration across the host systems and containers. |
| **Caddy** | Networking | Reverse Proxy & SSL | Functions as the secure reverse proxy, managing incoming external traffic, handling load balancing, and performing SSL/TLS termination for internal services. |
| **TailscaleCity** | Networking | Secure VPN/Networking | Implements a secure Virtual Private Network (VPN) infrastructure, enabling secure, peer-to-peer network access and encrypted connectivity across all devices within the homelab. |
| **Syncthing** | File Synchronization | Decentralized Sync | Provides a decentralized, secure, and peer-to-peer file synchronization mechanism, ensuring seamless file sharing across all connected homelab devices. |

## Media and Automation Ecosystem

This section details the applications dedicated to media management, streaming, synchronization, and continuous deployment.

| Service | Category | Purpose | Description |
| :--- | :--- | :--- | :--- |
| **Jellyfin** | Media Server | Media Management | Centralized platform for organizing, streaming, and serving multimedia content (movies, TV shows, photos) to users via a standardized interface. |
| **Navidrome** | Media Server | Music Streaming | Dedicated server for streaming, managing, and organizing personal music collections, integrated seamlessly within the overall media ecosystem. |
| **Tunarr** | Media Streaming | Live TV Management | Manages and streams live television content from various external sources, integrating TV content into the central media server. |
| **Fileflows** | Processing | Media Transcoding | Dedicated service responsible for the efficient, scalable transcoding and processing of various media file formats, optimizing performance for media playback. |
| **Radarr** | Media Management | Movie Automation | Application dedicated to automated organization, management, and acquisition of movies, integrating with indexers and download clients. |
| **Sonarr** | Media Management | TV Automation | Application dedicated to automated organization, management, and acquisition of television series, integrating with indexers and download clients. |
| **Lidarr** | Media Management | Music Automation | Application dedicated to automated organization, management, and acquisition of music collections, integrating with indexers and download clients. |
| **Prowlarr** | Media Indexing | Indexer Manager | Centralized management tool for coordinating, configuring, and connecting various media indexers (e.g., Prowlarr, Torrents, TV indexers) for unified searching. |
| **GitHub Runner** | CI/CD | Automation Execution | Dedicated environment utilized for executing Continuous Integration and Continuous Deployment (CI/CD) workflows, automating the build and deployment processes. |
| **Gitea** | Version Control | Self-hosted Git | Self-hosted platform providing version control, repository management, and complete Git operations for managing code and configuration files. |
| **Gitea Mirror** | Version Control Synchronization | Creates a mirrored instance of a Git repository, facilitating synchronization, backup, and disaster recovery across different instances. |
| **Argus** | System Monitoring & Alerting | A comprehensive system monitoring solution that provides deep insights into host performance, resource utilization, and service health, including proactive alerting. |
| **Pulse** | Real-time Monitoring | Delivers real-time monitoring of system health, resource usage (CPU, memory, I/O), and performance metrics for immediate operational awareness. |
| **Uptime Kuma** | Availability Tracking | A dedicated tool for monitoring the availability and uptime status of critical services and endpoints within the homelab environment. |
| **Open WebUI** | AI Interaction Interface | A user-friendly interface providing access and streamlined interaction capabilities with various integrated AI chat models. |
| **Homepage** | Central Dashboard & Management | The centralized web interface serving as the main dashboard for an overall status overview, management, and visualization of the entire homelab environment. |