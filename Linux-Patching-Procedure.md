# Linux Patching Procedure

## RHEL

dnf check-update
dnf upgrade -y

## SUSE

zypper refresh
zypper update -y

## Validation

- Reboot if required
- Check services
- Verify monitoring
