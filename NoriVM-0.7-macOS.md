## Nori 0.7

- Adds a live estimated time remaining to Windows ISO downloads.
- Shows the measured transfer rate beside the ETA, for example `12.5 MB/s · About 6 min remaining`.
- Uses the cumulative average throughput to keep the estimate stable as download ranges complete.
- Displays “Calculating time remaining…” until enough real transfer data is available.
- Keeps the four-stream accelerated downloader, cancellation, range verification, and partial-file cleanup from Nori 0.6.
