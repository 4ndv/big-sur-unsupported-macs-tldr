# mount /: failed with 66

This is because Big Sur boots off snapshot, instead of directly booting from the disk.

Here's ASentientBot's solution for this problem:

https://forums.macrumors.com/threads/macos-11-big-sur-on-unsupported-macs-thread.2242172/post-28603788

Sometimes there are necessary to also delete all the snapshots after doing that, here's the guide:

https://forums.macrumors.com/threads/macos-11-big-sur-on-unsupported-macs-thread.2242172/post-28604333
