# Availability Controls

## Service Auto-Restart

Configured via systemd override:

Restart=on-failure
RestartSec=5s

## System Health Validation

systemctl is-failed
systemctl --failed

## Notes

Hardware watchdog not implemented due to virtualization constraints.
