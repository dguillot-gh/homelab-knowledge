
# Container Services Overview

This document provides an inventory and overview of the services and applications deployed within the homelab environment. These services are primarily containerized using LXC and Docker technologies, ensuring modularity, isolation, and scalability.

## Service Inventory

| Service | Category | Purpose | Description |
| :--- | :--- | :--- | :--- |
| **Docker** | Infrastructure | Host Environment | The core virtualization and container orchestration platform upon which all other services are deployed. |
| **Databasus** | Data Storage | Database Management | Primary instance utilized for persistent storage of application data, configuration files, and operational metadata. |
| **Ansible** | Automation | Configuration Management | Used for system automation, configuration management, deployment orchestration, and infrastructure setup across the host. |
| **Caddy** | Networking | Reverse Proxy | Functions as the secure reverse proxy, handling all incoming external traffic and managing SSL termination for internal services. |
| **TailscaleCity** | Networking | Secure VPN/Networking | Implements a secure Virtual Private Network (VPN) infrastructure, enabling secure, peer-to-peer network access and connectivity across devices. |
| **Syncthing** | File Synchronization | Decentralized Sync | Provides decentralized, secure, and peer-to-peer file synchronization across all connected homelab devices. |
| **Jellyfin** | Media Server | Media Management | Centralized platform for organizing, streaming, and serving multimedia content (movies, TV shows, photos). |
| **Navidrome** | Media Server | Music Streaming | Dedicated server for streaming and managing personal music collections, integrated within the media ecosystem. |
| **Tunarr** | Media Streaming | Live TV Management | Manages and streams live television content from various sources. |
| **Radarr** | Media Management | Movie Automation | Application dedicated to automated organization, management, and acquisition of movies based on user criteria. |
| **Sonarr** | Media Management | TV Automation | Application dedicated to automated organization, management, and acquisition of television series. |
| **Lidarr** | Media Management | Music Automation | Application dedicated to automated organization, management, and acquisition of music collections. |
| **Prowlarr** | Media Indexing | Indexer Manager | Centralized management tool for coordinating and connecting various media indexers (e.g., Torrents, TV indexers). |
| **Fileflows** | Processing | Media Transcoding | Dedicated service responsible for the efficient transcoding and processing of media files. |
| **GitHub Runner** | CI/CD | Automation Execution | Dedicated environment used for executing Continuous Integration and Continuous Deployment (CI/CD) workflows. |
| **Gitea** | Version Control | Self-hosted Git | Self-hosted platform providing version control, repository management, and Git operations. |
| **Gitea Mirror** | Version Control | Repository Synchronization | Provides a mirrored Git repository instance for synchronization and backup purposes. |
| **Argus** | Monitoring | System Monitoring | Comprehensive system monitoring and alerting service, providing deep insights into host performance and service health. |
| **Pulse** | Monitoring | Real-time Monitoring | Provides real-time system health, resource usage, and performance monitoring for immediate operational awareness. |
| **Uptime Kuma** | Monitoring | Availability Tracking | Tool for monitoring the availability and uptime status of critical services. |
| **Open WebUI** | AI Interface | AI Interaction | User interface providing access and interaction capabilities with various AI chat models. |
| **Homepage** | Dashboard | Central Dashboard | Centralized web interface providing an overall status, overview, and management of the entire homelab environment. |