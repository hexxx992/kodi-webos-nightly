# Kodi webOS Nightly Changelog

## Kodi 23.0-ALPHA1 — 20261023-a097d697

**Homebrew Version:** `23.26.296`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-23 09:12:03 PDT`

**Commits:** 81

### All Commits

- [`8200621b`](https://github.com/xbmc/xbmc/commit/8200621b3ad1003749c6066a8f0d8abd127dc80b) [Video][Music] Leave the All entries out of the library windows' item count
- [`532cf915`](https://github.com/xbmc/xbmc/commit/532cf915ebeecccc5f12c1084bbae3576d8b3a13) [cleanup] Look each service up once per function
- [`df2de23d`](https://github.com/xbmc/xbmc/commit/df2de23d54dc2899ebe15aefdbbe0c388db9c094) [cleanup][PVR] Use the PVR manager GetProvidersDirectory already holds
- [`8374ee8b`](https://github.com/xbmc/xbmc/commit/8374ee8b6a25229a35ddeb76a561caf1f2584d72) [PVR][JSON-RPC] Hand out PVR image paths as URLs the web server can serve
- [`d4835b37`](https://github.com/xbmc/xbmc/commit/d4835b3728d4128aa779cb69859610bc9b76b9c5) [Windows][RendererSoftware] Draw RGB sources in their own colours
- [`67760a13`](https://github.com/xbmc/xbmc/commit/67760a136f0f9c1d249fc75072f7f0e6f6b5f14a) [VideoPlayer] RGB with no range given is full range
- [`d8335091`](https://github.com/xbmc/xbmc/commit/d833509187727ec3125b7e707f281c521c1d14a7) [VideoPlayer][CDVDDemuxClient] Keep parsed stream properties when a stream is opened again
- [`b7b3db85`](https://github.com/xbmc/xbmc/commit/b7b3db8593c840205a74d57cc66ab9eeb516da8d) [VideoPlayer][CDVDDemuxClient] Take a changed aspect, and the profile of a stream that changed codec
- [`a856eaab`](https://github.com/xbmc/xbmc/commit/a856eaab57552d334301dcca47ab3540ee3b3a2a) [dialogs] Nest the image choice entries inside KODI::ART
- [`2a951304`](https://github.com/xbmc/xbmc/commit/2a95130444ab0988457efc945b740f9fc9c20626) [cleanup] Look a service up in the GUI info case that uses it, and the messenger at each send
- [`0db84fe4`](https://github.com/xbmc/xbmc/commit/0db84fe4703118742b3c5994132da887866052b0) [RetroPlayer] Only strip shader parameter pragmas that start a line
- [`3b8a340c`](https://github.com/xbmc/xbmc/commit/3b8a340c02f9a40b361211e6c072025febdc30eb) [Video] Use cached local art in file listings and revalidate it
- [`04038b7c`](https://github.com/xbmc/xbmc/commit/04038b7c704120b2affdce20db96d59fd6e45779) [cmake] Make cache publication non-fatal
- [`688fbc0c`](https://github.com/xbmc/xbmc/commit/688fbc0cb246c4e0355f20cb8c172d54cccddbb9) [TextureCache] Return the cached copy at the requested size on a miss
- [`9c442a82`](https://github.com/xbmc/xbmc/commit/9c442a8235a8f89e4d2cc7604d21698e10142908) RetroPlayer: Fix hang when a client asks for its framebuffer off-thread
- [`487a8fee`](https://github.com/xbmc/xbmc/commit/487a8fee0975d0ebc944ccd47689ece243e90eb3) cmake: build FFmpeg with libopus for wasm
- [`d157b14f`](https://github.com/xbmc/xbmc/commit/d157b14f13e824dedae4bb8e0fe1b85d00f1d787) [video] Keep an unset play count when archiving a video info tag
- [`6cb8fd86`](https://github.com/xbmc/xbmc/commit/6cb8fd86fb9b53517ad6f2d589aa56f7a9d18e84) cmake: make Opus optional across platforms and bump to 1.6.1
- [`880957c9`](https://github.com/xbmc/xbmc/commit/880957c918c720a9e4fd934ce647d93a5ca32981) [RetroPlayer] Don't leave a shader's GLSL profile in its source
- [`6dfbe602`](https://github.com/xbmc/xbmc/commit/6dfbe60209e8ac0300a941eae3f2be3123d29f73) Games: Fix the player's standing on RetroAchievements leaderboards
- [`b5bad5a3`](https://github.com/xbmc/xbmc/commit/b5bad5a329203b5551831daa367d6ebe3c417097) [AudioEngine] ActiveAE: Leave audio starting late to the player's clock
- [`701d1033`](https://github.com/xbmc/xbmc/commit/701d10330f0efa5db5e8c1f1fe95304780e66cb5) VideoPlayer: add CProcessInfoWasm
- [`f8e8eef1`](https://github.com/xbmc/xbmc/commit/f8e8eef1910710616d56c8a270de6f9a378a1eb4) VideoPlayer: add WebCodecs bitstream helpers
- [`8810a63e`](https://github.com/xbmc/xbmc/commit/8810a63e736e069c33d7ae9c6b9ee8d41de0db35) VideoPlayer: add a WebCodecs video decoder
- [`ba5c4e3d`](https://github.com/xbmc/xbmc/commit/ba5c4e3d11dc7256b034fe0fdb27169d09ed4af6) VideoPlayer: render WebCodecs frames as WebGL textures
- [`9f17a616`](https://github.com/xbmc/xbmc/commit/9f17a616b00043903178bfb2d05a50ac37d1401c) cmake: track Opus configuration in Windows FFmpeg rebuilds
- [`b0b7a659`](https://github.com/xbmc/xbmc/commit/b0b7a6590aae01905c8e57be3aadd00231ff2ce4) cmake: search the dependency prefix for FFmpeg packages
- [`98d14a0c`](https://github.com/xbmc/xbmc/commit/98d14a0cdcd9d765a34aa09ab51b6d7c2b189946) [cert] Update CA bundle to 2026-10-20
- [`608a522f`](https://github.com/xbmc/xbmc/commit/608a522fb385746b8c43e80836d2d9004ece6ce9) Revert "[depends] mariadb: declare static zstd plugin in libmariadb.pc"
- [`c657b904`](https://github.com/xbmc/xbmc/commit/c657b904c268eee82fe26a732edb5ba5c2ae94e2) [cmake] FindMariaDBClient: link zstd after a reused static libmariadb
- [`9d8f4200`](https://github.com/xbmc/xbmc/commit/9d8f420049f39df96647580a6e6b727386947245) Merge pull request #29800 from clementperon/upstream/09-webcodecs
- [`b1dfafb1`](https://github.com/xbmc/xbmc/commit/b1dfafb1f7a5e49a46bcefaf9729562c7b0d5edd) Merge pull request #29917 from olympia/video-thumbloader-cached-art
- [`3cba8efb`](https://github.com/xbmc/xbmc/commit/3cba8efb39c13213cdd1abc275a35a9dca797902) [media] Fix the build with libfmt 10
- [`cf3582c7`](https://github.com/xbmc/xbmc/commit/cf3582c7bfcc6ee6c4b219ecc24daee6e07a40d3) [FileItemList] Leave the sort order of an added sort method to the view
- [`453dfcd8`](https://github.com/xbmc/xbmc/commit/453dfcd8597931867408a22ed870405f0bac7cca) [VideoPlayer] Reopen a hidden subtitle stream when showing it again
- [`5c87d5e9`](https://github.com/xbmc/xbmc/commit/5c87d5e9f890906bd9ace8d7ea66c57eb3168b2c) Merge pull request #29834 from sunlollyking/media-type-format-as
- [`c93aa95d`](https://github.com/xbmc/xbmc/commit/c93aa95dc835a095d45f005d1820504c934e4da5) Merge pull request #30004 from 78andyp/webosfix
- [`93132b7f`](https://github.com/xbmc/xbmc/commit/93132b7f2195ad0a999b4e1ddc08ec18028c088e) [VideoDatabase] Import a movie set's art of every type the artwork level allows.
- [`3abf251f`](https://github.com/xbmc/xbmc/commit/3abf251fbfb3a30c9c707e74fe3e63174b871c2e) [TextureCache] Cache an image again where its row has outlived its file.
- [`cbfae508`](https://github.com/xbmc/xbmc/commit/cbfae5088fdaccabc533d642fcf9f7aeb48ee0b0) [TextureCache] Name an exported image by the type it is cached again as.
- [`8cd19e23`](https://github.com/xbmc/xbmc/commit/8cd19e23be8e48daf99d9468b1e19a1319bac3e7) [TextureCache] Export art that hasn't been cached yet.
- [`cafd4a6c`](https://github.com/xbmc/xbmc/commit/cafd4a6cf7931147a56a21b10bb140ed3efff865) [TextureCache] Add TextureCache tests for exporting and recaching art.
- [`d642d1d6`](https://github.com/xbmc/xbmc/commit/d642d1d654661639773102ec2cb44ec8df2b7964) [VideoThumbLoader] Don't make a thumb of a stack of disc playlists.
- [`e23f255c`](https://github.com/xbmc/xbmc/commit/e23f255c45c4acab0e215833da9aee35b54a95c6) [VideoDatabase] Cache art on export that a scan caches.
- [`dccc1e67`](https://github.com/xbmc/xbmc/commit/dccc1e6773b0c9387e48bb675b5adf0d7817e1af) Merge pull request #29976 from clementperon/upstream/13-libopus
- [`485b4e27`](https://github.com/xbmc/xbmc/commit/485b4e27cc860100d746dc31b3e75e9872c0ce76) Merge pull request #29973 from sunlollyking/retroplayer-client-thread-framebuffer
- [`db19b77f`](https://github.com/xbmc/xbmc/commit/db19b77f0a815dea61a3f3d2a56618d5d6e23571) Merge pull request #29905 from sunlollyking/retroplayer-shader-parameter-lines
- [`8e4cef14`](https://github.com/xbmc/xbmc/commit/8e4cef1436bf73042e0c6d67a1671589369f4b38) [guilib] Free list item artwork when a container's window is deinited
- [`87d0f972`](https://github.com/xbmc/xbmc/commit/87d0f9721626ca63e64fe30c4113489ffb8bdd7a) windowing/gbm: apply videoscreen.limitguisize without a restart
- [`8d805c2d`](https://github.com/xbmc/xbmc/commit/8d805c2de597e6cc190bdce3ceae2f419b3d677b) threads: free the std::thread object when a thread is stopped
- [`620fbbff`](https://github.com/xbmc/xbmc/commit/620fbbff9fa8c74b0aa81751f24644ba859f3f6b) Merge pull request #29978 from ksooo/videoinfotag-archive-playcount
- [`998331ed`](https://github.com/xbmc/xbmc/commit/998331ed5b7df91998db95789f81e2e2ac6650dd) Merge pull request #30007 from ksooo/videoplayer-reopen-hidden-subtitle
- [`142ba687`](https://github.com/xbmc/xbmc/commit/142ba68716c8ceb2e3c121ec3ca28f43d0f6f67e) Merge pull request #29991 from ksooo/activeae-late-start-clock
- [`06294e41`](https://github.com/xbmc/xbmc/commit/06294e41e9c0dc9dea70d2503f45ba25b154bee0) Merge pull request #30009 from ksooo/fileitemlist-sort-order
- [`d41eb00c`](https://github.com/xbmc/xbmc/commit/d41eb00c9116deb7b0e95a5cfa6c8bd3965cd0f1) Merge pull request #30000 from shaan-forks/fix-emudhra-ca-compromise
- [`a9ffc7ab`](https://github.com/xbmc/xbmc/commit/a9ffc7ab3e025471b2c1422d16d1f887f9ebd7a2) Merge pull request #29970 from olympia/texturecache-miss-load-cached
- [`88a43c0f`](https://github.com/xbmc/xbmc/commit/88a43c0fa3162ddcf239f570c3f64f1ff6609e1b) guilib: scale an image from the frame's own dimensions
- [`3aa6033f`](https://github.com/xbmc/xbmc/commit/3aa6033f99637ec74e22991533515043932728a0) guilib: tell the image decoder the size the caller will use
- [`3168a2f2`](https://github.com/xbmc/xbmc/commit/3168a2f24e46ef9e7332f4832b0ea462667d8d3b) TextureCacheJob: load an image only as large as the cache will keep
- [`434da3cd`](https://github.com/xbmc/xbmc/commit/434da3cdb7974dbc40d6796fd5f96c10f12a0c6e) Merge pull request #29895 from sunlollyking/retroplayer-shader-version-profile
- [`e18cac9a`](https://github.com/xbmc/xbmc/commit/e18cac9a61cc78ed6d57f8c594fc736769b0ff5a) [depends] Include GBM in Linux system GL libraries
- [`4705fd3e`](https://github.com/xbmc/xbmc/commit/4705fd3e35ec385c696f748036b67483c0951125) guilib: decode oversized JPEGs at a reduced size
- [`b505d452`](https://github.com/xbmc/xbmc/commit/b505d45266a2e5ec71c2b80b2ad17f11db637d59) [RetroPlayer] Leave the client's scissor test as it was after capture
- [`654662df`](https://github.com/xbmc/xbmc/commit/654662dfe9d5deea53e539a9cae9e6ab2f795025) Merge pull request #29765 from malard/fix-jsonrpc-pvr-image-urls
- [`212539a4`](https://github.com/xbmc/xbmc/commit/212539a46b1236ef2a452b672fe3b169cbfe7bc3) Merge pull request #29790 from malard/fix-demuxclient-keep-parsed-stream-props
- [`964b40db`](https://github.com/xbmc/xbmc/commit/964b40db6c1f757db211fb3bc1589ee03106f68f) Merge pull request #29779 from malard/software-renderer-rgb
- [`ab97a0d1`](https://github.com/xbmc/xbmc/commit/ab97a0d12eea6b875ba9665e9a93856bd7d0961b) Merge pull request #29762 from malard/nest-image-choice-namespace
- [`17b29f78`](https://github.com/xbmc/xbmc/commit/17b29f78b1db874611d0b5df672d9bb884649cf2) Merge pull request #29728 from malard/look-up-services-once
- [`4ef416ff`](https://github.com/xbmc/xbmc/commit/4ef416ffa6c0f7b206f21d1d52c2b7e975a7eba3) Merge pull request #29694 from malard/fix-videonav-all-entry-count
- [`f6253f17`](https://github.com/xbmc/xbmc/commit/f6253f17315edb835b10b71d83c1025dacdb5fd3) Merge pull request #29955 from garbear/cache-rename-fix
- [`8ba86889`](https://github.com/xbmc/xbmc/commit/8ba868899755e0644a8b7b36678d32e2f4393db3) [guilib] Keep processing multiimages with smart redraw
- [`677c28e0`](https://github.com/xbmc/xbmc/commit/677c28e0dbcb1a4af1651632347ec62bd5bb8394) Merge pull request #29992 from popcornmix/texturecache-decode-ceiling
- [`05ed311c`](https://github.com/xbmc/xbmc/commit/05ed311c764ff1fe81c5678d7b82a2dbb76da17d) Merge pull request #29995 from popcornmix/texturecache-jpeg-lowres
- [`30069420`](https://github.com/xbmc/xbmc/commit/300694203c8a30dac93ec1642482d9a0536aa672) Merge pull request #29996 from popcornmix/listprovider-free-art
- [`5bffa62e`](https://github.com/xbmc/xbmc/commit/5bffa62ea98ba055ff718cb427e6243b044f4d16) Merge pull request #29985 from sunlollyking/retroplayer-scissor-restore
- [`3b19c96b`](https://github.com/xbmc/xbmc/commit/3b19c96b464851b0e851fb4d53d77c6e61350318) Merge pull request #29723 from 78andyp/artfixes
- [`d2eef63e`](https://github.com/xbmc/xbmc/commit/d2eef63eaced1ae701a412f054fc70e76cab09cb) Merge pull request #30023 from garbear/fix-missing-gbm
- [`e1ca53d5`](https://github.com/xbmc/xbmc/commit/e1ca53d5861dbb3afcb58d652fc7af74e0bf2805) Merge pull request #29795 from popcornmix/threadleak
- [`4c377a8d`](https://github.com/xbmc/xbmc/commit/4c377a8db0d5eb8d6014dbe49a4254288c0b4be3) Merge pull request #29799 from popcornmix/guilimitlive
- [`3c155bc4`](https://github.com/xbmc/xbmc/commit/3c155bc4273877ab980c67948bd4604e24e38189) Merge pull request #29982 from sunlollyking/leaderboard-standings
- [`a097d697`](https://github.com/xbmc/xbmc/commit/a097d6978028aef8840b23695a57c606697f156a) Merge pull request #29965 from neo1973/fix-smartredraw-multiimage

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/47ee87ca...a097d697)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261023-a097d697-master_arm.ipk

---
## Kodi 23.0-ALPHA1 — 20261021-47ee87ca

**Homebrew Version:** `23.26.294`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-21 09:22:38 PDT`

