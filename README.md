# Unraid templates

Unraid Community Applications template for [Ultra Explorer](https://ultra-explorer.app), a file
explorer for cloud storage and NAS folders built on rclone.

- [`templates/ultra-explorer.xml`](templates/ultra-explorer.xml): Docker template for the
  `ghcr.io/sudo-rahman/ultra-explorer` image.
- [`ca_profile.xml`](ca_profile.xml): repository profile shown in Community Applications.

Before the first start, create the appdata folder with owner `nobody:users`:

```bash
mkdir -p /mnt/user/appdata/ultra-explorer && chown 99:100 /mnt/user/appdata/ultra-explorer
```

Report problems on the [release repository](https://github.com/Sudo-Rahman/UltraExplorer-Releases/issues).

The MIT license of this repository covers the template files only. Ultra Explorer itself is
distributed under its own license.
