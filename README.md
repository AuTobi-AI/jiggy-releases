# Jiggy desktop downloads

Jiggy is a Windows desktop workspace for projects and multi-agent development, with a project library, isolated files and memory, a Markdown notebook, model selection and swarm workflows.

**[Download the latest Windows x64 installer](https://github.com/AuTobi-AI/jiggy-releases/releases/latest)**

Open the latest release and download its `Jiggy-Setup-<version>-x64.exe` file. Run the installer, then open Jiggy from the Start menu or desktop. Git is included. AI providers may require their own accounts, subscriptions, API keys or command-line tools; Blender workflows require Blender.

## Automatic updates

Version 0.3.1 and later include the public update connection. Jiggy checks for releases, downloads updates in the background, and offers **Restart to install** or **Later**. It waits until active work is finished, saves workspace edits before restarting, and never installs merely because you close the app.

If you have 0.3.0 or an earlier build, install the latest release once to enable automatic updates. Future updates use the same download address.

Projects, notes, settings and history stay in `%LOCALAPPDATA%\Jiggy\data`, separate from the installed program. You can continue locally without a Jiggy account. Local swarms require your PC to remain on; hosted swarm execution is not included.

The current installer is unsigned, so Windows may identify its publisher as unknown. This repository is the official download location. Each release includes a SHA-256 checksum file; the updater also verifies installer SHA-512 checksums.

## Release files

- `Jiggy-Setup-<version>-x64.exe`: Windows installer.
- `latest.yml` and `.blockmap`: used by automatic updates.
- `SHA256SUMS.txt`: checksums for the published files.

The update feed is [latest.yml](https://github.com/AuTobi-AI/jiggy-releases/releases/latest/download/latest.yml). Versioned installers remain attached to their original releases. This repository contains download information and release files; development history and user data are not published here.

Third-party notices and licenses are included with the application, including Electron, Chromium and the bundled Git for Windows runtime. [Git for Windows source and release](https://github.com/git-for-windows/git/releases/tag/v2.56.0.windows.2).
