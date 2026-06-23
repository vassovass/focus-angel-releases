# Focus Angel releases

This public repository is the release channel for Focus Angel, a local Windows focus monitor. It holds:

- `latest.json`: the auto-update manifest (version, installer URL, sha256).
- Release assets: the per-user installer `focus-buddy-setup.exe` on each tagged release.

The application source code is private. Focus Angel checks `latest.json` here, verifies the installer sha256 over HTTPS, and silently upgrades in place (no admin, no manual reinstall). To install or update by hand, download the installer from the latest release and run it.
