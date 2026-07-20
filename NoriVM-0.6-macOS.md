## Nori 0.6

- Adds an accelerated Windows ISO downloader using four secure HTTP range streams.
- Automatically verifies each downloaded range and the assembled ISO byte count.
- Keeps memory usage low by assembling the ISO from temporary files in 4 MB blocks.
- Adds a visible Cancel button and cleans up temporary download data when canceled.
- Continues to restrict ISO downloads to HTTPS Microsoft-controlled hosts.

Actual speed still depends on Microsoft’s CDN and the internet connection. In the live validation used for this release, accelerated throughput was roughly twice the previous single-stream transfer rate.
