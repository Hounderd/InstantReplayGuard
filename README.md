# Instant Replay Guard

[![Release](https://img.shields.io/github/v/release/Hounderd/InstantReplayGuard?display_name=tag&style=for-the-badge)](https://github.com/Hounderd/InstantReplayGuard/releases)
[![Windows](https://img.shields.io/badge/platform-Windows%2010%2F11-0A84FF?style=for-the-badge)](https://guard.nodd.dev)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-Scan-2F6FED?style=for-the-badge)](https://www.virustotal.com/gui/file/24366211ee7c936b25cdc44a1b7448d408997484b02fcc7cc5234186868f5fdc)

Public releases and issue tracking for **Instant Replay Guard**.

Instant Replay Guard is a lightweight Windows tray app that keeps NVIDIA Instant Replay from silently turning itself off, so you stop losing clips after restarts, overlay resets, or NVIDIA hiccups.

## Quick Links

- Website: https://guard.nodd.dev
- GitHub Releases: https://github.com/Hounderd/InstantReplayGuard/releases
- VirusTotal scan: https://www.virustotal.com/gui/file/24366211ee7c936b25cdc44a1b7448d408997484b02fcc7cc5234186868f5fdc
- Tip jar: https://ko-fi.com/hounderd

## What Instant Replay Guard does

- keeps Instant Replay alive in the background
- re-enables it if NVIDIA silently drops it
- runs locally on your machine with no account or cloud sync
- stays outside the game process entirely
- sits in the tray and uses negligible CPU when idle
- supports process-aware keepalive modes for app-specific behavior
- includes pause and exclusive app rules for whitelist-style control

## Hotkey requirement

Instant Replay Guard uses NVIDIA's currently configured Instant Replay toggle shortcut.

- it does not require the default NVIDIA keybind
- the `DVRToggle` hotkey does need to exist in NVIDIA settings
- if that shortcut is unbound or invalid, Guard cannot toggle Instant Replay

## Safety

- no account
- no telemetry
- no cloud sync
- no game memory interaction

## Support

If you hit a bug or edge case, open an issue and include:

- your Windows version
- NVIDIA app version
- whether Instant Replay was on or off at the time
- what action caused it to fail

## Source code

This repository does not contain the application source code. Public builds are distributed as release assets only.



