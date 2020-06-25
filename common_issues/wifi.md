# Wifi not working

Next steps depends on result of the `sudo mount -uw /` command:

### If it finishes successfully:

Follow this guide: https://forums.macrumors.com/threads/macos-11-big-sur-on-unsupported-macs-thread.2242172/page-23?post=28599729#post-28599729

### If it returns "failed with 66" error:

First, try to make root writable by following the guide from "[Common Issues -> mount /: failed with 66](common_issues/mount_failed_with_66.md)", then follow this guide:

If after that you're able to mount root with `sudo mount -uw /`, follow this guide: https://forums.macrumors.com/threads/macos-11-big-sur-on-unsupported-macs-thread.2242172/page-23?post=28599729#post-28599729

If not - there is my guide without making root mountable: https://medium.com/@andv/making-wifi-on-big-sur-unsupported-macs-with-failed-with-66-error-36c98e3f7965

### Wifi Adapters

Alternatively, you could use an USB Wifi Adapter, follow the information in [Guides -> USB Wifi Adapters](guides/usb_wifi.md)
