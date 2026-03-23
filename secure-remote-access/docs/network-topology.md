# Network Topology

## Overview
This setup uses Tailscale to create a secure peer-to-peer network between multiple devices.

## Devices
- Admin Laptop (Windows)
- Linux File Server (Samba + SSH)
- Monitoring Node (Grafana/Prometheus)
- Mobile Client (Android)

## Architecture
- Mesh VPN (no central gateway required)
- Encrypted communication between all nodes
- No port forwarding necessary

## Benefits
- Secure remote access
- Easy scalability
- Minimal configuration overhead
