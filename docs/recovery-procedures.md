# Recovery Procedures

## Emergency Mode Protection

System configured to require root passowrd using sulogin.

## Break-Glass Procedure

1. Attach RHEL ISO
2. Boot into rescue mode
3. Mount system:
   chroot /mnt/sysimage
4. Reset credentials or fix configuration

## Auditing

Emergency access is logged via system logs and sudo logging.
