# My NAS Setup (Living Documentation)

This repo documents the build and configuration of my personal NAS.  
It focuses only on the NAS itself: hardware, OS, storage configuration, and services running directly on it.  
I use Git to track changes and expand the setup over time.

## Current Features
- RAID-protected storage for files
- Immich (self-hosted photo library)
- Dockerized services (Pi-hole, Tailscale, etc.)
- SMB file shares with user access control
- Regular backups and snapshots

## Repository Layout
- `docs/` → Documentation of setup and services
- `configs/` → Example configs and Docker Compose files
- `logs/` → Troubleshooting notes, fixes
- `roadmap/` → Future NAS improvements

## Roadmap
- Expand storage pools
- Automate backups (rsync or BorgBackup)
- Add media server (Plex/Jellyfin)
- Experiment with monitoring (Uptime Kuma, Grafana)
