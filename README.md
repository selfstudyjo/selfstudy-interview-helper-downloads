# SelfStudyJo Interview Helper - downloads

This repository holds **installers only** (no source code) for the SelfStudyJo
Interview Helper, a desktop app for Arabic speakers in the HR part of an English
job interview. It listens to the interviewer on Zoom, Teams or Meet through your
computer's audio and shows a short answer in simple English plus the question in
Arabic. Signing in needs a SelfStudyJo account with the AI feature.

More: https://selfstudyjo.com/#/interview-helper

## Download the latest version

| System | File |
|---|---|
| Windows 10/11 (64-bit) | [SelfStudy-Interview-Helper-Windows.exe](https://github.com/selfstudyjo/selfstudy-interview-helper-downloads/releases/latest/download/SelfStudy-Interview-Helper-Windows.exe) |
| macOS, Apple silicon (M1 and later) | [SelfStudy-Interview-Helper-macOS-arm64.dmg](https://github.com/selfstudyjo/selfstudy-interview-helper-downloads/releases/latest/download/SelfStudy-Interview-Helper-macOS-arm64.dmg) |
| macOS, Intel | [SelfStudy-Interview-Helper-macOS-x64.dmg](https://github.com/selfstudyjo/selfstudy-interview-helper-downloads/releases/latest/download/SelfStudy-Interview-Helper-macOS-x64.dmg) |
| Linux (any distribution) | [SelfStudy-Interview-Helper-Linux.AppImage](https://github.com/selfstudyjo/selfstudy-interview-helper-downloads/releases/latest/download/SelfStudy-Interview-Helper-Linux.AppImage) |
| Debian / Ubuntu | [SelfStudy-Interview-Helper-Linux.deb](https://github.com/selfstudyjo/selfstudy-interview-helper-downloads/releases/latest/download/SelfStudy-Interview-Helper-Linux.deb) |

Every version is listed under [Releases](https://github.com/selfstudyjo/selfstudy-interview-helper-downloads/releases).

## Installing

The installers are not code-signed yet, so your system will warn you the first time.

- **Windows:** run the `.exe`. If SmartScreen says "Windows protected your PC",
  click **More info**, then **Run anyway**.
- **macOS:** open the `.dmg` and drag the app to Applications. The first time,
  **right-click** (or Control-click) the app, choose **Open**, then **Open** again.
  If macOS still refuses, open System Settings -> Privacy & Security and click
  **Open Anyway**.
- **Linux AppImage:** `chmod +x SelfStudy-Interview-Helper-Linux.AppImage`, then run it.
- **Debian / Ubuntu:** `sudo apt install ./SelfStudy-Interview-Helper-Linux.deb`.

This repository is filled automatically by the release workflow of the (private)
source repository. Do not edit it by hand: the next release overwrites it.
