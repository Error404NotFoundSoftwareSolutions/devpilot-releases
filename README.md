# DevPilot

**Learn real engineering tools with guided labs and an AI mentor.** Tell DevPilot what you want to learn, or paste a job
description. It plans a path, finds the videos, opens hands-on labs in VS Code and checks your work on your own
computer. The tutor gives hints, never finished answers. Finish a lab and claim a credential that says plainly how it
was checked.

This repository holds the downloadable app only. The source code is private.

## Download

**[DevPilot for Linux (x64), preview](https://github.com/Error404NotFoundSoftwareSolutions/devpilot-releases/releases)**,
see the release page for the file and its SHA-256 checksum. Windows and macOS are coming later.

## Install on Linux

```bash
tar -xzf devpilot-linux-x64.tar.gz
cd devpilot
./install.sh      # optional: adds DevPilot, with its icon, to your applications menu
./devpilot
```

Check the download first if you like:

```bash
sha256sum -c devpilot-linux-x64.tar.gz.sha256
```

**You need:** a 64-bit Linux desktop (GTK 3), [VS Code](https://code.visualstudio.com/) with the `code` command, Python
3.10 or newer, Git, and an internet connection. Sign in with email or with Google.

## What to expect from the preview

- Learning paths, videos, the tutor and the interview coach use the online DevPilot service.
- Lab code runs on your own computer, inside the lab folder.
- There are no automatic updates yet: download the newest release from this page.
- The package is not signed. Verify it with the checksum above.

## Problems or ideas

Open an [issue](https://github.com/Error404NotFoundSoftwareSolutions/devpilot-releases/issues). Please don't paste
passwords, tokens or private code into issues.
