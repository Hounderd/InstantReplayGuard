# Instant Replay Guard

Public releases and issue tracking for **Instant Replay Guard**.

Instant Replay Guard is a lightweight Windows tray app that keeps NVIDIA Instant Replay from silently turning itself off, so you stop losing clips after restarts, overlay resets, or NVIDIA hiccups.

## Latest build

- Website: https://guard.nodd.dev
- Direct download: https://download.nodd.dev/InstantReplayGuard-1.1.0-win-x64.zip
- VirusTotal: https://www.virustotal.com/gui/file/a67ac1d6c3b7ae26c935fb8457baf1096a6258027a3a531bb2b4ded44da88aaa?nocache=1

## What it does

- monitors Instant Replay in the background
- re-enables it if NVIDIA drops it
- runs locally on your machine
- stays out of the game process entirely
- sits in the tray and uses negligible CPU when idle

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