**Commits:** 78

### All Commits

- [`250af933`](https://github.com/xbmc/xbmc/commit/250af933e19e6eaa6da36e07a4f2cba3e4a4bf70) [games][CGUIWindowGames] Remove a commented-out game info dialog and two bare todos
- [`85b13776`](https://github.com/xbmc/xbmc/commit/85b13776ee84b8e35efb6811bb20e553875e274b) [cmake] Isolate dependency downloads from shared cache writers
- [`6b2a6c68`](https://github.com/xbmc/xbmc/commit/6b2a6c68835e7ac43864bccc1acf4a0d0094908d) uwp: add libdovi dependency
- [`adc081f8`](https://github.com/xbmc/xbmc/commit/adc081f86f6c29bf09e5e8c1eeb30d700bc948ee) [test] Characterize Kodi URL and path semantics
- [`64e3ea88`](https://github.com/xbmc/xbmc/commit/64e3ea88d477f57b2c7016b4f1efa245e833c3f6) [utils] Add lossless URI reference parsing
- [`a01228ec`](https://github.com/xbmc/xbmc/commit/a01228ecd28eadc4a6d389e1c2b29854973b863f) [CMake] Don't disable optimizations for Mime.cpp on Clang
- [`fca12dca`](https://github.com/xbmc/xbmc/commit/fca12dca06ec305cc28cbafec90badf6fb8b6680) [RetroPlayer] Only read a savestate when a game is resumed from one
- [`ee93b2b3`](https://github.com/xbmc/xbmc/commit/ee93b2b3688d989c3a5aff6d8e17f2412cc48b53) [cmake] Support SOURCE_SUBDIR for dependency builds
- [`11458b74`](https://github.com/xbmc/xbmc/commit/11458b74ddc975229e805c86194d10906b4e1aa3) [tools/depends][target] Add Zstandard dependency
- [`e105eeb4`](https://github.com/xbmc/xbmc/commit/e105eeb4b4214b629a6fbd7a3f321f4b1eeadf8a) [cmake] Introduce Zstandard dependency discovery
- [`a6bcd5a2`](https://github.com/xbmc/xbmc/commit/a6bcd5a2bbe8a3dd7172446dad5a8824c6e749fe) [cmake] Enable Zstandard support in curl
- [`8d3d054e`](https://github.com/xbmc/xbmc/commit/8d3d054edaa449d6f0c5d65b57627db2b4e55274) [cmake] Build MariaDB with static Zstandard support
- [`6d9181e4`](https://github.com/xbmc/xbmc/commit/6d9181e4cba470730665a61223cf998a52b747f4) [games] Add more details to a game's info tag
- [`575bbd95`](https://github.com/xbmc/xbmc/commit/575bbd956e5f3e08b95c626f9e442fc832b0590a) [filesystem] CFile::LoadFile: return -1 when the file cannot be read
- [`72fda1d0`](https://github.com/xbmc/xbmc/commit/72fda1d0a5046e9e1fb501e9196783e723091e29) [filesystem] HTTPDirectory: read through CFile instead of CCurlFile
- [`e82f29c1`](https://github.com/xbmc/xbmc/commit/e82f29c1f6eb53a1936e37d135cf41e8ec65a8c0) [addons] Repository: read through CFile instead of CCurlFile
- [`cc647782`](https://github.com/xbmc/xbmc/commit/cc647782d9f58145b3f83dbf4499e3bdc8ac93d8) [CDateTime] Get the time zone bias for dates before 1970 on POSIX
- [`417dc3a1`](https://github.com/xbmc/xbmc/commit/417dc3a176baa20dcd80f41ba88c32ebe0b4f95a) [CMake] Add precompiled header support for non-Windows platforms
- [`a25aa714`](https://github.com/xbmc/xbmc/commit/a25aa714d57345df40f1ca51bc224eecaeb0c490) [CMake] Keep ccache effective with precompiled headers
- [`ca502c9e`](https://github.com/xbmc/xbmc/commit/ca502c9ef4bf6bf0cbe02aec6a02b84ff34c9c8c) [guilib] Keep processing windows while interim images are shown
- [`28d01a46`](https://github.com/xbmc/xbmc/commit/28d01a462069d601c1f95e09be6ee982bdd098dd) [VideoPlayer] DVDFactoryInputStream: resolve redirects through CFile
- [`26def6e5`](https://github.com/xbmc/xbmc/commit/26def6e58bc4839a466f5348ddff504ec20e2ea1) wasm/tizen: BSD sockets over the Tizen Sockets Extension
- [`a9056143`](https://github.com/xbmc/xbmc/commit/a90561435976343b1bae5756031bf6345d9b8ff8) wasm/filesystem: serve http(s) through XMLHttpRequest without sockets
- [`68459f1b`](https://github.com/xbmc/xbmc/commit/68459f1bc9e979cfdde0c6f1a6febb08b2ad8ea8) [GUILIB] CGUIImage: report the incoming image right away
- [`efab72aa`](https://github.com/xbmc/xbmc/commit/efab72aa70be286873daf3f90a62a3edf8be67a6) Merge pull request #29883 from sunlollyking/retroplayer-skip-empty-savestate
- [`70256bc9`](https://github.com/xbmc/xbmc/commit/70256bc9ac72cc3e6fe08cdcf4fb450ebcfdcbe4) [RetroPlayer] Remove the unreachable savestate game client warning
- [`7915e245`](https://github.com/xbmc/xbmc/commit/7915e245f54b1426db5a529235026c987c40468b) Merge pull request #29890 from sunlollyking/game-info-tag-details
- [`8f6c50bd`](https://github.com/xbmc/xbmc/commit/8f6c50bd005f5b96426db93f8861cb063b2ebb21) Merge pull request #29843 from garbear/concurrent-downloads
- [`a2f8f396`](https://github.com/xbmc/xbmc/commit/a2f8f396fa08a9e5b51c0d81a81c84b09d935674) [RetroPlayer] Leave scissor testing disabled after capture
- [`2dc6f964`](https://github.com/xbmc/xbmc/commit/2dc6f964bdc57b6fcfa22ad63956d721b065634e) xbox: add dolby vision low latency and transform plugin
- [`56f0e005`](https://github.com/xbmc/xbmc/commit/56f0e005fb457e3d37e5752acaf94126673a0a14) [MediaManager] Keep the optical drive off the GUI and application threads.
- [`b1d28895`](https://github.com/xbmc/xbmc/commit/b1d28895db6f590552b56d8ce95089291fe7f5d7) [MediaManager] Don't let a finished job describe a disc that was ejected.
- [`839cf04b`](https://github.com/xbmc/xbmc/commit/839cf04b471b0333c9c01ea46391d61680b82418) [MediaManager] Work the tray from a job, not the application thread.
- [`5ea85c61`](https://github.com/xbmc/xbmc/commit/5ea85c611cdfbb248b4bab2434e8c8d4f534f4cf) [Disc] Report whether a tray operation moved the drive.
- [`ea3ed638`](https://github.com/xbmc/xbmc/commit/ea3ed63884c991774bc7a0151b12dabbc31c6679) [MediaManager] Leave autorun to the disc detection thread except on Windows.
- [`a0f6e219`](https://github.com/xbmc/xbmc/commit/a0f6e219e758d62e2c11a94275da92f1ce455d6b) [MediaManager] Leave reading the disc to a job when the GUI polls.
- [`0d5945a5`](https://github.com/xbmc/xbmc/commit/0d5945a589b74590fc780f472ce9f21595df5ab7) [MediaManager] Forget the Blu-ray playlist status when a disc arrives.
- [`46d4cf21`](https://github.com/xbmc/xbmc/commit/46d4cf2171a7ef85ba22d8b501ba2025d7154550) [macOS/tvOS] build in Release config
- [`5260e44c`](https://github.com/xbmc/xbmc/commit/5260e44c169ada5eeda3d9fef0492b2cd7baa714) [iOS] build RelWithDebInfo, package debug symbols for AppStoreConnect
- [`b0dbf25c`](https://github.com/xbmc/xbmc/commit/b0dbf25c9b6c1538462f49ca8efe44221f537ed0) [buildsteps] pass `--disable-debug` for anything but Debug config
- [`562dd54c`](https://github.com/xbmc/xbmc/commit/562dd54c8b55f4f5246e8b30f9b47e879ccc5fa2) [darwin_embedded] remove unused dSYM copying from the packaging scripts
- [`32f47f70`](https://github.com/xbmc/xbmc/commit/32f47f70a0327aaee99665cbf80ad7d6cf49d090) [Games] Let a game client ask for fast-forward
- [`c085541b`](https://github.com/xbmc/xbmc/commit/c085541b1dadb32dd80040b1ab45d5d102d3e6d1) Merge pull request #29861 from cscd98/dolby-vision-xbox
- [`88ae1b47`](https://github.com/xbmc/xbmc/commit/88ae1b4791e57cd2711429872fb5e763cdf19eb4) Merge pull request #29372 from 78andyp/status
- [`262e3a86`](https://github.com/xbmc/xbmc/commit/262e3a86f2f44ec486a19532dd261d95257d856e) [Application] Keep the startup job event alive until Set() returns.
- [`eca4f20a`](https://github.com/xbmc/xbmc/commit/eca4f20a835516c85362c6a01f2a86f7c807d073) [Stacks] Classify stack parts as video so .iso parts don't start RetroPlayer.
- [`b3870943`](https://github.com/xbmc/xbmc/commit/b387094301b30f8580fcd92f1f590e664eab069e) Merge pull request #29758 from 78andyp/crash
- [`9d576155`](https://github.com/xbmc/xbmc/commit/9d576155045f89a365b2777b084f9b603d0ee933) Merge pull request #29929 from garbear/rp-scissor
- [`b6b56b67`](https://github.com/xbmc/xbmc/commit/b6b56b6779679dfb1da655015befd21514730c46) Merge pull request #28476 from garbear/enable-zstd-curl
- [`180aca76`](https://github.com/xbmc/xbmc/commit/180aca7664d605280474d960c880c11fe7132f91) Merge pull request #29570 from kambala-decapitator/apple-release
- [`1d3419b0`](https://github.com/xbmc/xbmc/commit/1d3419b08e9ba8ccf57f607528e96851c811222c) Merge pull request #29837 from garbear/lossless-uri
- [`ae78af5f`](https://github.com/xbmc/xbmc/commit/ae78af5f64d2acb79e4dc4e95dd230b5d04bb806) Merge pull request #29885 from sunlollyking/retroplayer-drop-unreachable-client-warning
- [`fe8292d1`](https://github.com/xbmc/xbmc/commit/fe8292d1019c801b2c8b8b709c34316f48cf50ab) Merge pull request #29893 from sunlollyking/game-fastforward
- [`e80aac24`](https://github.com/xbmc/xbmc/commit/e80aac246026eaa426dd1357fe8cb0e84cc291eb) Merge pull request #29946 from 78andyp/stackfix
- [`2238d34d`](https://github.com/xbmc/xbmc/commit/2238d34d2d6269fe01c490765444a102d5551c95) [test] Test the AUTOINCREMENT rebuild directly
- [`18bce6d2`](https://github.com/xbmc/xbmc/commit/18bce6d2c2c70415860794bc509fd5d316c5e55d) Merge pull request #29902 from neo1973/fix-smartredraw-interim-images
- [`f0534ad1`](https://github.com/xbmc/xbmc/commit/f0534ad16e65ffce53e3d797bd3487334fa818f8) Merge pull request #29960 from 78andyp/dbtestfix
- [`e4957913`](https://github.com/xbmc/xbmc/commit/e4957913df124447a7d379529e584171c51370e4) [cmake] FindCurl: pass resolved zstd to an installed curl config
- [`f2343296`](https://github.com/xbmc/xbmc/commit/f23432964fe34369cd998f36d94c00a09a319ac8) [cmake] FindCurl: restore CMAKE_MODULE_PATH after the curl config lookup
- [`d354fb7d`](https://github.com/xbmc/xbmc/commit/d354fb7dc556dec969dfc583cfdde31fc48e8053) Merge pull request #29961 from 78andyp/windowsfix
- [`0ca6ddb1`](https://github.com/xbmc/xbmc/commit/0ca6ddb1073b0537902b55891ced7503a6c4b91c) [Estuary] Avoid duplicate version names in asset folders (#29913)
- [`f034024a`](https://github.com/xbmc/xbmc/commit/f034024a267559b5dc49b35796420a01a8de5e27) wasm/filesystem: handle XHR credentials safely
- [`51be90c3`](https://github.com/xbmc/xbmc/commit/51be90c393f8c45dc1594cc7efe7fa1d65e3dc1b) Merge pull request #29557 from neo1973/pch-non-windows
- [`cdbfacb1`](https://github.com/xbmc/xbmc/commit/cdbfacb15acc9d6b7b7c24d13fe5f0c84d88154d) [AudioEngine] ActiveAE: Do not mute in-sync samples while measuring the sync error
- [`e384f2f8`](https://github.com/xbmc/xbmc/commit/e384f2f897c6c089f74641c2dbba953230648fa4) [depends] mariadb: declare static zstd plugin in libmariadb.pc
- [`7ca2fcdd`](https://github.com/xbmc/xbmc/commit/7ca2fcdde53b04ded54f6031db5035c8150569cf) Merge pull request #29896 from sunlollyking/tz-bias-before-1970
- [`8743c6cf`](https://github.com/xbmc/xbmc/commit/8743c6cf564198ef833f6ec5368c47a6a3f8561d) Merge pull request #29781 from malard/remove-games-window-dead-code
- [`b4a8b410`](https://github.com/xbmc/xbmc/commit/b4a8b410c2cc72c6e2d750633329ee230d1be87e) Merge pull request #29980 from 78andyp/webosfix
- [`0acda0b8`](https://github.com/xbmc/xbmc/commit/0acda0b8b7d34b7e3b284f68cce56456b15b93af) [posix][smb] percent encode the colons of an IPv6 host again
- [`c13d40b9`](https://github.com/xbmc/xbmc/commit/c13d40b95b0073717a1d825dcad6f6bea34cb547) [posix][smb] read errno before strerror() when reporting failures
- [`37a2ca24`](https://github.com/xbmc/xbmc/commit/37a2ca24bc212767319a6db29a49ee9d111c6cf6) [posix][smb] treat libsmbclient's offset EINVAL codes as EINVAL
- [`f0a88217`](https://github.com/xbmc/xbmc/commit/f0a882175f9e60b7bca0ef55302bc757a3b38f4a) [dialogs] CGUIDialogExtendedProgressBar: Open dialog asynchronously
- [`9f66e981`](https://github.com/xbmc/xbmc/commit/9f66e981b0d1228b33bf040f1d1cda7cd8657f14) [dialogs] Test that GetHandle() does not wait for the GUI thread
- [`899f4bc6`](https://github.com/xbmc/xbmc/commit/899f4bc644c584570839fa9195256149e58712a6) Merge pull request #29984 from ksooo/activeae-sync-no-mute
- [`1e3e298b`](https://github.com/xbmc/xbmc/commit/1e3e298b68cc6d99fbdc7e3114a81ae2e93f1f6e) Merge pull request #29817 from clementperon/upstream/08-filesystem-network
- [`24ebd0f2`](https://github.com/xbmc/xbmc/commit/24ebd0f2f7c48ca7a7b3f2a7a5c1816355f8b6dd) Merge pull request #29925 from MikeSiLVO/fix-getlabel-pending-image
- [`8fc88d5a`](https://github.com/xbmc/xbmc/commit/8fc88d5a9773de75b5a67a6ea38cdaaee90e5157) Merge pull request #29969 from 78andyp/ipv6
- [`47ee87ca`](https://github.com/xbmc/xbmc/commit/47ee87ca616578267a0d34c6759918807f605cc5) Merge pull request #29945 from 78andyp/crash2

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/ef8105c7...47ee87ca)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261021-47ee87ca-master_arm.ipk

---
## Kodi 23.0-ALPHA1 — 20261017-ef8105c7

**Homebrew Version:** `23.26.290`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-17 07:44:07 PDT`

**Commits:** 33

### All Commits

- [`243dbe71`](https://github.com/xbmc/xbmc/commit/243dbe712c8dcd245ce3a9ed91ad959b431f959e) [Windows] Enable ccache for Visual Studio builds
- [`61c7d72e`](https://github.com/xbmc/xbmc/commit/61c7d72e7b9c4bcea24c7175f67bfa2a675aaa82) utils: add CGLBufferArena for small shared vertex ranges
- [`235eb321`](https://github.com/xbmc/xbmc/commit/235eb321dcd67ff026b654c15b43c2b0ede0dc96) guilib/GUIFontTTFGLES: share text vertex storage through a buffer arena
- [`bda2d5ba`](https://github.com/xbmc/xbmc/commit/bda2d5ba218be570317b80f157188ac7f8e85b10) [games] Answer ListItem labels from a game's own details
- [`316c7b98`](https://github.com/xbmc/xbmc/commit/316c7b9865d4536001c4257095049c2bf5bf09b9) [games] Sort a game list by title, year and genre
- [`45b3bac4`](https://github.com/xbmc/xbmc/commit/45b3bac450659d911502c1a2f3e75111b40caaf4) guilib/GUIFontTTFGLES: shrink text vertices from 24 to 16 bytes
- [`aa4661a8`](https://github.com/xbmc/xbmc/commit/aa4661a8a2d66ae2e85e68f5986db208aa110f16) [Video][Database] Fix a clean listing an episode once for each folder of its show.
- [`53d4ca8c`](https://github.com/xbmc/xbmc/commit/53d4ca8c78fdbeb5a17d2863d80efcece670828d) [Video][Database] Keep movie art the new default version lacks.
- [`30be4789`](https://github.com/xbmc/xbmc/commit/30be4789b5892bfb179e78a416d40c80e2552e12) [VideoPlayer][Windows] Fix HQ scaler cache in stereo modes.
- [`21cb09df`](https://github.com/xbmc/xbmc/commit/21cb09dfea303c05625359f7bc9e38894ba6307c) [VideoPlayer][Windows] Fix right eye of Pixel Shaders output in split stereo modes.
- [`564a6417`](https://github.com/xbmc/xbmc/commit/564a6417b5cf201c6a92ca0086386e72248da13c) [GUI] Age dirty regions once per frame in stereo modes.
- [`4208561c`](https://github.com/xbmc/xbmc/commit/4208561ce51ada45e2c6490e4c3823ca0f85b58c) [depends] Update TagLib to 2.3.2
- [`7692b7c6`](https://github.com/xbmc/xbmc/commit/7692b7c653af7ad2c18020b3bac255398de6640e) [Video] Don't re-import movies already in the library on update.
- [`670ef0f0`](https://github.com/xbmc/xbmc/commit/670ef0f04f9682bd03b660e872cdd7ccdabe0bf8) [guilib] Allow textures to keep subpixel positions
- [`6fab3d57`](https://github.com/xbmc/xbmc/commit/6fab3d575aebeaa1821d1fbaf346f234b93b9864) [guilib] Keep subpixel textures fractional only while they move
- [`b6dfbb1f`](https://github.com/xbmc/xbmc/commit/b6dfbb1fac45cefd257debb5a3a747fd10b3d467) [guilib] Settle subpixel textures a moment after they stop
- [`9a1e3f8c`](https://github.com/xbmc/xbmc/commit/9a1e3f8c5f05d59639186b71cf1ce3db8d1df5f2) [Video][Bluray] Decouple context menu 'Choose Playlist' from automatically playing the choice. This allows selection separately to playback.
- [`ad13d6db`](https://github.com/xbmc/xbmc/commit/ad13d6db8192b0cf1c42191c105bcaefecf939d0) [UDF] Read ahead when reading a few blocks of an image
- [`5376187a`](https://github.com/xbmc/xbmc/commit/5376187af7814c6880e00711aae7852240b05f78) [UDF] Don't read each file's size when listing without file info
- [`c88b87b0`](https://github.com/xbmc/xbmc/commit/c88b87b01b98f3c6c382ed269dd625b710e1c53b) [DiscsUtils] Look for a bluray image's index in BDMV first
- [`664c98a4`](https://github.com/xbmc/xbmc/commit/664c98a47986902d7cb6f22d35fd9fc202a25479) Merge pull request #29835 from sunlollyking/game-listitem-labels
- [`1f09aebf`](https://github.com/xbmc/xbmc/commit/1f09aebfa7856f11d8e3c46209c4da6bc594f231) Merge pull request #29839 from garbear/update-taglib
- [`f31214e8`](https://github.com/xbmc/xbmc/commit/f31214e82e7b7e2f13193fed9737bef00cd11016) Merge pull request #29716 from clementperon/gles-font-vertex-arena
- [`ca2ccdc8`](https://github.com/xbmc/xbmc/commit/ca2ccdc855ba2b9024c95e0a03d17b2841ae8f4d) Merge pull request #29822 from garbear/windows-ccache
- [`efc26d71`](https://github.com/xbmc/xbmc/commit/efc26d719f8832d03e7694378ff82c5b7313a3e4) Merge pull request #29857 from 78andyp/delete2
- [`6581bb80`](https://github.com/xbmc/xbmc/commit/6581bb809145540fa0ceb78d56a1c2a8930f4f31) Merge pull request #29672 from 78andyp/missing
- [`4e681966`](https://github.com/xbmc/xbmc/commit/4e681966b251c6d561a496a66c355af81c59df49) Merge pull request #29410 from 78andyp/various
- [`fd041b7d`](https://github.com/xbmc/xbmc/commit/fd041b7de9ce12eefcb02544ab5a2759e9e9c370) Merge pull request #29859 from 78andyp/stereo
- [`48dec8fb`](https://github.com/xbmc/xbmc/commit/48dec8fb6957596357cf39bc08ef51b901721af6) Merge pull request #29742 from 78andyp/test
- [`c7c26084`](https://github.com/xbmc/xbmc/commit/c7c26084f84b258fb59bb51a84cd10a70256b26a) [Estuary] Fix video version icons and labels (#29832)
- [`85cd79a0`](https://github.com/xbmc/xbmc/commit/85cd79a00cfaff6212cf5265c91f92fddb9846a5) Merge pull request #29493 from kel-mo/gui-subpixel-textures
- [`fb170c24`](https://github.com/xbmc/xbmc/commit/fb170c2456abf471da6f4a630a10ec0edfbd5a30) [Windows] Report the selected ccache and its statistics after the build (#29881)
- [`ef8105c7`](https://github.com/xbmc/xbmc/commit/ef8105c71ca79843ec58b088bfb5ea25349ab510) Merge pull request #29894 from 78andyp/discperf

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/41a645ab...ef8105c7)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261017-ef8105c7-master_arm.ipk

---
## Kodi 23.0-ALPHA1 — 20261015-41a645ab

**Homebrew Version:** `23.26.288`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-15 09:02:47 PDT`

**Commits:** 89

### All Commits

- [`b34415bd`](https://github.com/xbmc/xbmc/commit/b34415bde03ff6be4519d365bde975bb50cb4a06) Use local .strm files as subtitle anchors
- [`a169167d`](https://github.com/xbmc/xbmc/commit/a169167d30b648db91c0744984be3d790c5e67c5) SMBWSDiscoveryListener: fix stack buffer overflow in UDP receive path
- [`ec06f163`](https://github.com/xbmc/xbmc/commit/ec06f1638551f93edd29ea07aef5522379626c26) cc_decoder: fix heap buffer overflow in cc_to_text
- [`9d1c26c2`](https://github.com/xbmc/xbmc/commit/9d1c26c23121f94887aa7c5b47d7a24a282bb2ae) [python] Release the GIL in xbmc.getInfoLabel() and getInfoImage()
- [`400cbba6`](https://github.com/xbmc/xbmc/commit/400cbba6f7b9c5fff81c863e5d3542f4220e8cb8) [skin] Guard skin setting registration and access with a lock
- [`c65b242d`](https://github.com/xbmc/xbmc/commit/c65b242d412fa388faf70ae07c2b643f4dbb92fd) [wayland] Fail video sync setup when the refresh rate is unknown
- [`b4db7800`](https://github.com/xbmc/xbmc/commit/b4db780014fc8b038f637a3aacdab1b8fbd63668) [wayland] Use the refresh rate of the presented event for video sync
- [`c168ae8b`](https://github.com/xbmc/xbmc/commit/c168ae8b1418d74b10498566674fbbc8d087bb74) [VideoPlayer] Don't reopen a stream if it is already selected
- [`aea60c33`](https://github.com/xbmc/xbmc/commit/aea60c33fce87f0fcd98bc8ce9ae82be6e7b822d) [games] Keep each game's saves and state in one folder
- [`9d1a3fb1`](https://github.com/xbmc/xbmc/commit/9d1a3fb14f9800ed3e19177ca32348515719d563) [games] Find a game's folder from any form of its path
- [`ce5a21ff`](https://github.com/xbmc/xbmc/commit/ce5a21ff746eb5d77457194fddb5a6600e46f467) [GUI] Play the selected cue sheet track when started from the files view
- [`955f6ee1`](https://github.com/xbmc/xbmc/commit/955f6ee1f33fbffdf351a87bf37834b43fc185ee) RetroPlayer: Advance the shader frame count at the playback speed
- [`ace0110e`](https://github.com/xbmc/xbmc/commit/ace0110e5cfbe86a3b4f5256b4a55314ee558de8) [games] Key a game's folder on its last two folders and file name
- [`f9a662af`](https://github.com/xbmc/xbmc/commit/f9a662afe9eb9d5abff5231e6a0699d9bce88108) [ActiveAE] Reset AC3/EAC3 encoder on flush when transcoding
- [`a282c288`](https://github.com/xbmc/xbmc/commit/a282c288d30f8ce30b70332abed3a9d3dd494bc6) [guilib] Protect m_vecTextures with m_section in CGUITextureManager
- [`c22e472f`](https://github.com/xbmc/xbmc/commit/c22e472fa18422aaeabbef690f6809870bae93ee) [video] Start the thumb loader after the items are filtered
- [`3f48799f`](https://github.com/xbmc/xbmc/commit/3f48799fb0c708ca4546871f77090856b42b1b7e) [guilib] Protect the list item layouts against concurrent SetInvalid()
- [`f66b6c42`](https://github.com/xbmc/xbmc/commit/f66b6c42342ffc3c25e7fe5f6b4c0dd8c07095e3) [filesystem] Lock the cache in CDirectoryCache::ClearFile()
- [`a5ff10c5`](https://github.com/xbmc/xbmc/commit/a5ff10c5db4cc020966d7bbc27f64efd128242e7) [pvr] Channel group thumbs: Skip channels without icon
- [`deadbd47`](https://github.com/xbmc/xbmc/commit/deadbd470285558e371c07220f4476ee39f33df5) [pvr] Channel group thumbs: Refresh when the tiled channel icons change
- [`5cfdea9a`](https://github.com/xbmc/xbmc/commit/5cfdea9ac7d5e4678cd7a9fd71570bad69022724) [music] Stop the thumb loader while the items are filtered
- [`66fa879c`](https://github.com/xbmc/xbmc/commit/66fa879ca70e80e313b919c9ec3d41d52d0e729e) [guilib] Keep processing windows while background images are loading
- [`3ebe1534`](https://github.com/xbmc/xbmc/commit/3ebe15341bc77dc0b8074a8e9b98156ecaf14626) [guilib] Process all dialogs when a dialog changes
- [`b0deb27f`](https://github.com/xbmc/xbmc/commit/b0deb27f586d8be82198ee3653181242e78415be) [skin] Notify windows when skin timers change
- [`bfe67cfb`](https://github.com/xbmc/xbmc/commit/bfe67cfba71f8c4ff110c3d1b932f90d5b7b8209) [guilib] Mark fade labels dirty when their labels change
- [`6f8e5925`](https://github.com/xbmc/xbmc/commit/6f8e592550ea100712da704bc113810c8a018e8d) [guilib] Keep retained list item layouts across container resets
- [`d16bbe69`](https://github.com/xbmc/xbmc/commit/d16bbe69f5e4661b4d03d9f8648678c97deca732) pictures: stop over-allocating the image rotation buffer
- [`f28581a6`](https://github.com/xbmc/xbmc/commit/f28581a6d42e6d26fcc85a5e499e4024e2ef01e9) [pictures] Keep picture details across restarts
- [`8d041a06`](https://github.com/xbmc/xbmc/commit/8d041a061a15c8e1212209a47d7c32335cfb5eb5) [games] Keep a game's folder and cheat choice when the library moves
- [`9a51b8dd`](https://github.com/xbmc/xbmc/commit/9a51b8dd76dd0e36961e42a7db752a964986d7b0) [Windows] Bump pycryptodome to 3.24.1
- [`266f5065`](https://github.com/xbmc/xbmc/commit/266f5065a76caa19184ad3fb21affb879115e705) windowing/gbm: apply the GUI size limit on 1080p displays too
- [`2a8e25c3`](https://github.com/xbmc/xbmc/commit/2a8e25c3f26f8a4c6b40e63cbcfe525c9da97805) [pvr] Channel group thumbs: Replace magic number for max tiles
- [`3dcee3b1`](https://github.com/xbmc/xbmc/commit/3dcee3b1eba8971dd441616b20684469a741c488) Merge pull request #29615 from thexai/pycryptodome-3.24.0
- [`e5d5ba7e`](https://github.com/xbmc/xbmc/commit/e5d5ba7eeea728f68ad4b16242450c9c4d64e6bd) Merge pull request #29689 from sunlollyking/games-per-game-folder
- [`cbf502d9`](https://github.com/xbmc/xbmc/commit/cbf502d998cc50d9fd7eb16bae962ca9e1b554ca) Merge pull request #29786 from Portisch/fix_main_menu_selection
- [`f881012b`](https://github.com/xbmc/xbmc/commit/f881012b10c547622d9c5a75d7255fbcf5f3c9a0) Merge pull request #29545 from TristanInSec/fix/wsdiscovery-recvfrom-oob
- [`5fff0621`](https://github.com/xbmc/xbmc/commit/5fff062126f050d9f1d8f71de46704fdf26636fd) Merge pull request #29546 from TristanInSec/fix/cc608-text-heap-overflow
- [`679620af`](https://github.com/xbmc/xbmc/commit/679620af9e29d13abb5d16f096bbece72f12f16b) Merge pull request #29692 from sorin-suciu/fix-files-view-cue-track-selection
- [`8fd95313`](https://github.com/xbmc/xbmc/commit/8fd95313199e39d68c6c01e11d5113da870bf21c) Merge pull request #29714 from VuzzyM/reset-encoder
- [`0a8f5abe`](https://github.com/xbmc/xbmc/commit/0a8f5abe2d0ca6afacb51eb89acb046dc04ae446) [games] Keep a game's folder when its Windows drive letter changes
- [`d825e2ce`](https://github.com/xbmc/xbmc/commit/d825e2ce780bba6be7bff7fd38dee25e33d95c51) Merge pull request #28077 from senendds/fix-strm-subtitles
- [`8cfc1476`](https://github.com/xbmc/xbmc/commit/8cfc1476996bb185373e4d6f4bdda67ae7fd361c) [Games] Name the file an emulator is missing when it can't load a game
- [`71d5d847`](https://github.com/xbmc/xbmc/commit/71d5d84769c4c531ac29f1121fd46dba2222dfef) Merge pull request #29639 from sunlollyking/retroplayer-shader-speed
- [`42c0ea8d`](https://github.com/xbmc/xbmc/commit/42c0ea8db6df87993af2802526b4d9dc7d248219) RetroPlayer: Count shader frames at the speed the game rewinds
- [`8f988431`](https://github.com/xbmc/xbmc/commit/8f988431ca75ee66689ccb1f8e4697eb8ef64aa8) Merge pull request #29548 from kel-mo/python-infolabel-release-gil
- [`0d8f0b17`](https://github.com/xbmc/xbmc/commit/0d8f0b174efb7b8a921a708b2b7073a6684f89a0) [guilib] Allow textures to be mipmapped
- [`53aef6f9`](https://github.com/xbmc/xbmc/commit/53aef6f98e3ea3c4037e2e8818edc29e0f087922) [cmake] Fix Windows LCMS2 definitions after rediscovery
- [`cf1f47ac`](https://github.com/xbmc/xbmc/commit/cf1f47ac15d70fbc6223a42d5fa8abe59ffe594a) Merge pull request #29796 from popcornmix/rotatebuffer
- [`37d3f24e`](https://github.com/xbmc/xbmc/commit/37d3f24ebc1c4e93c9c20604bc2c4a95f8454ffd) Merge pull request #29739 from ksooo/pvr-channel-group-thumbs
- [`13b52717`](https://github.com/xbmc/xbmc/commit/13b52717245dd41459bf3df0f7584ccbe2df902a) threads: make Join() with a max() timeout actually wait
- [`43edf43d`](https://github.com/xbmc/xbmc/commit/43edf43dc66fb3a18e85bab3a80ad0c020c66472) [Video][Player] Implement seek whilst paused.
- [`6d4e50ac`](https://github.com/xbmc/xbmc/commit/6d4e50ac3e9b99bbf4eaabf4b0664a3684bc0316) [Video][Player] Remove unused variable.
- [`02dc672f`](https://github.com/xbmc/xbmc/commit/02dc672f484f3cf82055953f2812027554e67129) [RenderManager] Fix pause -> rewind -> pause did not stop smoothly.
- [`c44272cd`](https://github.com/xbmc/xbmc/commit/c44272cd0e991e2d131da6f5b0337de74db39ea1) [Video][Player] Fix excessive seeks on rewind.
- [`74ee3ae1`](https://github.com/xbmc/xbmc/commit/74ee3ae14658787fc14b0e3eed0f22931873239e) [Video] Publish stream details once instead of rebuilding them in place.
- [`096e214f`](https://github.com/xbmc/xbmc/commit/096e214fe155450e311d92515cddef41e1f82225) Merge pull request #29818 from sunlollyking/pictures-details-cache
- [`1a7630c0`](https://github.com/xbmc/xbmc/commit/1a7630c092c1c786789e47ef5731d09b4de78b81) [Video] Fix missing movie information within sets (#29736)
- [`2f83a932`](https://github.com/xbmc/xbmc/commit/2f83a932f9b328e1f69958d07ad9a8e53f5e2971) [cleanup] Remove a header, two members and a property nothing uses (#29696)
- [`381ccc8d`](https://github.com/xbmc/xbmc/commit/381ccc8d62c4ce951a6e18bb41b8c1e6120bd1d2) [VideoDatabaseDirectory] Read the details level with the variant's fallback (#29697)
- [`8785725c`](https://github.com/xbmc/xbmc/commit/8785725c669eda8ede27926fd8378db61f1a8d62) [VideoPlayer][RDS] Accept language code 1, Albanian (#29698)
- [`0b312d14`](https://github.com/xbmc/xbmc/commit/0b312d14f6604b4a00a359b88a9bd24a457771f1) [Doxygen][CMusicDatabase] Describe the song and album parameters as they are (#29705)
- [`4673b0f6`](https://github.com/xbmc/xbmc/commit/4673b0f6ed929bfc7bf13f020ad6ecacd7699c94) [builtins][CleanLibrary] Clean the content named in any case (#29712)
- [`afe9b316`](https://github.com/xbmc/xbmc/commit/afe9b316af6ce48c89d3eded3b0613620bf6f7da) [language][CLangInfo] Take the region's long date format for a regional long date (#29718)
- [`492d01b0`](https://github.com/xbmc/xbmc/commit/492d01b042761bec828bbb31b1a3d79e34bc7e79) [UPnP][UPnPInternal] Keep every artist and genre of a song, and share the mapping's conversions (#29731)
- [`4aca3567`](https://github.com/xbmc/xbmc/commit/4aca3567f4fecba31a27b069dc078557512e4a16) [playlists] Add a smart playlist feed that deals its matches without repeats (#29713)
- [`1e5bc7aa`](https://github.com/xbmc/xbmc/commit/1e5bc7aaf32e1b5456b63c0e57442fa055206034) [media][ContentNames] Name the remaining content strings in library URLs, databases and UPnP (#29699)
- [`1d03a755`](https://github.com/xbmc/xbmc/commit/1d03a755617307fb69f5cb3a1dc0306a53a10b5b) [pictures][CPictureInfoTag] Replace SetInfo with SetResolution and SetDateTimeTaken (#29695)
- [`bd7f9f99`](https://github.com/xbmc/xbmc/commit/bd7f9f99d2d5e2a229058108a4893f35bab4a05e) [Video][VideoUtils] Set a show or season's episode counts in one place (#29701)
- [`25d6103d`](https://github.com/xbmc/xbmc/commit/25d6103d83eeb23c18c6c656959a56127acd7040) [application] Skin, volume and power handle their own setting callbacks (#29710)
- [`08fce0ca`](https://github.com/xbmc/xbmc/commit/08fce0ca8556e0260ffc34102678d5f2a43396ef) [utils] Name the default images a skin provides once (#29725)
- [`0a18f184`](https://github.com/xbmc/xbmc/commit/0a18f1848bce2f479b59e27597a740f65a689ad6) [Util] Find the playlists folder wherever the user keeps it (#29726)
- [`685dc56f`](https://github.com/xbmc/xbmc/commit/685dc56fdcaa97302e733abcae144350fa53cd1f) RetroPlayer: Stop the savestate capture test racing its worker thread (#29745)
- [`4088fb0e`](https://github.com/xbmc/xbmc/commit/4088fb0e914945f569aa87dc02364f510e1d8343) [dialogs] Name the numeric dialog's modes once, as DIALOGS::NUMERIC_MODE (#29727)
- [`4b207809`](https://github.com/xbmc/xbmc/commit/4b2078099e84324da486b2a03349a6ec75b4a2e5) [addons] Name the content a plugin provides in one table (#29711)
- [`590ecc01`](https://github.com/xbmc/xbmc/commit/590ecc017ec6d109969475cf00abec8ef9ab8a65) Merge pull request #29778 from neo1973/fix-smartredraw-background-images
- [`d95558df`](https://github.com/xbmc/xbmc/commit/d95558dfa3acf31d0fe0a65d3477160cee6fe27d) Merge pull request #29735 from neo1973/fix-gui-data-races
- [`03052882`](https://github.com/xbmc/xbmc/commit/030528827a9d524c9a29f14f52798758cc42d07d) Merge pull request #29603 from neo1973/wayland-presentation-refresh
- [`b373a04c`](https://github.com/xbmc/xbmc/commit/b373a04cebb506332d912395f887c5cf77d2cd33) Merge pull request #29518 from kel-mo/gui-mipmap-textures
- [`5d3030c3`](https://github.com/xbmc/xbmc/commit/5d3030c3f358de32895385001627a02c3ad42b35) Merge pull request #29516 from kel-mo/videoplayer-same-audiostream
- [`2160595a`](https://github.com/xbmc/xbmc/commit/2160595a170e9c514fe2c82a1bdc8f69f484fbf2) Merge pull request #29847 from sunlollyking/games-folder-windows-root
- [`07c2b2e1`](https://github.com/xbmc/xbmc/commit/07c2b2e11c02d0164d5055494a4dee9f04e38c47) Merge pull request #29792 from sunlollyking/game-load-failed-message
- [`f918831a`](https://github.com/xbmc/xbmc/commit/f918831ad61bd27197f4162fa6af90385d97ca18) Merge pull request #29848 from sunlollyking/retroplayer-shader-rewind-speed
- [`9e1c5fcd`](https://github.com/xbmc/xbmc/commit/9e1c5fcd0839f28fe824659d73166f4eb4d3ded5) Merge pull request #29852 from garbear/fix-lcms2
- [`86868508`](https://github.com/xbmc/xbmc/commit/868685089456b418f7e230bae5b58260727098d6) Merge pull request #28774 from 78andyp/paused
- [`d6a360cd`](https://github.com/xbmc/xbmc/commit/d6a360cd375d33535a2bd4973ce44451fe6555a4) Merge pull request #29798 from popcornmix/guilimit1080
- [`c8c6c098`](https://github.com/xbmc/xbmc/commit/c8c6c0982d6ca72fea7e91c39e7a1499bf8cda2f) Merge pull request #29853 from popcornmix/joinmax
- [`66dd635f`](https://github.com/xbmc/xbmc/commit/66dd635f802bb715a9c888621334e13d71be0fe5) [RetroPlayer] Fix macOS FBO capture state and test lifecycle
- [`47d81a48`](https://github.com/xbmc/xbmc/commit/47d81a48da4bce1effc53880e5df51a45a348622) Merge pull request #29860 from 78andyp/race
- [`41a645ab`](https://github.com/xbmc/xbmc/commit/41a645ab9e3deb8ae983ab1c3bed8cec1bd6096d) Merge pull request #29877 from garbear/fix-macos-test

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/11f50401...41a645ab)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261015-41a645ab-master_arm.ipk

---
## Kodi 23.0-ALPHA1 — 20261012-11f50401

**Homebrew Version:** `23.26.285`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-13 11:42:26 PDT`

**Commits:** 110

### All Commits

- [`0fd22480`](https://github.com/xbmc/xbmc/commit/0fd22480005614dc1ea0397742aa514cd83629d8) webOS: prefix gcc for LTO plugin
- [`363bb6d2`](https://github.com/xbmc/xbmc/commit/363bb6d208a1e36b093cd483fa6fbc772717d158) [GL] Give rotated controls their perspective back
- [`61c40b4a`](https://github.com/xbmc/xbmc/commit/61c40b4ac8669673fa7776804daeb790ae03baf1) [GUILIB] CGUIImage: report the requested image until one renders
- [`6845bbc3`](https://github.com/xbmc/xbmc/commit/6845bbc3e7fd127ae37706c13692832182ec7f25) [Video][Bluray] Remove orphaned all-episodes branch from GetOrShowPlaylistSelection.
- [`d378e8e7`](https://github.com/xbmc/xbmc/commit/d378e8e73e76cd1083850c57bc100eff69bbf066) [GUILIB] CGUILargeTextureManager: share decodes across nearby display sizes
- [`4a9d15d5`](https://github.com/xbmc/xbmc/commit/4a9d15d5d8fc97b210cb3d3b9aba11508141c8c8) [GUILIB] CGUITexture: draw another loaded size while the requested one loads
- [`6ac01f43`](https://github.com/xbmc/xbmc/commit/6ac01f43ef9fc912192edc19e16b75a2043bd67d) [RetroPlayer] Give shader passes their real texture size
- [`16bdfad7`](https://github.com/xbmc/xbmc/commit/16bdfad73b3fa83f5d860a0674b17e9339f961d8) [Bluray] Take one clip per play item of a multi-angle playlist.
- [`2841ff9e`](https://github.com/xbmc/xbmc/commit/2841ff9e17914c9266d8edf1484bab2bcfb6a3f2) [Bluray] Offer the longest candidate for a single special first.
- [`b1d75acc`](https://github.com/xbmc/xbmc/commit/b1d75acc2151214e19fccf132759b868a5454d72) [Bluray] Apply the minimum special length to a disc holding only specials.
- [`7ff12249`](https://github.com/xbmc/xbmc/commit/7ff12249d99206cae173d8a3a1285625a75eb818) [VideoInfoScanner] Keep a disc's movie when merging its main title fails.
- [`40f3d2e8`](https://github.com/xbmc/xbmc/commit/40f3d2e81ff2f23cb1b681c839e893d5b99b05c6) [VideoInfoScanner] Resolve an episode's bluray playlist as an episode.
- [`5771b85d`](https://github.com/xbmc/xbmc/commit/5771b85d651afba224d680849cc777ec11e5ab85) [Bluray] Don't take a seconds-long named segment as the single title.
- [`502a08c8`](https://github.com/xbmc/xbmc/commit/502a08c83994ea85e2fcf09981312e915d491b28) [Bluray] Keep an episode's stored duration when none is given.
- [`26e7835d`](https://github.com/xbmc/xbmc/commit/26e7835da9f80060ed2b9f6b95825b9f38047abb) [Video] Keep a folder stack's nfo and art inside its own folder
- [`16867be7`](https://github.com/xbmc/xbmc/commit/16867be75bb98333d74e8cc78efadca0a87b0c87) [Joysticks] Fix accelerometer losing its axes
- [`379a214f`](https://github.com/xbmc/xbmc/commit/379a214fe77a51c8a2e2da259e6bb27fa056d7df) Games: Stop rumble when a game's controller is detached
- [`cb30df01`](https://github.com/xbmc/xbmc/commit/cb30df015a37634d340a78265d3ecae0fb43ba22) [Windows][buildsteps] Keep built dependencies between builds, and seed liblzo2's configure checks
- [`aaf1fea8`](https://github.com/xbmc/xbmc/commit/aaf1fea84206c6c85902267564810bf76abea7ec) Games: Stop rumble when a game is paused
- [`90a69eb9`](https://github.com/xbmc/xbmc/commit/90a69eb9e573638c85ac027710191ca33d81c018) [Windows][buildsteps] Key the dependency cache by build configuration
- [`c618c502`](https://github.com/xbmc/xbmc/commit/c618c502b81df409a492ea54a7bf3b30b9003d9b) rendering/gles: own CGUITextureGLES::DrawQuad's drawer as a CRenderSystemGLES member instead of a static local
- [`5cf059fa`](https://github.com/xbmc/xbmc/commit/5cf059fa2804ca64c157b050d68555cf06c47f47) rendering/gles: upload GLES draws through real GPU buffers instead of client-side arrays
- [`beb76f4c`](https://github.com/xbmc/xbmc/commit/beb76f4cdb902217fdbdb6fea05a256d3adc1a38) cmake/wasm: drop -sFULL_ES3=1 now that GLES rendering no longer uses client-side arrays
- [`7c6ef84c`](https://github.com/xbmc/xbmc/commit/7c6ef84c549ce0e04b5c941b36a7be912b493dfc) pictures/gles: destroy CSlideShowPicGLES's GL buffers in Free() instead of relying only on the destructor
- [`2b85cce2`](https://github.com/xbmc/xbmc/commit/2b85cce22933e6e72887f36c6ace5de1ffc7daf4) utils/test: add unit tests for CGLBufferObject
- [`7b68240e`](https://github.com/xbmc/xbmc/commit/7b68240ea6ae697efabab9f8aa650366f0605018) LinuxRendererGLES: keep the buffers behind the clearing quads
- [`a61fbf29`](https://github.com/xbmc/xbmc/commit/a61fbf29f6deb69ddd1f967c5432e60edb5937e9) [VideoPlayerVideo] Skip late packets to the next keyframe when the decoder can't keep up.
- [`06e26a37`](https://github.com/xbmc/xbmc/commit/06e26a37fe10774ef7fb4bc13359ecd9f78531da) [VideoRenderers][Windows] Don't convert the same picture again on every refresh.
- [`66c46139`](https://github.com/xbmc/xbmc/commit/66c461390b7dd5ab04bb189425138e3bb1c031d9) [VideoRenderers][Windows] Convert at view size when downscaling with shaders.
- [`4524d544`](https://github.com/xbmc/xbmc/commit/4524d544deade8fc68e8028bd78303dddb75ae7c) [VideoRenderers] Use the configure result after a slow renderer configure.
- [`a6049882`](https://github.com/xbmc/xbmc/commit/a604988287eddf139d0a5ed3eddea0fad088e134) [VideoRenderers][Windows] Don't HQ scale the same picture again on every refresh.
- [`2a383940`](https://github.com/xbmc/xbmc/commit/2a383940716ce35ee18e301d10986be40ba4d51c) [Bluray] Notice a disc replaced at the same path.
- [`7dbc21f5`](https://github.com/xbmc/xbmc/commit/7dbc21f5f5702886bd86b8843b30f53adef8d2e4) [Bluray] Count only the playlists offered when logging a silent choice.
- [`0ace3fba`](https://github.com/xbmc/xbmc/commit/0ace3fbad36206d1c323f3e362c4a65c6d8ee17b) [Bluray] Treat a picture-in-picture copy of a playlist as a copy.
- [`a2ca18af`](https://github.com/xbmc/xbmc/commit/a2ca18afbd5ee5ce4de5b8c74ee0a1e50c671420) [Bluray] Prefer the Dolby Vision copy of a playlist.
- [`29341d47`](https://github.com/xbmc/xbmc/commit/29341d47403104e82490785b299fca31937a2d46) [Bluray] Record which disc a probe cached its name from.
- [`5cafbfca`](https://github.com/xbmc/xbmc/commit/5cafbfcae5219da935a84ef8867a3ae9a48a1473) Merge pull request #29608 from 78andyp/blurayfixes
- [`3ad030d9`](https://github.com/xbmc/xbmc/commit/3ad030d9b7aa326edb67cff2d7bd1caa1db78108) VAAPI: fix build with ffmpeg 7.0.3
- [`6acfac6f`](https://github.com/xbmc/xbmc/commit/6acfac6ffba80898db9d022ecaf69c905881e1e9) AEEncoderFFmpeg: fix build with ffmpeg 7.0.3
- [`3c316917`](https://github.com/xbmc/xbmc/commit/3c3169171165607a7637c7c5dbd876a637e2109a) InputStreamAddon: fix build with ffmpeg 7.0.3
- [`2bfb4bcf`](https://github.com/xbmc/xbmc/commit/2bfb4bcf0e75481fe82a9b005248dce0e5b2acb0) [Windows] Add option to render on the high-performance GPU.
- [`b0a30c69`](https://github.com/xbmc/xbmc/commit/b0a30c69c72a7a5abbee2baadfb83f73eabce8c4) Merge pull request #29719 from 78andyp/allepisodes
- [`35881862`](https://github.com/xbmc/xbmc/commit/3588186266bae749ff59e0bf15128541355de865) Merge pull request #27810 from cscd98/lto-prefix
- [`da16b2f0`](https://github.com/xbmc/xbmc/commit/da16b2f0077d61474bbf9955b42f9f41f82c59b5) Merge pull request #28558 from clementperon/gles-webgl2-client-arrays
- [`15edfb92`](https://github.com/xbmc/xbmc/commit/15edfb926868a9de3cd8e6df2315ab428a0a4b25) [GUILIB] CGUILargeTextureManager: reuse a loaded decode instead of rounding
- [`6b88075d`](https://github.com/xbmc/xbmc/commit/6b88075dde1e9d4467b8cab7eef8c194157e286b) [pictures] Don't stall a slideshow on a picture that won't load
- [`c4865d88`](https://github.com/xbmc/xbmc/commit/c4865d887ca8a95fa5f2f0b11286613aae01a1c6) [pictures] Don't change the display mode for a slideshow video
- [`d07932a5`](https://github.com/xbmc/xbmc/commit/d07932a5cef29aa92b286d6e416ae492c1f1f618) [addons] Show progress for background add-on installs
- [`5c2e3d2d`](https://github.com/xbmc/xbmc/commit/5c2e3d2d3627a2b1ea598488ecff503620376c27) Merge pull request #29519 from 78andyp/video
- [`e33ba5ae`](https://github.com/xbmc/xbmc/commit/e33ba5aeed5384cd63ef0b117bf2a6c80e54dd6d) [Video][CGUIWindowVideoBase] Let a video library path carry a filter, as a music library path does (#29654)
- [`08c80e49`](https://github.com/xbmc/xbmc/commit/08c80e49d1bb31a942b4a1d54a666860289c2e89) [i18n][CIso3166_1] Remove the English country names and the lookups nothing calls (#29633)
- [`d3630f5e`](https://github.com/xbmc/xbmc/commit/d3630f5ecd932e90e1e4d9c1f1dd54355888bfab) [AirTunes] Clear the previous track's cover when a track has no cover art (#29629)
- [`bda459fa`](https://github.com/xbmc/xbmc/commit/bda459fa15c0639d9f93a910b5bb7e8465aefe4e) [DatabaseUtils] Return a movie's filename column without the numbered column offset (#29628)
- [`7d48bf1e`](https://github.com/xbmc/xbmc/commit/7d48bf1e487f5b1b346311f8158c7faf6421bfeb) [cleanup] Remove three members nothing calls (#29618)
- [`d3ae06c4`](https://github.com/xbmc/xbmc/commit/d3ae06c4961ea56b5dc786df41129852c3c2a4c9) [music][CGUIWindowMusicNav] Open the box sets for the boxsets start folder (#29602)
- [`5d90391c`](https://github.com/xbmc/xbmc/commit/5d90391c21708c7bc0d7a2d2e31159b9dbb4ff79) [cleanup] Nest the named constant groups inside their area's namespace (#29598)
- [`2cd210f2`](https://github.com/xbmc/xbmc/commit/2cd210f2a37cfc67a096df7daaf0cb2fa3c289c7) Merge pull request #29693 from 78andyp/stacknfo
- [`5544ff63`](https://github.com/xbmc/xbmc/commit/5544ff63d1ebedb8142f22e72ca1d0b138dfdf67) [pictures] Show HDR video in a slideshow
- [`745c94d7`](https://github.com/xbmc/xbmc/commit/745c94d7be57af3ae18f76b3998d86343fd30aea) [VideoPlayer] Measure the content geometry of a file by sampling it (#29600)
- [`5f2cb9bc`](https://github.com/xbmc/xbmc/commit/5f2cb9bc7e008c4bfbeb506b2e926dcfc446afb1) [Video][CBlurayDirectory] Join the stream languages through one helper (#29729)
- [`5ac32066`](https://github.com/xbmc/xbmc/commit/5ac3206627baa61a68f8166c8b5ee270374d8bbb) [JSON-RPC][CTCPServer] Serve each connection on its own thread, and let no peer hold up the server (#29636)
- [`e48e05ec`](https://github.com/xbmc/xbmc/commit/e48e05ec874cbac6bbdb2de91e6d28d92fc7dcb0) [settings] Don't hold a setting's lock while its change callbacks run (#29011)
- [`bab56fad`](https://github.com/xbmc/xbmc/commit/bab56fad18a51cc0106b1afb8d0a280c9498a814) [pictures] Keep a video slide's thumbnail up until the video starts
- [`5958d6f8`](https://github.com/xbmc/xbmc/commit/5958d6f8524baf42acc8f62724343fa1c78f0d67) [pictures] Add a setting to show a picture's date and time on screen
- [`f929f6f9`](https://github.com/xbmc/xbmc/commit/f929f6f95b1c64a083606b096b8f120b2ea37689) [media] Name what a library item is with KODI::MEDIA::TYPE, not a string (#29707)
- [`320fc963`](https://github.com/xbmc/xbmc/commit/320fc9639248edaa0cd41406af87f8d07919a9b0) [pictures] Show a video's thumbnail in a running slideshow too
- [`d2313f95`](https://github.com/xbmc/xbmc/commit/d2313f95445db2e919d175d52b53931ec49012d8) [Video][Database] Fix a targeted library clean skipping disc rips.
- [`fd685a2b`](https://github.com/xbmc/xbmc/commit/fd685a2bcaa1574c06969d15d26de3a997bec6c5) [Video][VideoInfoScanner] Fix the clean after a scan missing video extras.
- [`dc1acc9d`](https://github.com/xbmc/xbmc/commit/dc1acc9db8f5560dcf7cfd382200dcdb0eac8aca) [Video] Fix a failed movie refresh leaving its versions and extras behind.
- [`a32c743e`](https://github.com/xbmc/xbmc/commit/a32c743eea13d1c7fcdc206cb42310bd19a5f75f) [Video][Database] Fix the announcement of versions and extras removed by a clean.
- [`e45c1579`](https://github.com/xbmc/xbmc/commit/e45c1579a4bb7668b5b3f0f2a1ffb643ff1fdde8) [Video][Database] Fix a default version without art leaving the movie with none.
- [`5456b11a`](https://github.com/xbmc/xbmc/commit/5456b11aaee56c64d2ba410a6020df4ae83acacb) [Video][Database] Fix a clean asking about versions and extras outside the sources.
- [`d8d5ef34`](https://github.com/xbmc/xbmc/commit/d8d5ef3473a631373a760175ee6ea1970d377369) [Video][Database] Fix a clean removing a movie whose default version is offline.
- [`c85ca0d6`](https://github.com/xbmc/xbmc/commit/c85ca0d64683d91dd986fb55ac3e805782e7ec94) [Video][Database] Add tests for the library clean.
- [`5ce6a028`](https://github.com/xbmc/xbmc/commit/5ce6a028f991a230f3522f374b8368203a4977a1) [Video][Database] Add tests for the clean of paths and played files.
- [`79d7cb4a`](https://github.com/xbmc/xbmc/commit/79d7cb4a0f4a4d9d26d338bb52967efd6fa73eac) [Video][Database] Fix GetSourcePath() swapping two settings of a parent source.
- [`db1c86a0`](https://github.com/xbmc/xbmc/commit/db1c86a0e0f5eb113a195a723627bb6b20e2aaa4) Merge pull request #29724 from sunlollyking/joystick-accelerometer-axes
- [`5c97b631`](https://github.com/xbmc/xbmc/commit/5c97b631cfc0d2741f5b18990fa6722ad2b338bd) Merge pull request #29579 from 78andyp/gpu
- [`0c89745d`](https://github.com/xbmc/xbmc/commit/0c89745df922e29d634bb93a2402843905bf1e51) Merge pull request #29793 from bkuhls/master-fix-ffmpeg-7.0
- [`99019b2b`](https://github.com/xbmc/xbmc/commit/99019b2bb2219fab2aa63787f58607bb092ccde4) Merge pull request #29732 from malard/buildsteps-win-cache
- [`02034d89`](https://github.com/xbmc/xbmc/commit/02034d89f3fe8668649043d2827c2e5880608667) [GUILIB] CGUILargeTextureManager: reuse a decode only at its exact size
- [`f414b1bb`](https://github.com/xbmc/xbmc/commit/f414b1bbce4b3be0e2416ec5319a03cb9c86ebbe) Merge pull request #29650 from ksooo/addon-install-progress
- [`154fe01d`](https://github.com/xbmc/xbmc/commit/154fe01dc091df4355551de8341df149cf455aaf) [pictures] Skip a video that won't play in a slideshow
- [`acb94725`](https://github.com/xbmc/xbmc/commit/acb947255af6a236a40ca164939d697d9b1e547b) guilib: keep CGUITexture quads in skin space between frames
- [`721d3ca6`](https://github.com/xbmc/xbmc/commit/721d3ca639c49e135a9b803d68a26a0c0dd9981e) rendering/gles: draw GUI textures from static vertex buffers
- [`fb69f7ae`](https://github.com/xbmc/xbmc/commit/fb69f7ae65eec0d19552d38a0eba4339c8f732bb) rendering/gles: draw CGUITexture::DrawQuad from a static unit quad
- [`8d075085`](https://github.com/xbmc/xbmc/commit/8d0750859772072f57f62f8e6d808e737beea37d) OverlayRendererGLES: draw bitmap overlays with DrawGUIQuad
- [`a49b99be`](https://github.com/xbmc/xbmc/commit/a49b99be5686044b3f5b7204dc7a5aba53a207d1) RetroPlayer: draw the GLES game quad with DrawGUIQuad
- [`f34df188`](https://github.com/xbmc/xbmc/commit/f34df1882ea2d3a821244ea47fe649de3aaa5d45) pictures/gles: draw the slideshow with DrawGUIQuad
- [`76ac6163`](https://github.com/xbmc/xbmc/commit/76ac6163b0993d4c4a53a3fcc5b9ffe438bbba6e) LinuxRendererGLES: draw the clear quad and black bars with DrawGUIQuad
- [`d4706119`](https://github.com/xbmc/xbmc/commit/d4706119516f9c98c6539ea5bf1edf7737402a10) LinuxRendererGLES: draw the video passes from the static unit quad
- [`bfa1047d`](https://github.com/xbmc/xbmc/commit/bfa1047dfdd21bfa113e8d0d1bdfa1558b11ec6b) RetroPlayer: draw the GLES renderers' game quad with DrawGUIQuad
- [`0122e10a`](https://github.com/xbmc/xbmc/commit/0122e10a54a6d000aa66b3e9798c19e167061c62) RendererDRMPRIMEGLES: draw from the static unit quad
- [`fad900ed`](https://github.com/xbmc/xbmc/commit/fad900edda827a2108b79d91184a5c2e3a731b21) RetroPlayer: upload GLES shader preset quads only when the size changes
- [`8063cdfe`](https://github.com/xbmc/xbmc/commit/8063cdfe1f6da9c3b6214a78609693378eeb3f0d) windowing/gbm: draw the GUI composite from the static unit quad
- [`e32e7c74`](https://github.com/xbmc/xbmc/commit/e32e7c7444fd24aa237f4465aa61ffa5aec8ae80) rendering/gles: keep GUI texture quads relative to the texture rectangle
- [`f98e903e`](https://github.com/xbmc/xbmc/commit/f98e903edfd526f09c5d1a64c5148f065cc2a014) rendering/gles: multiply the GUI projection and model-view on the CPU
- [`d80e2142`](https://github.com/xbmc/xbmc/commit/d80e21428951d89a690da492d02e0966d91bf7b3) rendering/gles: skip the texture matrix for CGUITexture quads
- [`a465181c`](https://github.com/xbmc/xbmc/commit/a465181c507f03eeed96f5fe7d8ed9bc174215a5) Merge pull request #29687 from clementperon/gles-static-gui-vertices
- [`ab402f1e`](https://github.com/xbmc/xbmc/commit/ab402f1eff20294421589ae341c598487e99f567) Merge pull request #29667 from 78andyp/delete2
- [`a07b2bba`](https://github.com/xbmc/xbmc/commit/a07b2bbabdb7a07f9de0d00728962378f5b902c2) Merge pull request #29730 from sunlollyking/rumble-stop-on-detach
- [`798cbc23`](https://github.com/xbmc/xbmc/commit/798cbc2315d2e02bbca682dd911c521ea94572a2) Merge pull request #29688 from MikeSiLVO/fix-image-decode-delay
- [`915379eb`](https://github.com/xbmc/xbmc/commit/915379ebe3457da08186c779d42dcf3e247b8af4) Merge pull request #29542 from sunlollyking/gl-rotate-perspective
- [`6bac2db5`](https://github.com/xbmc/xbmc/commit/6bac2db516b44e09e29fb7553c36e3b321b082d9) Merge pull request #29576 from sunlollyking/retroplayer-shader-pass-whole-pixels
- [`616fa78b`](https://github.com/xbmc/xbmc/commit/616fa78b03c7a07ac0e713b3e8c9d3a1a01e53b0) Merge pull request #29802 from sunlollyking/slideshow-broken-picture
- [`9275c5b7`](https://github.com/xbmc/xbmc/commit/9275c5b77d0334beb18f42cb89916c2a06245dd2) Merge pull request #29803 from sunlollyking/slideshow-video-display-mode
- [`b9e69078`](https://github.com/xbmc/xbmc/commit/b9e6907849b2b91635b364e5c63f165729acc4d9) Merge pull request #29808 from sunlollyking/slideshow-hdr-video
- [`8df12d4b`](https://github.com/xbmc/xbmc/commit/8df12d4b212196d2f03e9e44a9c96c57560de9c5) Merge pull request #29815 from sunlollyking/slideshow-date-taken
- [`fc73908b`](https://github.com/xbmc/xbmc/commit/fc73908b757d475e61565b4596face92fc9f030a) Merge pull request #29814 from sunlollyking/slideshow-video-thumbnail
- [`11f50401`](https://github.com/xbmc/xbmc/commit/11f5040156551bafcfda36ee1a3c0523c995ca7f) Merge pull request #29812 from sunlollyking/slideshow-skip-broken-video

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/494721df...11f50401)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261012-11f50401-master_arm.ipk

---
## Kodi 23.0-ALPHA1 — 20261011-494721df

**Homebrew Version:** `23.26.284`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-11 10:07:24 PDT`

**Commits:** 67

### All Commits

- [`a80745bb`](https://github.com/xbmc/xbmc/commit/a80745bbc8f7f0cf94de4ae1040a660a61c8bcba) [RetroPlayer] Fix GL shader preset fallback logic when RenderUpdate fails
- [`3a7a163d`](https://github.com/xbmc/xbmc/commit/3a7a163da50351b377db1dcf063ae9957cd1d024) [RetroPlayer] Clean up GL renderers' clearing
- [`941d589d`](https://github.com/xbmc/xbmc/commit/941d589dfdedd669adcf43ce506fd75d6ee40a2b) [RetroPlayer] Use limited black for clears
- [`d55ddaea`](https://github.com/xbmc/xbmc/commit/d55ddaeafda43383a55227d934c03a2282cd1975) [RetroPlayer] Wait for FBO capture fences before deleting their textures
- [`3f885ee2`](https://github.com/xbmc/xbmc/commit/3f885ee236a1d08f05c453b2c92c1040b0b3d9eb) [RetroPlayer] Grow the framebuffer for a frame larger than reported
- [`9c0dc205`](https://github.com/xbmc/xbmc/commit/9c0dc205c523ae9807ba7d8f6fb90b7b3f79e422) Break the CAgentController reference cycle on shutdown
- [`f86e1547`](https://github.com/xbmc/xbmc/commit/f86e1547809a0895dcae9470f6710fbada2ce8a3) [Video] Fixes a crash on the GUI thread in `CStreamDetails::GetPreferredAudioStreamIndex()` while a video library list is loading.
- [`aac75aa1`](https://github.com/xbmc/xbmc/commit/aac75aa1603269c36be270c501b8d9f4c3d1be24) [addons][pvr] Show PVR settings menu hooks in add-on settings dialog
- [`98904763`](https://github.com/xbmc/xbmc/commit/989047636c175be997932f1f8a85a6033dbd2c22) [addons] Make add-ons with settings actions but no settings configurable
- [`1ee73d0f`](https://github.com/xbmc/xbmc/commit/1ee73d0ff14d14c1888ee05edef221167762dfba) [pvr] Remove client specific settings entry from PVR settings
- [`689f0476`](https://github.com/xbmc/xbmc/commit/689f0476ecefa932d9ce965799c94bad84574982) [pvr] Scope channel OSD to provider and group
- [`aa67611c`](https://github.com/xbmc/xbmc/commit/aa67611c3bd64a89bff6e2184a61529611d36b89) SaveFileState: keep a disc image's state against the image
- [`8840d876`](https://github.com/xbmc/xbmc/commit/8840d87601f8300f87dec48be811b7c897802bf8) ActiveAE: log buffer state on large audio sync errors
- [`8e6f9050`](https://github.com/xbmc/xbmc/commit/8e6f90504e2b214b51707ac26a8e0d3c825179fc) audioengine: add a Web Audio worklet sink
- [`0b1bb8d0`](https://github.com/xbmc/xbmc/commit/0b1bb8d0d21f78406020a07f7107da01ecdd9799) windowing/wasm: fix double promotion in the refresh-rate check
- [`fda52e62`](https://github.com/xbmc/xbmc/commit/fda52e62ab8b08a689f15afa57bd940c748860c2) platform/wasm: rename CWasmAudioWorkletManager::Instance() to GetInstance()
- [`7fad4f8d`](https://github.com/xbmc/xbmc/commit/7fad4f8d9180c50547421535f5c137ae58767bbe) platform/wasm: wait for the browser pipeline when draining audio
- [`bdd42c69`](https://github.com/xbmc/xbmc/commit/bdd42c6930f27e829e8d23f0df808c99eca56062) [pvr] Add channel groups node to provider view
- [`0929e56b`](https://github.com/xbmc/xbmc/commit/0929e56b09c852df85669e5c421d2a75b84b2f4d) [application] Keep the frame move guard released after Stop() (#29569)
- [`fecf9c58`](https://github.com/xbmc/xbmc/commit/fecf9c58d4574f46856cfc669f84a7afe36dd69d) Update translation files
- [`15653f05`](https://github.com/xbmc/xbmc/commit/15653f05a7de7e46139b3a8306d2796a248c0781) platform/wasm: refresh the pipeline latency before the drain wait
- [`540a4ac4`](https://github.com/xbmc/xbmc/commit/540a4ac4cd6dc695e76c2907ed1ea29268641637) Merge pull request #29690 from weblate/weblate-kodi-add-ons-skins-skin-estuary
- [`9a33d95c`](https://github.com/xbmc/xbmc/commit/9a33d95c421971367f88d8de07d94b5db300b9f0) [language][CLanguageTag] Move CLanguageTag to xbmc/language (#29655)
- [`498725fe`](https://github.com/xbmc/xbmc/commit/498725fe6e6dbdda5374a86e03268d121e62f8c2) Merge pull request #29433 from ldzhjn/pvr-osd-provider-title
- [`256fe8a1`](https://github.com/xbmc/xbmc/commit/256fe8a175bbd2ea993e426869b5ca81c5f8ad50) [AudioEngine][CAEStreamParser] Confirm a DTS core frame before taking it as the stream (#29641)
- [`d07adc93`](https://github.com/xbmc/xbmc/commit/d07adc9336d2dcf1fbb0634594370ed3fc74de34) [buildsteps][depends] Keep built depends of other revisions in a workspace cache (#29611)
- [`a2de1274`](https://github.com/xbmc/xbmc/commit/a2de12747a94ca79e929914b4fc5269385c2a203) [VideoPlayer] Keep a hidden subtitle selected when its stream is closed (#29624)
- [`02f40fc0`](https://github.com/xbmc/xbmc/commit/02f40fc0c314b09e40c19349ef0b0961f385fe10) [Announcements][CAnnouncementManager] Call announcers without holding the announcer lock (#29515)
- [`14e94add`](https://github.com/xbmc/xbmc/commit/14e94addded41219a791971f0079d72f895a430b) [Video][CVideoDatabase] List a TV show director's shows when found by search (#29601)
- [`4d2e30b6`](https://github.com/xbmc/xbmc/commit/4d2e30b6bc663e6ee21e031c667e701e1f504abf) [dialogs] Name the image choice entries once (#29528)
- [`61f590c5`](https://github.com/xbmc/xbmc/commit/61f590c5d609f56703f28bcec397c1a225eb57a6) [JSON-RPC][AudioLibrary] Keep each album's tracks together when several are added to a playlist (#29656)
- [`4c97c8c2`](https://github.com/xbmc/xbmc/commit/4c97c8c2951b2b4d7064695c6592b5d922883ff7) [media] Name a section of Kodi with a type, not a string (#29621)
- [`e75e05e1`](https://github.com/xbmc/xbmc/commit/e75e05e1374a0786679d0ab4891a4a279a8b6304) [utils] Name the common art types once (#29625)
- [`296e91df`](https://github.com/xbmc/xbmc/commit/296e91df28b04bd1fe9f0aebf23e2e0b95c03ab1) Merge pull request #29649 from ksooo/pvr-settings-menuhooks-in-addon-settings
- [`36adc12c`](https://github.com/xbmc/xbmc/commit/36adc12c8e300e6a42cf232750700980c1dc03c5) Merge pull request #29432 from ldzhjn/pvr-provider-channel-groups
- [`46928e87`](https://github.com/xbmc/xbmc/commit/46928e87cfc0744391be0a3888fe761aa368e996) Merge pull request #29588 from sunlollyking/retroplayer-grow-hw-framebuffer
- [`7c769ae8`](https://github.com/xbmc/xbmc/commit/7c769ae882637a37b31aa51710bc1a95d039a613) Merge pull request #29553 from clementperon/upstream/07-audio
- [`48728880`](https://github.com/xbmc/xbmc/commit/48728880755ffcad4ed543d9fa46e61ef0ca7b4b) Merge pull request #29440 from 78andyp/race
- [`f36b45d8`](https://github.com/xbmc/xbmc/commit/f36b45d87061be5a181687e72403dc03e564319e) Merge pull request #29589 from popcornmix/discresume
- [`612d11b5`](https://github.com/xbmc/xbmc/commit/612d11b598100f550b78e10f9c9c66b6547573a0) Merge pull request #29607 from popcornmix/peripheral-shutdown-cycle
- [`eab05410`](https://github.com/xbmc/xbmc/commit/eab05410a50ce77646330e708e7e65623c50c95c) [Peripherals] Power off controllers on quit (#29686)
- [`73029888`](https://github.com/xbmc/xbmc/commit/730298886ecff81436bd7516d47d6e7fb81a3950) [UPnP][CUPnPPlayer] Apply the deadline set on a renderer action (#29155)
- [`0a9c932b`](https://github.com/xbmc/xbmc/commit/0a9c932b61ca5abfa7156510cb7a5759715dd642) [utils] Remove utility members that only the unit tests call (#29605)
- [`63f24baa`](https://github.com/xbmc/xbmc/commit/63f24baaeb932b5492dbd61fc92913d98cab3dff) [VideoPlayer][CDebugRenderer] Build the debug overlay's subtitle options with the main overlay's code (#29616)
- [`da968f69`](https://github.com/xbmc/xbmc/commit/da968f69fbfa91ad5e677bd949149842b506b252) [Database] Never hand a deleted library item's id to another item (#29622)
- [`507005ce`](https://github.com/xbmc/xbmc/commit/507005cec3ac5769cf83c7b15bae29f51852d475) [URIUtils] Decode a path's escapes without turning a '+' into a space (#29630)
- [`0dd455fa`](https://github.com/xbmc/xbmc/commit/0dd455faf83706c702756d35bc8eab24d140df94) [windowing][RESOLUTION_INFO] Give a declared aspect the pixel ratio that produces it (#29657)
- [`34d4e422`](https://github.com/xbmc/xbmc/commit/34d4e42203535312bbd40d6413473c4edb7eccec) [addons][CSkinInfo] Ignore a layout aspect that is not a positive ratio (#29658)
- [`376e3b71`](https://github.com/xbmc/xbmc/commit/376e3b71d194b892d5232d6072ff03d4b9bb93e5) [network][HTTPRequestHandlerUtils] Report the scheme a request arrived by, not always http (#29659)
- [`6761830e`](https://github.com/xbmc/xbmc/commit/6761830e72f4cd5c9f8a9b6dfb587f374c9fdbd6) [JSON-RPC][VideoLibrary] Apply a TV show's playcount and lastplayed to its episodes (#29660)
- [`be900708`](https://github.com/xbmc/xbmc/commit/be900708a1ef6828cdce26832bf63c68014694e0) [JSON-RPC][AudioLibrary] Report a failed artist query as an internal error, not a missing artist (#29661)
- [`13d27c4c`](https://github.com/xbmc/xbmc/commit/13d27c4c067786bdf9958f386942890b26ab494a) [LocalizeStrings] Remove the fallback to language folders named after the language (#29662)
- [`7cbb5041`](https://github.com/xbmc/xbmc/commit/7cbb5041d5cb754e514649c078225a2371c5abc6) [Video][Database] Remove the artist id GetMusicVideoAlbumsNav is never given (#29671)
- [`1e176c94`](https://github.com/xbmc/xbmc/commit/1e176c94b1c264d5faf8ef8a6effffa61d47b202) [VFS][VFSEntry] Read the preformatted-label flag from the property's value (#29676)
- [`3bd7db75`](https://github.com/xbmc/xbmc/commit/3bd7db755745d75eebc01ac5b42bd011ffc96af0) [utils][Digest] Match a digest type name regardless of case (#29678)
- [`1b0a9550`](https://github.com/xbmc/xbmc/commit/1b0a95503c244d1cbdfa31d39023e5e0dbff8c22) [input][CInputManager] Let every listed builtin run past the screensaver (#29679)
- [`4507628f`](https://github.com/xbmc/xbmc/commit/4507628f05624d58f3e62c5d10648480153904dd) [peripherals][CPeripherals] Skip a mapping setting without a key (#29680)
- [`fc421a09`](https://github.com/xbmc/xbmc/commit/fc421a094b06aa208a9e52dee5a49145a109265b) [Video][CVideoInfoTag] Restart the cast at an NFO actor marked clear="true" (#29681)
- [`fa8ea0b1`](https://github.com/xbmc/xbmc/commit/fa8ea0b14af0a853c9b22f7ec8b2f42304828d47) [windowing][X11] Take the GLES pbuffer fallback from --gl-interface (#29683)
- [`ff7678f6`](https://github.com/xbmc/xbmc/commit/ff7678f69a50f86e47376b3785df5352a4c82f3a) [dialogs] Own the colour picker's list and the progress bar's handles (#29700)
- [`6b390285`](https://github.com/xbmc/xbmc/commit/6b39028587d87154f4f375ec7511ecd26e8ae4cc) [guilib][test] Share the GUI tests' stub render system, window system and GUI (#29702)
- [`e624fb08`](https://github.com/xbmc/xbmc/commit/e624fb080c632c5f411f91e6ddf773c2320da04a) [utils][CLabelFormatter] Label a whole list in one place (#29703)
- [`f41d8066`](https://github.com/xbmc/xbmc/commit/f41d80660b036360d87de4647507c4d4c73029cf) [utils][LabelFormatter] Read a rating from a file name as a number (#29677)
- [`0939c0f8`](https://github.com/xbmc/xbmc/commit/0939c0f8244885540181cf47e7fdaee39fc337ad) [peripherals][CPeripherals] Read the order of a mapping setting (#29682)
- [`a7dd0c7d`](https://github.com/xbmc/xbmc/commit/a7dd0c7d247032776e90e6fc73337208d13b0c52) [settings][SettingLevel] Name the setting levels in the settings code (#29704)
- [`6f8320d5`](https://github.com/xbmc/xbmc/commit/6f8320d51f2b4de6a1c20997f87f46ad6247829a) Merge pull request #29567 from KOPRajs/retroplayer-gl-cleanup
- [`494721df`](https://github.com/xbmc/xbmc/commit/494721df6fde78d1188ae110b6688d2a8324ba44) [RetroPlayer][test] Bring the test renderers in line with the GL clearing cleanup (#29777)

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/60c2c516...494721df)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261011-494721df-master_arm.ipk

---
## Kodi 23.0-ALPHA1 — 20261008-60c2c516

**Homebrew Version:** `23.26.281`

**Official webOS Package Version:** `22.90.701`

**Feed Updated:** `2026-10-09 19:45:38 PDT`

**Commits:** 110

### All Commits

- [`c49438e9`](https://github.com/xbmc/xbmc/commit/c49438e9f81d1d6a1e5fa997f86eb7c94c12fe89) windowing/gbm: fix reentrant Unregister() UB in OnResetDisplay()
- [`d072578a`](https://github.com/xbmc/xbmc/commit/d072578ac7a0e71b66f0c00d2cbd3aeecc205721) [filesystem] Avoid replaying seeks at FileCache EOF
- [`19d3508c`](https://github.com/xbmc/xbmc/commit/19d3508c35a3c5d0d88b8345209c85186d1ea785) FFmpegImage: Read the EXIF orientation from the display matrix
- [`02b3e356`](https://github.com/xbmc/xbmc/commit/02b3e3560bcb845a8a0636db9fc80f76ea98a8aa) VideoPlayer: build the GLES renderers for wasm
- [`272811c3`](https://github.com/xbmc/xbmc/commit/272811c33b91c88e013eeee496152385bd4be991) windowing/wasm: add the WebGL 2 windowing backend
- [`c9d4746f`](https://github.com/xbmc/xbmc/commit/c9d4746f3e37725f0ff694e13122c6e50134b174) windowing/wasm: sync the reference clock to the display
- [`225fa79f`](https://github.com/xbmc/xbmc/commit/225fa79f001fad0b36468dd2590708cfe76a8aa7) windowing/wasm: keep the screen awake with a wake lock
- [`27d1e568`](https://github.com/xbmc/xbmc/commit/27d1e568f7dffdcd3dd1b4ea078bc9ae1af2045e) wasm: persist the user profile to IndexedDB
- [`4b03f9df`](https://github.com/xbmc/xbmc/commit/4b03f9df45ad7c6c1bde6ff9310cd81fcd1151c9) windowing/wasm: paste from the browser clipboard
- [`877c82ac`](https://github.com/xbmc/xbmc/commit/877c82ac5b391308a3d2f575a178d542f9e89afe) windowing/wasm: support the browser's native keyboard
- [`f29e0537`](https://github.com/xbmc/xbmc/commit/f29e053739b1f7e5c0b8a75bed913f8ba98287cb) tools/wasm: route cross-origin requests through the dev proxy
- [`99f224f1`](https://github.com/xbmc/xbmc/commit/99f224f194f39b45cfed4822030c7e4822bbbee4) windowing/wasm: translate mouse wheel input
- [`105e0a9e`](https://github.com/xbmc/xbmc/commit/105e0a9ec2b977f38114258ee5c5426ee826174f) [filesystem] Add tests for replay seek at EOF
- [`23b298b1`](https://github.com/xbmc/xbmc/commit/23b298b1c0ee496c6d3cc35660bc6d63000783e1) changed: let a resource add-on say what it publishes rather than what is allowed
- [`7dcf13cc`](https://github.com/xbmc/xbmc/commit/7dcf13cc540c83ecbc72cf6f7f5b434e5b418b93) [video] Add "Refresh all content" to the video source context menu
- [`65b551ed`](https://github.com/xbmc/xbmc/commit/65b551eddb17241b2c587602a78411b8d37af215) [video] Don't save the default icon as art when refreshing
- [`33dbdf30`](https://github.com/xbmc/xbmc/commit/33dbdf3053ecdb72c5c5414d87f649ba0a4b71c2) [video] Refresh a bluray movie from its disc
- [`c0700490`](https://github.com/xbmc/xbmc/commit/c07004904252143abb94fb6a8bc83c1d99f20637) [video] Keep a disc's watched state when a refresh finds one playlist
- [`38f56084`](https://github.com/xbmc/xbmc/commit/38f5608455c4ea456279ca46b342584b42a4e72b) [video] Re-read the stream details of the versions kept by a refresh
- [`59503f8f`](https://github.com/xbmc/xbmc/commit/59503f8fb0d7feb34e559ffc21bc254eb1691114) windowing/wasm: give the reference clock the measured refresh rate
- [`5ed979a1`](https://github.com/xbmc/xbmc/commit/5ed979a1cbd2320fd7fb438b99c42df3d4656d65) [RetroPlayer] Restore the audio delay after a pause
- [`b97434d1`](https://github.com/xbmc/xbmc/commit/b97434d1e8418005c8f66dfcd658484ffe01356b) [RetroPlayer] Give every shader pass the preset's parameters
- [`b307a426`](https://github.com/xbmc/xbmc/commit/b307a4264cfd663233e4839b43d81c0ce6b71a0f) Games: Add RetroAchievements hardcore mode, hidden until approved
- [`5e2fb3d5`](https://github.com/xbmc/xbmc/commit/5e2fb3d5cfb84d48786e2eb015a98250503c3a39) [Windows] Bump Python to 3.14.8 / OpenSSL to 3.5.9 / expat to 2.8.5
- [`1a13e491`](https://github.com/xbmc/xbmc/commit/1a13e491f844ae92b199093153e918e0223a1e95) [input] Play the GUI sound for a controller's actions too
- [`b519ee30`](https://github.com/xbmc/xbmc/commit/b519ee30144a20cb191e90d4d38f8c212b9a1554) windowing/wasm: follow refresh-rate changes in the reference clock
- [`182dff13`](https://github.com/xbmc/xbmc/commit/182dff13fb85bd85cf5b0189fbe8f4c21f46b28f) [RetroPlayer] Remove leftover regex includes from the shader presets
- [`99bb9d91`](https://github.com/xbmc/xbmc/commit/99bb9d910f602daf294670eee877a4b2e4f12601) [RetroPlayer] Only show achievement indicators over the game
- [`37499d4a`](https://github.com/xbmc/xbmc/commit/37499d4ac513e8103040167f13090ea20e00f37d) VideoPlayer: detect a 3D file name from the file, not the library URL
- [`218b0c0d`](https://github.com/xbmc/xbmc/commit/218b0c0d7a8314e1f26269f981c242d0dc7600ac) changed: report an RDS country as a CTerritory
- [`b4b4b97c`](https://github.com/xbmc/xbmc/commit/b4b4b97cbb2cee7427524800178ec92c3e541cdc) MediaSettings: keep the default stereo invert across a restart
- [`e1d9aef9`](https://github.com/xbmc/xbmc/commit/e1d9aef96cb4bc468e2b5772198ae7ab1f2ca86d) fixed: resolve no resource path through a parent segment, and build with GCC
- [`fe7c69a2`](https://github.com/xbmc/xbmc/commit/fe7c69a29e0ea3c2013daa1c2eff4eeb19841a6b) fixed: tell a UPnP renderer to stop once, and close even when it does not answer
- [`c6c63772`](https://github.com/xbmc/xbmc/commit/c6c63772e611eb07986f2474fa3d2035bbad0394) [Estuary] Add colour icons to media flags
- [`be3cc854`](https://github.com/xbmc/xbmc/commit/be3cc8543be4cd915b7e167ac0d71df607eb1045) Merge pull request #29568 from Hitcher/colourise_media_flags
- [`e3f7fdfe`](https://github.com/xbmc/xbmc/commit/e3f7fdfec44c698fb76322749c2d184560918ccf) Merge pull request #29290 from malard/fix-upnp-player-repeated-stop
- [`ef9eb6b4`](https://github.com/xbmc/xbmc/commit/ef9eb6b40faef1f5e1733be06e836eaae61d4418) Merge pull request #29574 from thexai/python-openssl-expat
- [`77e7e482`](https://github.com/xbmc/xbmc/commit/77e7e4821c1ed3cebfdc3e7b40a8db4d17e51248) fixed: compile the content bar detector where ptrdiff_t is 32 bits
- [`bcacd8ff`](https://github.com/xbmc/xbmc/commit/bcacd8ffb86d67d61314c37c2b99c4bf35e07776) [Windows] Fix rare crash related to audio initialization with incomplete format
- [`7e3d87bf`](https://github.com/xbmc/xbmc/commit/7e3d87bf0ff7c8acaa7a7eda24df0538e57f48ce) Merge pull request #29441 from smp79/28915-follow-up
- [`c5bd04f5`](https://github.com/xbmc/xbmc/commit/c5bd04f5ec3bf4e0c3fa974ce89c54ced2887987) Merge pull request #29609 from malard/fix-content-bar-32bit
- [`857262ad`](https://github.com/xbmc/xbmc/commit/857262add6c413050472303d3824deb5ba619d33) [Video][Database] Fix stale path entries surviving a library clean.
- [`5e899dc9`](https://github.com/xbmc/xbmc/commit/5e899dc9aecd1c420bf881abe56bd3331397af1c) [Video][Database] Fix a library clean keeping the dead sub paths of a live source.
- [`45b1f26c`](https://github.com/xbmc/xbmc/commit/45b1f26cce17215adf5825788634cea88e50a605) [Video][Database] Fix a library clean leaving the path entry of a removed disc or archive behind.
- [`0d2c65e2`](https://github.com/xbmc/xbmc/commit/0d2c65e2a7dad602d01d68c5cfb494ad1c100ba4) [Video][VideoInfoScanner] Fix incorrect logging of 'missing' directories that have been collapsed by stacking.
- [`e33bd68d`](https://github.com/xbmc/xbmc/commit/e33bd68db541800778084f37dea560a06b1e1b00) [Video][Database] Remove files that have gone.
- [`b3b63b66`](https://github.com/xbmc/xbmc/commit/b3b63b66e05cb2d9886c4b4c28e5c55a4d6c6885) [Video][Database] Remove redundant deletes from EraseAllForPath.
- [`46bc86d3`](https://github.com/xbmc/xbmc/commit/46bc86d3de37f6965c90c6a852e47ea077e2a0d4) [Video] Remove unused CSetInfoTag::Copy()
- [`36d2b859`](https://github.com/xbmc/xbmc/commit/36d2b859321cc198e2ab5912e6344c300cd50dc2) [Video] Add <sorttitle> to SetInfoTag and read it from set.nfo
- [`a715dc5b`](https://github.com/xbmc/xbmc/commit/a715dc5b78b075ce9f3ed898cf350d16be67d825) [Video][Database] Store the movie set sort title
- [`5684f76a`](https://github.com/xbmc/xbmc/commit/5684f76afab429287efd89512f2fe439265e7335) [Video] Allow movie sets to be sorted by sort title
- [`d5e2a5ad`](https://github.com/xbmc/xbmc/commit/d5e2a5ad0d4abf072d847d85a87ab8e880dc00bc) [JSON-RPC] Add sorttitle to movie set details
- [`09855bfd`](https://github.com/xbmc/xbmc/commit/09855bfd76fdf3505420d2d4bd267ae49fc9ba43) [Windows] SMB: don't reconnect when a path doesn't exist.
- [`b5fc9a1f`](https://github.com/xbmc/xbmc/commit/b5fc9a1fdd5a6fd646ddf3c1943fd96c18bc5ee4) [Windows] SMB: don't reconnect for a file in a missing folder.
- [`e7c9e83c`](https://github.com/xbmc/xbmc/commit/e7c9e83c86052f446de3025c3e3c59d5d6b43de8) [Windows] SMB: use the existing session on a credential conflict.
- [`7e87e475`](https://github.com/xbmc/xbmc/commit/7e87e4754e3b18ebde138b3d4f63c888f0a426f6) [Windows] WS-Discovery: lock server list access.
- [`45912708`](https://github.com/xbmc/xbmc/commit/45912708dcc2c2c96d39f138edd42ab3fb0cd569) [Windows] WS-Discovery: don't resolve server names over multicast.
- [`36e1a887`](https://github.com/xbmc/xbmc/commit/36e1a8875e637bc88eb9ef255b36cae8a7611172) [Windows] WS-Discovery: track servers by endpoint.
- [`725f02b1`](https://github.com/xbmc/xbmc/commit/725f02b1c410d80dcc5c782a27effda08abd7458) [Windows] WS-Discovery: use the computer name the server announces.
- [`9396996f`](https://github.com/xbmc/xbmc/commit/9396996f85258772de6860d4e96647c9be334571) [Windows] WS-Discovery: resolve server names in parallel and cache them.
- [`70d092ef`](https://github.com/xbmc/xbmc/commit/70d092efdff690398f8636fc00fae03e29762b23) [Windows] SMB: list servers with the same name by IP.
- [`de4e353c`](https://github.com/xbmc/xbmc/commit/de4e353c22bcfd9efd3c2504a37dbf446b05a0da) [Windows] WS-Discovery: log name lookup time.
- [`994aecad`](https://github.com/xbmc/xbmc/commit/994aecadc7d7c5dd3f1248ba31309fc87fdef8e6) [passwordManager] Look up credentials by host name in any case.
- [`dffbeb86`](https://github.com/xbmc/xbmc/commit/dffbeb865ee2e686e0dd70e3ba75ce41f2308f02) [windowing] Allow cropped content to match whitelist modes
- [`6907645f`](https://github.com/xbmc/xbmc/commit/6907645f3f71df338c99c94f2ac98a52d64497cb) [Video][Database] Fix movie search results matched by original title.
- [`1204b5bc`](https://github.com/xbmc/xbmc/commit/1204b5bc486c6efd7cd60ddba1e0770b1d22dedb) Merge pull request #29496 from olympia/videodb/search-show-original-title
- [`048936cc`](https://github.com/xbmc/xbmc/commit/048936ccb387e5224731b0b242cf95d7bb6c504b) Merge pull request #28953 from 78andyp/sets
- [`391fb9d4`](https://github.com/xbmc/xbmc/commit/391fb9d406954a67530b63e01f8574f150a40465) Merge pull request #29454 from 78andyp/smb
- [`d3a80ccd`](https://github.com/xbmc/xbmc/commit/d3a80ccde220ca7e220d4f5d21c96f70e8379a7f) Merge pull request #29411 from 78andyp/delete
- [`8b50843a`](https://github.com/xbmc/xbmc/commit/8b50843a840d4121b4863fb1e35a92db7403fd41) [Video][Bluray] Improve handling of heuristic v. project differences.
- [`4c8954df`](https://github.com/xbmc/xbmc/commit/4c8954dfd0bb5df1da77b8d98af489f78c8b10cb) [Video][Bluray] Add advanced setting to disable authoring project parsing.
- [`8141618d`](https://github.com/xbmc/xbmc/commit/8141618db7fd21ab2ee8ba60a2ef81bcc699c7fe) [Video][Bluray] Don't reject a playlist whose extension data is invalid.
- [`3ca52af4`](https://github.com/xbmc/xbmc/commit/3ca52af4ea71f43e14b0f3aabb56eadcf6889c49) [PVR][RDS] Address review of the RDS country lookup
- [`421b0542`](https://github.com/xbmc/xbmc/commit/421b0542979e4a6cc227f436f2cb519a4ed1e8f8) Merge pull request #29455 from 78andyp/parse
- [`6ce46324`](https://github.com/xbmc/xbmc/commit/6ce46324b9df0bfe993e4e1b28e1327820615a25) Merge pull request #29577 from thexai/fix-audio-crash
- [`c8c7d26d`](https://github.com/xbmc/xbmc/commit/c8c7d26df32c7a02cccb850e4082f4573d6038f4) Merge pull request #29584 from popcornmix/stereopath
- [`c25d7246`](https://github.com/xbmc/xbmc/commit/c25d72466b3cea5988578ae557321beeb8874ca5) Merge pull request #29586 from popcornmix/stereoinvert
- [`446f818c`](https://github.com/xbmc/xbmc/commit/446f818c6ae25232c2dd9a5b8d5f598339a523f5) [RetroPlayer] Keep the shader frame count in medium precision on GLES
- [`6c040bd6`](https://github.com/xbmc/xbmc/commit/6c040bd6713f7f37c6b7a65ca11e31408e0be03c) [VideoPlayer] Audio ID3: Update the displayed artist with each tag
- [`f6f3162c`](https://github.com/xbmc/xbmc/commit/f6f3162c4428d755c394e5c6dc602320d241ed3d) [VideoPlayer] Audio ID3: Show attached pictures as thumb
- [`ca711de8`](https://github.com/xbmc/xbmc/commit/ca711de86e1d5fb97a1fde7d6f94546bca3234f0) Merge pull request #29565 from malard/rds-country-territory
- [`6f72492c`](https://github.com/xbmc/xbmc/commit/6f72492c71654d9652a66a28d6fcf21b6ba65a7f) Merge pull request #29512 from malard/resource-addons-publish
- [`b2b55564`](https://github.com/xbmc/xbmc/commit/b2b5556480daec3a7a40838a4e3253171fb4b68b) Merge pull request #29448 from kel-mo/ffmpegimage-displaymatrix
- [`8952e9e8`](https://github.com/xbmc/xbmc/commit/8952e9e8897c4d4809cb035cf83abf3e06cf03f1) Merge pull request #29497 from chewitt/whitelist-crop-tolerance
- [`7d76d07d`](https://github.com/xbmc/xbmc/commit/7d76d07da647b46716f1707ad03098be24079d7f) Merge pull request #29562 from sunlollyking/retroplayer-shader-pass-parameters
- [`969a7a25`](https://github.com/xbmc/xbmc/commit/969a7a2539342e45effbdc28a6586e84d0011ec0) Merge pull request #29452 from garbear/fix-smb-seek
- [`31e3167b`](https://github.com/xbmc/xbmc/commit/31e3167bb0339c3ad8a1ede72662fb3b883c5c45) Merge pull request #29575 from sunlollyking/game-indicators-over-game
- [`ac7a9792`](https://github.com/xbmc/xbmc/commit/ac7a979233a711c749fce915e25d362dac91ed5e) Merge pull request #29559 from sunlollyking/retroplayer-audio-resume-delay
- [`2cf5e3e0`](https://github.com/xbmc/xbmc/commit/2cf5e3e05bd1642782e2d6f540f333eb793d4470) Merge pull request #29504 from sunlollyking/controller-navigation-sounds
- [`14a6bd18`](https://github.com/xbmc/xbmc/commit/14a6bd1854307e0736b3568b2e6a50304c78ad30) Merge pull request #29467 from sunlollyking/hardcore-upstream
- [`bbecced0`](https://github.com/xbmc/xbmc/commit/bbecced088f85b0a1e679f3827efa9d703ae5406) Merge pull request #29648 from ksooo/audio-id3-fixes
- [`49459725`](https://github.com/xbmc/xbmc/commit/49459725a5834304952dfcd36743090c765848cf) Merge pull request #29259 from clementperon/upstream/06-windowing
- [`58b66c7e`](https://github.com/xbmc/xbmc/commit/58b66c7ee7600d5761ef0e56ec8881e8c264ae55) [depends][python] build a statically linkable CPython for wasm
- [`ad18aaef`](https://github.com/xbmc/xbmc/commit/ad18aaefa9dc58f26126a41366196b7438fa9a02) [wasm] run the Python interpreter from a statically linked CPython
- [`0b336247`](https://github.com/xbmc/xbmc/commit/0b33624753a6afc3b1c432235c6d77001036c519) [wasm] re-glob the Python stdlib when the depends change
- [`640d8279`](https://github.com/xbmc/xbmc/commit/640d827976fd0b1009fe90162d58ed6055553588) Merge pull request #29169 from clementperon/upstream/wasm-python
- [`014071ee`](https://github.com/xbmc/xbmc/commit/014071ee44affd8370e904cee48a919c0d17138c) Merge pull request #29471 from 78andyp/library
- [`86c38b02`](https://github.com/xbmc/xbmc/commit/86c38b0294a8ed840681489e5bfa622cd363faec) [VideoPlayer][CBaseRenderer] Read the 4:3 stretch setting once in SetViewMode (#29644)
- [`30e80b94`](https://github.com/xbmc/xbmc/commit/30e80b9441cd9df023b1fd84a1b9b9186b9f6548) [GUIWindowFullScreen] Draw the picture through one function (#29643)
- [`e178c1d5`](https://github.com/xbmc/xbmc/commit/e178c1d5c0145454c3acc45d24694ae7d3dffba2) [PVR][CPVRChannel] Let a channel keep its own logo when the airing programme has artwork (#29634)
- [`f89ea8eb`](https://github.com/xbmc/xbmc/commit/f89ea8eb34b9bc51b090c54b6a632f506dbf193f) [JSON-RPC] Register the methods before anything can call them (#29623)
- [`76efd7ec`](https://github.com/xbmc/xbmc/commit/76efd7eccd095c813ed74031d3fb70ce55baa0bc) [JSON-RPC] Don't open a PVR item through Player.Open before PVR has started (#29627)
- [`133d6e3e`](https://github.com/xbmc/xbmc/commit/133d6e3eb129f27f528151810a448310d242d9ee) [playlists][CPlayListPLS] Name a playlist without a name entry after its file (#29642)
- [`198575f6`](https://github.com/xbmc/xbmc/commit/198575f69fb3331244ea95e33036edd9308a6e99) [media] Remove the media type names nothing asks for (#29631)
- [`20606fe1`](https://github.com/xbmc/xbmc/commit/20606fe176bdc463a14a89c3da7a4c59d0fd9899) [Database] Keep the art table code the video and music databases share in CDatabase (#29635)
- [`1a2e269d`](https://github.com/xbmc/xbmc/commit/1a2e269d2ad236e2d14c6d7b6146c93dde411a09) [Video] Name the videodb:// node paths once (#29599)
- [`db76a0b8`](https://github.com/xbmc/xbmc/commit/db76a0b832c0f4d3a146ad348b64382bc222e3df) [addons] Name the addons:// node paths once (#29637)
- [`c1a0f9cb`](https://github.com/xbmc/xbmc/commit/c1a0f9cb5daf0ebb7c8d0416c52043b477d53fac) [Music] Name the musicdb:// node paths once (#29619)
- [`2f561616`](https://github.com/xbmc/xbmc/commit/2f561616a77fc5c7f1715094409a064b0acb2336) [FileItemList] Name a list's content once (#29620)
- [`60c2c516`](https://github.com/xbmc/xbmc/commit/60c2c516981b531e44d99c6009867d3458faf22d) [FileItem] Name the list item property keys shared between files (#29626)

[Full Kodi GitHub comparison](https://github.com/xbmc/xbmc/compare/d1cecd8a...60c2c516)

Official Nightly Source: https://mirrors.kodi.tv/nightlies/webos/master/org.xbmc.kodi_20261008-60c2c516-master_arm.ipk

---
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
