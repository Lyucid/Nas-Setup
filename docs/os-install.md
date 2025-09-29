# OS Installation

---

## ISO & Version
- **OS**: TrueNAS SCALE (e.g., 24.04 Dragonfish)
- **Source**: Official ISO (link)
- **Install Medium**: 16GB USB (flashed with Balena Etcher)

---

## BIOS/UEFI Settings
- Boot mode: UEFI
- SATA mode: AHCI
- Virtualization: Enabled (if planning VMs)

---

## Installation Steps
1. Booted from USB installer
2. Selected target boot drive: **ADATA SP550 256GB (sda)**
3. Configured initial root password
4. Installed with default partitioning

---

## Post-Install Setup
- Set **static IP** for NAS 
- Applied latest TrueNAS SCALE updates via Web UI
- Verified networking (ping + web dashboard)

