# Kodi webOS Nightly Changelog

## Kodi 23.0-ALPHA1 — 20261002-0056082c

**Homebrew Version:** `23.26.275`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-04 02:59:41 PDT`

**Commits:** 51

### All Commits

- [`c070f068`](https://github.com/xbmc/xbmc/commit/c070f068a472df7c5320833a761b4e4bd73b266f) [Android] Add option to use the native on-screen keyboard
- [`65783e65`](https://github.com/xbmc/xbmc/commit/65783e65656e19598d87cbeaf567ad20ed964c7c) Android: Relinquish Splash focus before launching Main
- [`5419f176`](https://github.com/xbmc/xbmc/commit/5419f1767cde723bc840705d6cba4f83ee0ff99f) [Docs] Add revisions for v23
- [`fc9b1a94`](https://github.com/xbmc/xbmc/commit/fc9b1a9480463c98a1ab39f4c702612972f0d675) tests: Give each test process its own masterprofile
- [`046b68bb`](https://github.com/xbmc/xbmc/commit/046b68bb0c0006808931af50c307ba4376498912) Fix dependency library path for MSVC
- [`eae0ae12`](https://github.com/xbmc/xbmc/commit/eae0ae12f1b4396f3b64207301e8e8c956b200ce) Suppress C4146 and C4996 for Windows Store dependencies
- [`b38684f5`](https://github.com/xbmc/xbmc/commit/b38684f539229c1617f0d162d542c9828ea633c4) [guilib] Keep a panel's selected item when its row length changes
- [`2a958573`](https://github.com/xbmc/xbmc/commit/2a9585730c22d79dd071b82ee11ad177c4023b99) RetroPlayer: Refuse to open a game while another is opening
- [`e8001117`](https://github.com/xbmc/xbmc/commit/e8001117fc7f828302f2a744a64d31d984893478) fixed: job manager stalls when a callback blocks
- [`4d62f19a`](https://github.com/xbmc/xbmc/commit/4d62f19a41cde712133d77ecc5e8df4a8b178a2d) changed: the scanning job names its own type
- [`0a04fe75`](https://github.com/xbmc/xbmc/commit/0a04fe7579225f4a0e8dfa4c0f09f54d7cb3ba81) fixed: a music database upgrade queried songview after dropping it
- [`97949c2c`](https://github.com/xbmc/xbmc/commit/97949c2c7fc4e023454f7a54774ec99f8f3def34) fixed: report a music database commit that succeeded without a GUI
- [`9ae2249c`](https://github.com/xbmc/xbmc/commit/9ae2249c540eb42262613afe930b03c2a8a88d0b) fixed: a downloaded subtitle in no known language is saved without an empty suffix
- [`23cf5689`](https://github.com/xbmc/xbmc/commit/23cf5689b12ef55f3863e3b31dc461b2f1aecd66) added: a vocabulary of the aspect ratios Kodi recognises
- [`3f13fc3b`](https://github.com/xbmc/xbmc/commit/3f13fc3b7d66cfb9efa0d36f6986a6f6bc74641f) added: frame reduction and sampling for content geometry
- [`151559a9`](https://github.com/xbmc/xbmc/commit/151559a9f0c84d94a90f36a7ffc4de44601b5abf) fixed: a movie, episode or music video is found by its director's name
- [`8efb963f`](https://github.com/xbmc/xbmc/commit/8efb963fb6ab6d6b6d27af77f93b52eeb021c974) changed: treat an empty playlists path as no playlists folder
- [`3196cab5`](https://github.com/xbmc/xbmc/commit/3196cab53972033d04d7ea3c15897374fa95d5a7) changed: open and decode a file's video through one reusable session
- [`94732fbf`](https://github.com/xbmc/xbmc/commit/94732fbf10b3b49bbb0925635af077a714a7f463) Merge pull request #29468 from sunlollyking/docs-v23-revisions
- [`31338108`](https://github.com/xbmc/xbmc/commit/31338108558afc9feb0b400094d957f1e571ff46) Merge pull request #28580 from DevFalko/feature/android-native-keyboard
- [`9ce9ddc1`](https://github.com/xbmc/xbmc/commit/9ce9ddc11b514bf2cad2033439c6d9f8aa6564e1) changed: move LangInfo to xbmc/language
- [`2bb03cb0`](https://github.com/xbmc/xbmc/commit/2bb03cb057bef45c894df3468cf7d2aefb2fb24f) Merge pull request #29481 from malard/move-langinfo-to-language
- [`52245df1`](https://github.com/xbmc/xbmc/commit/52245df1c714d5cb054363138ab60c6037f49ae8) [guilib] Keep a game in the game window when it opens there
- [`8613ae4e`](https://github.com/xbmc/xbmc/commit/8613ae4e4ade1324345a62a52b813c18554de24b) RetroPlayer: Report a closed game as stopped, not ended
- [`b2ff98e5`](https://github.com/xbmc/xbmc/commit/b2ff98e5c85bcb9c2650d38e3963e3dfec6b8a69) RetroPlayer: Close the leaderboards without a flash
- [`1a74787f`](https://github.com/xbmc/xbmc/commit/1a74787fb0e7e500c82d985cd83bb758da19c448) fixed: reject an aspect ratio that has no key of its own
- [`ab688011`](https://github.com/xbmc/xbmc/commit/ab688011b372aff0bc9b45e446b0f858b676af32) changed: find a running video scan by the scanning job's own type
- [`e563e07c`](https://github.com/xbmc/xbmc/commit/e563e07c02913f68636c5725d5d11f8ff34ffd5d) RetroPlayer: Close the leaderboards when a game has none
- [`b67e00ff`](https://github.com/xbmc/xbmc/commit/b67e00ff526f441f7b9e961d8fc1f7691dee460e) Merge pull request #29486 from malard/fix-subtitle-empty-language-suffix
- [`91f909c1`](https://github.com/xbmc/xbmc/commit/91f909c1ade282bb47d41f26b169260274cc7aff) Merge pull request #29487 from malard/add-frame-reduction-and-sampling
- [`963d9256`](https://github.com/xbmc/xbmc/commit/963d92564c432260bfcf45bea7e78a54309b49cc) fixed: reject an aspect ratio whose key would not fit an int
- [`e8d78f99`](https://github.com/xbmc/xbmc/commit/e8d78f99a17324bc5c154b3dd99438363bd0bcf2) Merge pull request #29485 from malard/fix-music-upgrade-songview
- [`20ae57cf`](https://github.com/xbmc/xbmc/commit/20ae57cf2e8cf95274a75512102c9d7a5db06fb5) [JSON-RPC] Change version to 14.0.0 for v23 development
- [`c5211db4`](https://github.com/xbmc/xbmc/commit/c5211db48d0ec782cee82f190695c38acaf7cd82) Merge pull request #29507 from malard/jsonrpc-version-14.0.0
- [`91569911`](https://github.com/xbmc/xbmc/commit/91569911bed49b70a2157389e30bac4385e2b8b2) Merge pull request #29474 from garbear/msvc-libpath
- [`e99bb6a9`](https://github.com/xbmc/xbmc/commit/e99bb6a9192c26a8575fb2d16a7247bf49f8fb04) Merge pull request #29469 from popcornmix/isolate-masterprofile-in-tests
- [`e05562de`](https://github.com/xbmc/xbmc/commit/e05562debb790e479077e3756ec5ca661d20f689) RetroPlayer: Keep a DMA buffer mapped until its last reader is done
- [`2dfad7d9`](https://github.com/xbmc/xbmc/commit/2dfad7d95f9afea7171a85c9e8e6bd6efdef13b0) RetroPlayer: Ask about a savestate's game client before opening the game
- [`b6d1f0a4`](https://github.com/xbmc/xbmc/commit/b6d1f0a4018a54d4b9ea4989735235b6abe5c0ca) Merge pull request #29489 from malard/fix-video-director-filter
- [`0b613b92`](https://github.com/xbmc/xbmc/commit/0b613b92c7028b43e7ec0436f884946a90b0f32e) Merge pull request #29490 from malard/empty-playlists-path-is-no-folder
- [`6afcb3db`](https://github.com/xbmc/xbmc/commit/6afcb3dbdaf0f7bf20135c0aa9e309f4993fcb13) Merge pull request #29491 from malard/extract-video-decode-session
- [`bba3bc71`](https://github.com/xbmc/xbmc/commit/bba3bc71d4ee0dc142b3c64f6f9c74610e820fa1) Merge pull request #29488 from malard/scanning-job-names-its-type
- [`4ae481df`](https://github.com/xbmc/xbmc/commit/4ae481df2ea1fcde97d647843cf5542840aa3cda) Merge pull request #29482 from malard/fix-music-commit-without-gui
- [`5a07c067`](https://github.com/xbmc/xbmc/commit/5a07c0676a9a1b2fe2fa717ef37d7c28b229941f) Merge pull request #29484 from malard/add-aspect-ratio-vocabulary
- [`15789003`](https://github.com/xbmc/xbmc/commit/157890037cc8b34de526b289fbb78905a5647ebd) Merge pull request #28944 from malard/fix-28894-jobmanager-worker-accounting
- [`c1045311`](https://github.com/xbmc/xbmc/commit/c1045311ce94ec71663b2f377df7110e9de0702e) Merge pull request #29477 from sunlollyking/retroplayer-open-reentry
- [`308762f3`](https://github.com/xbmc/xbmc/commit/308762f37fcbb7b2283836285ff9c91f07bd96c7) Merge pull request #29500 from sunlollyking/retroplayer-dma-map-refcount
- [`1442a51b`](https://github.com/xbmc/xbmc/commit/1442a51b81deaf86ccdfccb7f7245c75e567062b) Merge pull request #29503 from sunlollyking/retroplayer-report-stop
- [`4fb5f56d`](https://github.com/xbmc/xbmc/commit/4fb5f56d5c299c5fde32f7d70b0cc0230f5545e4) Merge pull request #29476 from sunlollyking/panel-keep-selection
- [`beb53ac8`](https://github.com/xbmc/xbmc/commit/beb53ac84b09702e9f3fea4b9ff2e2b430fbc5fe) Merge pull request #29443 from garbear/android-splash
- [`0056082c`](https://github.com/xbmc/xbmc/commit/0056082cce2ce72b67e593beffdc0daa8950eca4) Merge pull request #29505 from sunlollyking/leaderboards-close-without-flash

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/f889ea2dd127a4910216c0c2b6e249435e06b9fa...0056082cce2ce72b67e593beffdc0daa8950eca4)
