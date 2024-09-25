### Description

Proxmox configuration for samba / plex / cron job to remount ssd

### Paths
```
/etc/fstab #mounts
/etc/samba/smb.conf #samba config
/usr/local/bin/ #execs
/etc/pve/qemu-server/ #lxc/qm configs (not vms)
```

### Commands
```
crontab -e #edit crons
remount-all
remount-all-logs
restart-only
restart-only-logs
```