# Secret Solver v4.2 - Stability Update

> ⚠️ **Canary Release** — This version is available to canary testers only. App access is restricted to the canary channel.

## Latest Updates (v4.2 - Stability Update)
- **BLE Typing Fix**:
  - Resolved an issue where typing text to the calculator would fail after the first character.
  - Multi-character input now works reliably over BLE.
  - Improved key send/acknowledge handshake timing for consistent input delivery.
- **Reply Loading Fix**:
  - Fixed a bug where replies would get stuck in an infinite loading state.
  - Messages and replies now load consistently without requiring a restart.