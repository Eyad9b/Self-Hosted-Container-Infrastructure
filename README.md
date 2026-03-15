# Self-Hosted-Container-Infrastructure
Designed and deployed a self-hosted infrastructure to manage multiple services using containerization and secure remote access. The system allows centralized container management and secure connectivity from anywhere
Technologies Used

- Docker
- Portainer
- Tailscale
- TSDProxy
- Docker Compose
- Linux Server

Architecture

- Installed a Linux server to host containerized applications.

- Installed Docker to run and manage containers.

- Deployed Portainer for web-based container management.

- Configured Tailscale VPN to securely access services remotely.

- Implemented TSDProxy to expose services via domain names instead of IP:port.

- Managed container deployments using Docker Compose.

Implementation Steps
1. Linux Server Setup

Installed and configured a Linux server environment to host the container infrastructure.

2. Container Runtime Installation

Installed Docker and Docker Compose to enable container deployment and service orchestration.

3. Container Management Platform

Deployed Portainer to provide a graphical interface for managing containers, images, volumes, and networks.

4. Secure Remote Access

Configured Tailscale VPN to securely access internal services from outside the local network without exposing ports to the internet.

5. Reverse Proxy Integration

Deployed TSDProxy to automatically create internal domain names for services and simplify access.

6. Service Deployment

Deployed multiple services using Docker containers and managed them through Portainer.
