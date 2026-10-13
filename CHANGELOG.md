# Kodi webOS Nightly Changelog

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
