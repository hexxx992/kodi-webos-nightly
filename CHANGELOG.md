# Kodi webOS Nightly Changelog

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
