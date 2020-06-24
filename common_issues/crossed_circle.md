# Crossed circle after several reboots

This happens because for boot on unsupported devices Big Sur requires `-no_compat_check` boot arg

Reboot into your Catalina installation (requires SIP disabled) or Recovery and run this command:

```bash
(sudo) nvram boot-args="-no_compat_check"
```

If running in Recovery, sudo is not required
