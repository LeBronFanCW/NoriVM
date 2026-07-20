# Nori 0.8

Turbo downloads make large official Windows ISOs arrive substantially faster.

- Uses eight independent, persistent Microsoft CDN streams for large Windows installers.
- Splits the ISO into smaller ranges so fast streams keep working instead of waiting on a slow range.
- Retries interrupted ranges automatically and validates every exact byte range before using it.
- Writes verified ranges directly into the final ISO, eliminating the old multi-gigabyte assembly copy.
- Shows Turbo stream count, transfer rate, progress, and estimated time remaining in the download panel.
- Keeps cancellation clean: active transfers stop and partial installer data is removed.

Nori still downloads directly from Microsoft and only accepts trusted HTTPS Microsoft hosts.
