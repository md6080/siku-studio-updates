# SIKU STUDIO — signed Windows update feed

Public distribution channel for SIKU STUDIO Foundation (Windows x64).

The installed application checks [release.json](release.json) from this repository. Every update must be signed with the publisher's Ed25519 signing key and the downloaded installer must match the declared SHA-256 and file length. This repository contains **distribution packages only**, not private application source code or private signing keys.

Installation is opt-in: **SIKU STUDIO → Check updates → Download update → Install verified update**.

**Important:** The current Foundation application is an experimental test build. The local email field is not a verified online account, and the three 30-second MP4 outputs are not an enforceable cloud license. Windows SmartScreen may warn about unsigned publishers; binary integrity signatures in release.json are not a replacement for Windows Authenticode code signing.

Do not upload any private Ed25519 signing key, customer project, account data, or unpublished source code here.
