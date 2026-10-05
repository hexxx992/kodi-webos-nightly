# Kodi webOS Nightly Changelog

## Kodi 23.0-ALPHA1 — 20261004-d1cecd8a

**Homebrew Version:** `23.26.277`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-05 07:31:22 PDT`

**Commits:** 66

### All Commits

- [`f2dd5a1a`](https://github.com/xbmc/xbmc/commit/f2dd5a1ae4bb4b7edab8f5fae3c04dbc7f2b3350) [RetroPlayer] Batch GUI capture submission before reuse
- [`2e86af64`](https://github.com/xbmc/xbmc/commit/2e86af64949db8a2e021fd62393a1fb461441765) [Video][Database] Clear the hashes of shows that lose episodes.
- [`8ad91ceb`](https://github.com/xbmc/xbmc/commit/8ad91cebe1d09ec8eff239da06bf4323119dda75) [VideoInfoScanner] Use the scanned folder for a show's local art.
- [`0d39166e`](https://github.com/xbmc/xbmc/commit/0d39166e2bea5a03c3c7844b932f423a0242719e) [Video][Database] Remove links to show folders that have gone.
- [`f8889cf7`](https://github.com/xbmc/xbmc/commit/f8889cf7dc5a4f16a780290cd0fb8538daf44e99) [Android] Skip app icons with no intrinsic size
- [`7c3b818b`](https://github.com/xbmc/xbmc/commit/7c3b818b9dcd9574191e287477623931e568cd43) [Video] Name the NFO and art of episodes in an archive after the archive.
- [`2b910fec`](https://github.com/xbmc/xbmc/commit/2b910fec303225ef5c24e7e561047c4418cbf37f) [guilib] FFmpegImage: let av_frame_get_buffer align the temp stride
- [`13a04851`](https://github.com/xbmc/xbmc/commit/13a04851af596f6a81fbc3113c96b19c8e0ff748) fixed: honour the directory parameter of a video library clean
- [`0e1b93e6`](https://github.com/xbmc/xbmc/commit/0e1b93e66f4ed5c43242d0b2efeb6f339ae992b4) [guilib] Fix CGUIImage::SetFileName ignoring useCache
- [`29dba37b`](https://github.com/xbmc/xbmc/commit/29dba37b8b6e1d1bc16459053d48d9aa04c844e7) [WinEventsWin32] Improved handling of display changes.
- [`d9ab26f0`](https://github.com/xbmc/xbmc/commit/d9ab26f056ab5082d155731d9a0f430cf876c8ed) [PlayListPlayer] Don't read the current item of a cleared playlist
- [`4b704add`](https://github.com/xbmc/xbmc/commit/4b704addab6aba013b671c1e17ae71edc596d0c2) [music] Album: initialise year when loading legacy <year> tag
- [`e3f067bd`](https://github.com/xbmc/xbmc/commit/e3f067bd0b8deccc47a7b6252108ec1c6776d6f9) [test] TestVideoPlayer: avoid 2 s renderer wait per test
- [`8202c4ea`](https://github.com/xbmc/xbmc/commit/8202c4eaa782db21906b926db653e145fb1f72f8) added: the content geometry core
- [`3babf317`](https://github.com/xbmc/xbmc/commit/3babf3172b4c69deb2532a9d6d5c1c3a273db269) added: CTerritory, a place a language is used in
- [`a7b9d334`](https://github.com/xbmc/xbmc/commit/a7b9d334599c96db5d88727f81555a29304bf200) changed: open a Blu-ray title without a player
- [`7399f8b4`](https://github.com/xbmc/xbmc/commit/7399f8b47c97d45ef750b0e2ca9b385c4b939e63) [RetroPlayer] Fix FBO renderer synchronization
- [`08364e60`](https://github.com/xbmc/xbmc/commit/08364e607acef5bd0b803b71cc129cc6da187c9e) [RetroPlayer] Clear game window
- [`140cde43`](https://github.com/xbmc/xbmc/commit/140cde43073dddec80da7fc99818301b1a9428cc) [games] Drop an error that can no longer be shown
- [`dd385d97`](https://github.com/xbmc/xbmc/commit/dd385d9703bd49fb02e4e0ecf3e8db421b1dff36) changed: name the view states once
- [`19c05470`](https://github.com/xbmc/xbmc/commit/19c05470122da3d8b8575d0faacad753d48ca8e5) changed: drop two includes Application.cpp does not use
- [`c6246d44`](https://github.com/xbmc/xbmc/commit/c6246d440d76e3d5dfc59b09299c75f2681ee905) fixed: translate a legacy library path by its longest matching prefix
- [`c52a1276`](https://github.com/xbmc/xbmc/commit/c52a12765672045ff63d1ba7cec34d55115dbdfa) changed: the volume component handles the volume actions
- [`0c33dd10`](https://github.com/xbmc/xbmc/commit/0c33dd108d7145ddb3e32618bbf755fdf8307383) changed: the player component handles the playback and video display actions
- [`fce05935`](https://github.com/xbmc/xbmc/commit/fce059356b0f0f6d19b0b2c108c1f8179c23e8df) Dev-kit: Share the check for an instance's API version
- [`4db9eb20`](https://github.com/xbmc/xbmc/commit/4db9eb204b1167576cd3a7934ff298acb68a36af) [games] Pass a game client its libretro core's name
- [`83838f85`](https://github.com/xbmc/xbmc/commit/83838f850b89dedba9eabf6ceccd1d74656df19d) Merge pull request #29494 from kel-mo/guiimage-usecache
- [`940ab0f8`](https://github.com/xbmc/xbmc/commit/940ab0f84df3e64eac4f089a7fa783b34755efc3) Merge pull request #29534 from malard/volume-actions-in-component
- [`d8a8363f`](https://github.com/xbmc/xbmc/commit/d8a8363f255605544281ae721fc615d0e5968d17) Merge pull request #29513 from malard/bluray-open-without-player
- [`9a84a73d`](https://github.com/xbmc/xbmc/commit/9a84a73d48e4eb673451dee926cc3020d6b019c1) Merge pull request #29514 from malard/add-territory
- [`1517ce1e`](https://github.com/xbmc/xbmc/commit/1517ce1e7f992e786bb68a5de7fb0dc91976a210) Merge pull request #29509 from neo1973/fix-testvideoplayer-slow-teardown
- [`14946b61`](https://github.com/xbmc/xbmc/commit/14946b61d8d5dec70e73c2477a3694210c4b7ece) Merge pull request #29502 from sunlollyking/playlist-play-after-clear
- [`d34e66e5`](https://github.com/xbmc/xbmc/commit/d34e66e5c70eed1530fd8a3d26a1873dcbc8125a) Merge pull request #29511 from malard/add-content-geometry-core
- [`0a67f17d`](https://github.com/xbmc/xbmc/commit/0a67f17d5dc30c938edbac6be11abde615508df2) Merge pull request #29506 from neo1973/fix-album-year-uninit
- [`7fa2ccda`](https://github.com/xbmc/xbmc/commit/7fa2ccdaa963bdfb07b76c2d5a8710a95d3b6050) Merge pull request #29530 from malard/drop-unused-application-includes
- [`0f5792ea`](https://github.com/xbmc/xbmc/commit/0f5792ea9a82b667dabed7cd7d79c0280cc8b149) Merge pull request #29456 from M0Rf30/android-appicon-zero-size
- [`4c149d23`](https://github.com/xbmc/xbmc/commit/4c149d23af0076d68bbf28ef35c05c18d8395316) Merge pull request #29483 from malard/fix-cleanlibrary-directory
- [`ee9fb61d`](https://github.com/xbmc/xbmc/commit/ee9fb61da142e4f70ae0749ccfe4646bb3caf7b6) fixed: keep a C standard from CFLAGS out of the depends CPPFLAGS
- [`048c1c42`](https://github.com/xbmc/xbmc/commit/048c1c42ac2952ddf1f3d8e064bb3d860df2de0c) [Video] Export the scraped runtime to nfo rather than the stream duration.
- [`e456f6aa`](https://github.com/xbmc/xbmc/commit/e456f6aacb009b0ad192d8471a808957671df2ec) [Video] Don't export a tv show's cast as the cast of each of its episodes.
- [`f622b89a`](https://github.com/xbmc/xbmc/commit/f622b89abd7b4aa9d143d012f3c6ba1dfa283b0d) [Video] Export the video stream language to nfo.
- [`25bfb445`](https://github.com/xbmc/xbmc/commit/25bfb445facbc5182592c29d10a9a26f65046ac3) [Video] Keep the case of the hdr detail read from nfo.
- [`e6fb2e62`](https://github.com/xbmc/xbmc/commit/e6fb2e6294871c7b3b011884735749fb8cc2f0c1) [Video] Export and import the total time of an episode bookmark.
- [`b74eeea0`](https://github.com/xbmc/xbmc/commit/b74eeea02edd7be643b5776e4bd0d4c7aaab36ed) [Video] Don't escape a plain text episode guide read from nfo.
- [`79ad9462`](https://github.com/xbmc/xbmc/commit/79ad946211b55b8dbb15f4c63f4a5e895f6d2d38) [Video] Keep the streamdetails of a movie converted into a version or extra.
- [`85b57a64`](https://github.com/xbmc/xbmc/commit/85b57a640ec8632cf9e2a05a8d1ed48afc8e0e4e) Merge pull request #29449 from KOPRajs/retroplayer-gl-v3
- [`64520f48`](https://github.com/xbmc/xbmc/commit/64520f488e2454084ea09c2f5c24c66e992fb5db) Merge pull request #29475 from 78andyp/nfoart
- [`e51caaaa`](https://github.com/xbmc/xbmc/commit/e51caaaac328bed84aa79bd3671436cba0dbec06) Merge pull request #29525 from sunlollyking/remove-unreachable-gl-message
- [`337a467c`](https://github.com/xbmc/xbmc/commit/337a467c4ab9b3d5df317ea277be36a7859154f4) Merge pull request #29480 from neo1973/fix-ffmpegimage-stride
- [`c94ca95c`](https://github.com/xbmc/xbmc/commit/c94ca95c20ce273cc76bda6e2ab9cadaa8504b20) Merge pull request #29450 from 78andyp/cleanshows
- [`e46bd9cc`](https://github.com/xbmc/xbmc/commit/e46bd9cc6cafa0073f386a974e0aa43546a4d531) Merge pull request #29539 from sunlollyking/game-libretro-core-name
- [`33cf0eb4`](https://github.com/xbmc/xbmc/commit/33cf0eb4ab39fe5531b6eb0d6f297ae1cb29cb7b) fixed: clear the scraped time of the artist being refreshed (#29533)
- [`ef190cdc`](https://github.com/xbmc/xbmc/commit/ef190cdce25529e35784edb0566643c074f9884f) fixed: trim the genres a music tag keeps when asked to (#29531)
- [`eebf7908`](https://github.com/xbmc/xbmc/commit/eebf79082ba44045bb9cc3b42cfd41c9b0122aa8) changed: name the placeholder entry paths once (#29527)
- [`f3156d1f`](https://github.com/xbmc/xbmc/commit/f3156d1f5373a7a897b3505619e72654313e65ae) fixed: establish the subtitle position from playback start, not the first line (#29150)
- [`c14999cd`](https://github.com/xbmc/xbmc/commit/c14999cd75604bbf314bcb23687de169b910571f) changed: name the library:// node paths once (#29526)
- [`c082c55f`](https://github.com/xbmc/xbmc/commit/c082c55fefed64709c528a83142c9a9f34b39a76) fixed: tell one renderer action's reply from another's (#29219)
- [`3b5010b5`](https://github.com/xbmc/xbmc/commit/3b5010b53818bf5142602c6f7bb1ae72c6494bee) added: the result of sampling one file for content geometry (#29564)
- [`9d554b9e`](https://github.com/xbmc/xbmc/commit/9d554b9ef2d7006889ac23a879469c85b2d974cb) Merge pull request #29479 from 78andyp/exportimport
- [`5d356178`](https://github.com/xbmc/xbmc/commit/5d3561780f5d1cfc285f81366670236e794c6ab3) Merge pull request #29458 from 78andyp/rdp
- [`ca28c949`](https://github.com/xbmc/xbmc/commit/ca28c9492c3993dd4164495951f4ac904a51aba2) added: content bar detection and live geometry selection
- [`590cff67`](https://github.com/xbmc/xbmc/commit/590cff6765b5c5efd7b1bd9c7d037571eaa13f5e) fixed: keep a sample above the declared depth inside the histogram
- [`72f4be96`](https://github.com/xbmc/xbmc/commit/72f4be96e2b5e2b4d82346f7a8e4ed35f1fd0a35) Merge pull request #29532 from malard/fix-legacy-path-longest-prefix
- [`19a54021`](https://github.com/xbmc/xbmc/commit/19a540213ada28502f40697e6036e8c69ed14097) Merge pull request #29535 from malard/player-actions-in-component
- [`5ef5185c`](https://github.com/xbmc/xbmc/commit/5ef5185c365f3a9198128f22212d1e2b8bdaa3b5) Merge pull request #29529 from malard/name-view-states
- [`d1cecd8a`](https://github.com/xbmc/xbmc/commit/d1cecd8ab59d8e6c67bcfd2eaa25312184733339) Merge pull request #29563 from malard/geometry-bar-detector

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/0056082c...d1cecd8a)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261004-d1cecd8a-master_arm.ipk

---
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
