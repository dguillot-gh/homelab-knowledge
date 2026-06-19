
# Container Services Overview

This document outlines the services and applications currently running within the homelab environment, primarily deployed using LXC containers and Docker.

| Container | Purpose | Description |
| :--- | :--- | :--- |
| [Docker](docker.md) | Host Environment | The core virtualization platform for running all containerized services. |
| [Databasus](databasus.md) | Data Storage | Primary database instance utilized for application data and configuration. |
| [Ansible](ansible.md) | Automation & Configuration | Used for system automation, configuration management, and deployment orchestration. |
| [Caddy](caddy.md) | Reverse Proxy | Serves as the reverse proxy, handling incoming traffic and SSL termination for internal services. |
| [TailscaleCity](tailscalecity.md) | Networking | Implements a secure virtual private network (VPN) for secure, peer-to-peer network access. |
| [Syncthing](syncthing.md) | File Synchronization | Provides decentralized, secure file synchronization across all connected devices. |
| [Jellyfin](jellyfin.md) | Media Server | Central media management platform for organizing, streaming, and serving media files. |
| [Navidrome](navidrome.md) | Music Streaming | Dedicated music streaming server integrated with the media ecosystem. |
| [Tunarr](tunarr.md) | Live TV Streaming | Manages and streams live television content. |
| [Radarr](radarr.md) | Movie Management | Application for automated organization, management, and acquisition of movies. |
| [Sonarr](sonarr.md) | TV Management | Application for automated organization, management, and acquisition of television shows. |
| [Lidarr](lidarr.md) | Music Management | Application for automated organization, management, and acquisition of music. |
| [Prowlarr](prowlarr.md) | Indexer Manager | Centralized management for connecting and coordinating various media indexers. |
| [Fileflows](fileflows.md) | Media Transcoding | Dedicated service for transcoding and processing media files. |
| [GitHub Runner](github-runner.md) | CI/CD Runner | Dedicated environment for executing Continuous Integration and Continuous Deployment workflows. |
| [Gitea](gitea.md) | Self-hosted Git | Self-hosted platform for version control and Git repository management. |
| [Gitea Mirror](gitea-mirror.md) | Git Mirror | Provides a mirrored Git repository for synchronization purposes. |
| [Argus](argus.md) | Monitoring | Comprehensive system monitoring and alerting service. |
| [Pulse](pulse.md) | Monitoring | Real-time system health and performance monitoring. |
| [Uptime Kuma](uptimekuma.md) | Uptime Monitoring | Tool for monitoring the availability and uptime of services. |
| [Open WebUI](openwebui.md) | AI Interface | User interface for accessing and interacting with AI chat models. |
| [Homepage](homepage.md) | Dashboard | Centralized dashboard providing an overview of the homelab status. |