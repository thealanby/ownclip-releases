# OwnClip Releases

Public binary distribution for [OwnClip](https://ownclip.io) — the native macOS screen recorder with AI camera effects.

Source code is private. This repo only hosts release artifacts.

## Latest

- **Download:** [OwnClip-arm64.dmg](https://github.com/thealanby/ownclip-releases/releases/latest/download/OwnClip-arm64.dmg)
- **Auto-update feed (Sparkle):** [appcast.xml](https://github.com/thealanby/ownclip-releases/releases/latest/download/appcast.xml)

## Requirements

macOS 14 (Sonoma) or later, Apple Silicon (M1 or newer).

## Authenticity

All builds are code-signed with a valid Apple Developer ID and notarized by Apple. macOS Gatekeeper will accept the DMG without warnings on first launch. Sparkle auto-update payloads are additionally signed with an EdDSA key pinned in the app, so updates can't be tampered with in transit.
