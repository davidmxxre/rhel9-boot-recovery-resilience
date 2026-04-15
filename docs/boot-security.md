# Boot Process Security

## GRUB Hardening

- Superuser configured in GRUB
- Boot allowed without authentication
- Editing and command line require authentication

## Key Configuration

- /etc/grub.d/01_users
- /boot/loader/entries/*.conf

## Ctrl+Alt+Del

systemctl mask ctrl-alt-del.target
