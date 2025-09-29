# Security

---

## Accounts
- Created non-root admin user for daily tasks
- Root account restricted

---

## Network Security
- **UI Access**: LAN-only
- **Remote Access**: Tailscale VPN configured
- **Firewall**: Default deny-all, only SMB/NFS/Tailscale allowed

---

## Storage Security
- ZFS encryption: [Enabled]
- Datasets separated by user/group permissions
- SMB shares restricted to authenticated users

---

## Additional Hardening
- Disabled SSH password login (keys only)
- Disabled unused services
- Regular update policy: check monthly
