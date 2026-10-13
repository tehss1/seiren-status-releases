# Seiren Status downloads

Seiren Status is a macOS controller for the Razer Seiren V3 Chroma microphone.
It manages idle, recording, and muted lighting, microphone gain, headphone
volume, and hardware sidetone.

Download the universal app for Apple silicon and Intel Macs from
[the latest release](https://github.com/tehss1/seiren-status-releases/releases/latest).
macOS 14 or later is required. Quit any running Seiren Status instance, extract the ZIP, install the app in Applications,
open it, and grant Input Monitoring access when prompted.

Version 0.3.0 adds automatic updates. Install it manually once if using 0.2.2.
The app checks on launch and hourly, downloads the latest stable update, and
installs it when the app quits. Choose Check for Updates to install and relaunch
immediately. Automatic checking and downloading can be changed in Updates.

Update feeds and archives are verified with Ed25519 signatures before
installation. GitHub builds use ad hoc signing and are not Apple-notarized;
macOS may require approval to open a downloaded app.

This repository contains downloads and documentation. The application source
remains private. No GitHub sign-in or token is needed to receive updates.
Update checks contact GitHub; microphone audio and diagnostics are not uploaded.
License and third-party notices are included in the app's Resources directory.
