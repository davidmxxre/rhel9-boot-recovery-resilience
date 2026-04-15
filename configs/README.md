# Boot Security Preparations

1. Take a snapshot of virtual machine state before continuing lab
2. Ensure GRUB_ENABLE_BLSCFG=true
   grep GRUB_ENABLE_BLSCFG /etc/default/grub

3. Create GRUB Superuser
  grub2-mkconfig-pbkdf2
  Enter password
  Confirm password

4. COPY HASH
