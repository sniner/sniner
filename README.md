## Hi, I'm Stefan

Software developer based in Germany — mostly working in Python and Rust.
A small curated tour of my projects, since GitHub only lets me pin six:

### Python

- **[docuware-client](https://github.com/sniner/docuware-client)** — Client library for the DocuWare DMS REST API. Query archives, transfer documents, edit index fields, read OCR text; ships with a `dw-client` CLI for everyday tasks.
- **[docuware-mcp](https://github.com/sniner/docuware-mcp)** — MCP server that exposes DocuWare to LLM clients like Claude Desktop. Built on top of [docuware-client](https://github.com/sniner/docuware-client).
- **[jellyplex-sync](https://github.com/sniner/jellyplex-sync)** — Keeps Plex and Jellyfin movie libraries in sync through hardlinks — one file on disk, two frontends to enjoy it from.
- **[imapbackup](https://github.com/sniner/imapbackup)** — Back up and archive IMAP mailboxes. A local, searchable copy independent of your provider.

### Rust

- **[filebridge](https://github.com/sniner/filebridge)** — Lightweight, secure REST API for remote file access — for when FTP and SFTP feel like either too much or too little.
- **[revenant](https://github.com/sniner/revenant)** — Atomic Btrfs snapshots of the Linux root filesystem, EFI partition included. A safety net against bad updates.
- **[viddeck](https://github.com/sniner/viddeck)** — Fast, modern web frontend for browsing your video collection. Thumbnails, metadata, and inline playback, powered by ffmpeg.
- **[uwhat](https://github.com/sniner/uwhat)** — A human-friendly USB device lister — for when the output of `lsusb` makes your eyes glaze over.
- **[fifi](https://github.com/sniner/fifi)** — Finds identical files in directory trees. Fast, parallel, and hardlink-aware. Rust successor to [duplicates](https://github.com/sniner/duplicates), with xxh3 hashing and JSON output for scripting.
