<p align="center">
  <img src="../ghost-term-client/src/assets/ghosterm-icon.svg" alt="Ghosterm logo" width="96" />
</p>

<h1 align="center">Ghosterm</h1>

<p align="center">
  A local-first desktop workspace for SSH, SFTP, host inventories, and optional cloud sync.
</p>

<p align="center">
  Ghosterm is built for operators, DevOps teams, and infrastructure engineers who need a cleaner way to manage servers, keys, groups, and file transfers without losing the reliability of local data.
</p>

## Why Ghosterm

Most terminal tools are great at opening a shell, but weak at organizing real operational work.

Ghosterm focuses on the layer around the terminal:

- Structured host inventories with groups and reusable credentials
- Multi-pane SSH workflows inside a desktop app
- Built-in SFTP for day-to-day file operations
- Local-first storage with optional cloud-backed vault sync
- Cross-platform delivery for desktop environments

## What is in this repository

This is the public GitHub-facing repository for Ghosterm.

It is intended to present the project at a high level without exposing private implementation details, internal infrastructure, or unpublished product internals.

## Core capabilities

### Desktop workspace

- Open SSH sessions in a dedicated desktop client
- Work with multiple tabs and split terminal panes
- Search inside terminal sessions
- Keep operational context inside a single workspace

### Hosts, groups, and keys

- Organize hosts into groups and nested structures
- Reuse credentials across environments
- Store hosts, groups, and key metadata locally
- Surface host context with OS-aware badges

### SFTP built for operations

- Browse local and remote files side by side
- Upload and download through the same workspace
- Search within the current path
- Use keyboard-friendly navigation and selection flows

### Local-first sync model

- SQLite remains available on the device
- Users can work offline and keep local access to their inventory
- When cloud mode is enabled, the client syncs with the API
- Sync state is reflected in the desktop experience

## Stack

- Desktop application
- Secure backend services
- Cloud-connected sync model
- Cross-platform delivery pipeline

## Current direction

Ghosterm is centered on a practical idea: keep terminal-based infrastructure work fast and local, then add cloud features only where they improve portability and team workflows.

That means the desktop experience remains the center of the product, while cloud capabilities support portability and team workflows where they add real value.

## Public repo note

This is a public repository. It should not contain secrets, private certificates, production credentials, internal endpoints, or environment files with real values.

## License

License information has not been added yet.
