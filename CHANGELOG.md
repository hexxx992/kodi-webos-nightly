# Kodi webOS Nightly Changelog

## 23.0-ALPHA1 Nightly — 20261002-0056082c

Homebrew version: `23.26.275`

Changes from `f889ea2d` to `0056082c`:

• RetroPlayer: Ask about a savestate's game client before opening the game (2dfad7d9)
• RetroPlayer: Keep a DMA buffer mapped until its last reader is done (e05562de)
• [JSON-RPC] Change version to 14.0.0 for v23 development (20ae57cf)
• fixed: reject an aspect ratio whose key would not fit an int (963d9256)
• RetroPlayer: Close the leaderboards when a game has none (e563e07c)
• changed: find a running video scan by the scanning job's own type (ab688011)
• fixed: reject an aspect ratio that has no key of its own (1a74787f)
• RetroPlayer: Close the leaderboards without a flash (b2ff98e5)
• RetroPlayer: Report a closed game as stopped, not ended (8613ae4e)
• [guilib] Keep a game in the game window when it opens there (52245df1)
• changed: move LangInfo to xbmc/language (9ce9ddc1)
• changed: open and decode a file's video through one reusable session (3196cab5)
• + 39 additional commits

Official source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261002-0056082c-master_arm.ipk

Full comparison: https://github.com/xbmc/xbmc/compare/f889ea2d...0056082c

---
