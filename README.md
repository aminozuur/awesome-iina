# Awesome IINA

A curated list of awesome [IINA](https://github.com/iina/iina) plugins, browser extensions, tools and resources.

🌐 Also available as a website: <https://cxwx.github.io/awesome-iina/>

English | [简体中文](README.zh-CN.md) (community translation — may lag behind this page)

[IINA](https://iina.io) is the modern video player for macOS. Built on [mpv](https://mpv.io), written in Swift, with native macOS design, Picture-in-Picture, and a JavaScript plugin system.

## Contents

- [Official Resources](#official-resources)
- [Install](#install)
- [Plugins](#plugins)
  - [Official Plugins](#official-plugins)
  - [Media Servers & Streaming](#media-servers--streaming)
  - [Subtitles & Captions](#subtitles--captions)
  - [Playback & Control](#playback--control)
  - [Video & Audio Processing](#video--audio-processing)
  - [Playlists & Library](#playlists--library)
  - [Danmaku](#danmaku)
  - [Language Learning](#language-learning)
  - [Tracking & Sync](#tracking--sync)
- [Browser Extensions](#browser-extensions)
- [Launcher Integrations](#launcher-integrations)
- [Tools & Scripts](#tools--scripts)
- [Forks](#forks)
- [Plugin Development](#plugin-development)
- [Community & Resources](#community--resources)
- [Contribute](#contribute)

## Official Resources

- [iina.io](https://iina.io) — Official website.
- [iina/iina](https://github.com/iina/iina) — Source code of IINA.
- [Plugin Center](https://iina.io/plugins/) — Official curated plugin directory, installed directly from IINA's plugin manager.
- [docs.iina.io](https://docs.iina.io/) — Official plugin API documentation.
- [GitHub Discussions](https://github.com/iina/iina/discussions) — Q&A, feature ideas and release feedback.
- [GitHub Releases](https://github.com/iina/iina/releases) — Official release notes.
- [iina-cli](https://github.com/iina/iina/tree/master/iina-cli) — Bundled command-line tool: open media from the terminal, attach to a running instance and pass through mpv options.
- [Crowdin](https://crowdin.com/project/iina) — Help translate IINA.

## Install

- [Download](https://iina.io/download/) the latest release from the official website or [GitHub Releases](https://github.com/iina/iina/releases).
- Via Homebrew:

```bash
brew install --cask iina
```

## Plugins

Plugins are written in JavaScript, packaged as `.iinaplgz`, and installed from IINA's settings → Plugins (either from the Plugin Center or "Install from GitHub" with an `owner/repo` string).

### Official Plugins

- [iina/plugin-opensub](https://github.com/iina/plugin-opensub) — Search and download subtitles from opensubtitles.com.
- [iina/plugin-more-seeking](https://github.com/iina/plugin-more-seeking) — Add more seeking options.
- [iina/plugin-online-media](https://github.com/iina/plugin-online-media) — Play online videos via yt-dlp, with on-the-fly resolution switching.
- [iina/plugin-userscript](https://github.com/iina/plugin-userscript) — Load userscripts in IINA.

### Media Servers & Streaming

- [ada-bee/jellyfin-iina](https://github.com/ada-bee/jellyfin-iina) — Browse and watch content from your Jellyfin server.
- [ada-bee/youtube-iina](https://github.com/ada-bee/youtube-iina) — Browse and watch YouTube videos in a sidebar.
- [Arnav12S/iina-contentplay](https://github.com/Arnav12S/iina-contentplay) — Search movies/series, resolve Real-Debrid streams via Stremio, then play a whole season as a playlist.
- [DTTerastar/iina-plugin-channels](https://github.com/DTTerastar/iina-plugin-channels) — IPTV channel browser: M3U playlists with search, groups and an XMLTV now/next guide.
- [mhajder/iina-jellyfin](https://github.com/mhajder/iina-jellyfin) — Jellyfin media browser sidebar with automatic subtitle downloading.
- [ozykhan/iina-airplay](https://github.com/ozykhan/iina-airplay) — Cast the current file to an Apple TV over AirPlay; IINA stays the remote.
- [qydxyx/iina-webdav](https://github.com/qydxyx/iina-webdav) — Connect to a WebDAV server, browse media, and add files or folders to the playlist.

### Subtitles & Captions

- [bbeny123/iina-save-subs-with-delay](https://github.com/bbeny123/iina-save-subs-with-delay) — Save subtitles with the current delay baked in.
- [Robpol86/iina-file-name-search](https://github.com/Robpol86/iina-file-name-search) — Search the currently playing file's name on a configurable website.
- [isparkyou-github/iina-realtime-speech-translator](https://github.com/isparkyou-github/iina-realtime-speech-translator) — Real-time speech transcription and translation.
- [janwee-sha/SubTandem](https://github.com/janwee-sha/SubTandem) — Real-time AI-powered bilingual subtitle translation.
- [wilbeibi/iina-plugin-assrt](https://github.com/wilbeibi/iina-plugin-assrt) — Search and auto-download Chinese subtitles from assrt.net (伪射手), with alass timing correction.
- [yuxiqian/whisperina](https://github.com/yuxiqian/whisperina) — Generate subtitles locally with OpenAI Whisper models.

### Playback & Control

- [alexkuang0/iina-key-binding-youtube](https://github.com/alexkuang0/iina-key-binding-youtube) — Key bindings modeled on YouTube's keyboard shortcuts.
- [aminozuur/iina-thumbnails](https://github.com/aminozuur/iina-thumbnails) — Clickable thumbnails for each video.
- [bbeny123/iina-jump-to-frame](https://github.com/bbeny123/iina-jump-to-frame) — Frame-accurate navigation by frame number.
- [D0CA/iina-cinemode](https://github.com/D0CA/iina-cinemode) — Fullscreen pause overlay, skip intro, and an optional Stremio next-episode shortcut.
- [glechic/iina-bilingual-audio](https://github.com/glechic/iina-bilingual-audio) — Play two audio tracks with left/right channel separation for bilingual viewing.
- [leo-mathurin/iina-nightshift-fs](https://github.com/leo-mathurin/iina-nightshift-fs) — Disable macOS Night Shift while in fullscreen.
- [nastarandarjani/iina-pip-toggle](https://github.com/nastarandarjani/iina-pip-toggle) — Toggle Picture-in-Picture to fullscreen.
- [pangziqiang/iina-auto-skip](https://github.com/pangziqiang/iina-auto-skip) — Automatically skip intro and outro sections with a drag-to-set overlay.
- [pparanoiidd/iina-skip-intro](https://github.com/pparanoiidd/iina-skip-intro) — Detect and skip intros, recaps and credits.
- [Tommy12356F/iina-hold-to-speed](https://github.com/Tommy12356F/iina-hold-to-speed) — Hold Space to play at 2× speed, just like YouTube.
- [treehog2/iina-absave-plugin](https://github.com/treehog2/iina-absave-plugin) — Save AB loops.
- [Zain-Imam/iina-episode-info](https://github.com/Zain-Imam/iina-episode-info) — TMDB episode/movie info on pause, with built-in subtitle search.

### Video & Audio Processing

- [5thDimensionalVader/recorder-iina](https://github.com/5thDimensionalVader/recorder-iina) — Clip a video using ffmpeg.
- [bbeny123/iina-hdr-screenshot](https://github.com/bbeny123/iina-hdr-screenshot) — Capture HDR screenshots using ffmpeg.
- [Fhlisherman/iina-video-upscaler](https://github.com/Fhlisherman/iina-video-upscaler) — GPU-accelerated upscaling.
- [Gabe-LS/iina-audio-normalize](https://github.com/Gabe-LS/iina-audio-normalize) — Automatic audio normalization (peak and EBU R128 loudness modes).
- [karthisnk/multi-cutter-iina](https://github.com/karthisnk/multi-cutter-iina) — Cut multiple clips with ffmpeg, with batch clipping, vertical clips, format selection and preview.
- [lenadweb/iina-plugin-keystone](https://github.com/lenadweb/iina-plugin-keystone) — Vertical/horizontal keystone correction for projectors, adjusted live.
- [yorkyang2333/iina-AnimeEnhancer](https://github.com/yorkyang2333/iina-AnimeEnhancer) — Real-time anime upscaling via Anime4K and AnimeJaNai shaders, controlled from a sidebar tab.
- [fetzu/iina-plugin-vr2d](https://github.com/fetzu/iina-plugin-vr2d) — Watch 3D VR videos (180°/360°, SBS/OU, equirectangular or fisheye) as a flat 2D image you can pan and zoom.

### Playlists & Library

- [CatCodeDanix/iina-playlist-pro](https://github.com/CatCodeDanix/iina-playlist-pro) — Manage local and online playlists.
- [dotWee/iina-playlist-sortings](https://github.com/dotWee/iina-playlist-sortings) — Extra playlist sorting options.
- [HowDidTheCatGetSoFat/iina-detached-playlist](https://github.com/HowDidTheCatGetSoFat/iina-detached-playlist) — Show the playlist in its own floating window.
- [icsarisakal/iina-playlist-searchbox](https://github.com/icsarisakal/iina-playlist-searchbox) — Search the current playlist by song title and artist.
- [qktechies/iina-plugin-file-viewer](https://github.com/qktechies/iina-plugin-file-viewer) — Bookmark folders, browse directory structures, and play files without leaving IINA.
- [roboloop/media-manager](https://github.com/roboloop/media-manager) — Tag and organize media files directly from the player.
- [thepushkarp/iina-metadata](https://github.com/thepushkarp/iina-metadata) — Identify movies and episodes via TMDB/TVmaze, then save metadata and artwork into MKV/MP4 (Kodi/Infuse compatible).
- [wyattowalsh/iina-plugin-bookmarks](https://github.com/wyattowalsh/iina-plugin-bookmarks) — Save and manage video timestamps.

### Danmaku

- [karappo-yu/iina-plugin-danmaku-cosmos](https://github.com/karappo-yu/iina-plugin-danmaku-cosmos) — Niconico/Bilibili/DanDanPlay danmaku with dual CSS & Canvas rendering, Comment Art support and style presets.
- [xjbeta/iina-plugin-danmaku](https://github.com/xjbeta/iina-plugin-danmaku) — Overlay danmaku comments on video.

### Language Learning

- [afn478/iinatan](https://github.com/afn478/iinatan) — Dictionary lookups and Anki mining inside IINA.
- [AkihaZhang/hoshitan](https://github.com/AkihaZhang/hoshitan) — Experimental subtitle dictionary lookup and Anki card creation.
- [alyssabedard/mpv2anki](https://github.com/alyssabedard/mpv2anki) — mpv script for Anki flashcard creation: auto-capture subtitles, audio clips and screenshots.
- [kerim/iina-clickable-subtitles](https://github.com/kerim/iina-clickable-subtitles) — Click subtitles to look up words with macOS Look Up.
- [polyscript-app/polyplugin-release](https://github.com/polyscript-app/polyplugin-release) — PolyScript: dual subtitles, hover dictionary and AI-assisted translation.
- [s4ysolutions/iina-verba](https://github.com/s4ysolutions/iina-verba) — Select a word in the subtitles and press A to add it to your Verba vocabulary.

### Tracking & Sync

- [ethanndickson/iina-lastfm](https://github.com/ethanndickson/iina-lastfm) — mpv script to scrobble music played through IINA to Last.fm.
- [gridness/anilist-sync](https://github.com/gridness/anilist-sync) — Sync watched local anime episodes to AniList after playback reaches 85%.
- [i3p9/iina-trakt-scrobbler](https://github.com/i3p9/iina-trakt-scrobbler) — Trakt.tv scrobbler.
- [kevllarco/iina-plex-sync](https://github.com/kevllarco/iina-plex-sync) — Sync local IINA playback progress and watched status to Plex.
- [notfire/iina-listenbrainz](https://git.notfire.cc/notfire/iina-listenbrainz) — Scrobble your music to ListenBrainz.

## Browser Extensions

- [Open In IINA for Chrome](https://chromewebstore.google.com/detail/open-in-iina/pdnojahnhpgmdhjdhgphgdcecehkbhfo) — Open videos and audio in IINA instead of the browser.
- [Open In IINA for Firefox](https://addons.mozilla.org/firefox/addon/open-in-iina/) — Firefox version of the official extension.
- [IINAplex for Chrome](https://chromewebstore.google.com/detail/iinaplex/epjfaegeibjoigkenalmdagpbmelemik) — Launch Plex media in IINA.
- [n3d1117/plex-to-iina](https://github.com/n3d1117/plex-to-iina) — Safari App Extension for playing Plex content with IINA.
- Safari: "Open in IINA" ships inside IINA.app — enable it in Safari → Settings → Extensions.

The source of the official extension lives in the main repository under [`browser/`](https://github.com/iina/iina/tree/master/browser).

## Launcher Integrations

- [eutialia/open-in-iina](https://github.com/eutialia/open-in-iina) — Open a URL in IINA directly from Alfred or Raycast.

## Tools & Scripts

- [kjtsune/embyToLocalPlayer](https://github.com/kjtsune/embyToLocalPlayer) — Play Emby/Jellyfin/Plex content in local players (including IINA) with progress sync-back.
- [LuckyPuppy514/external-player](https://github.com/LuckyPuppy514/external-player) — Browser userscript to send web video to external players.
- [n3d1117/acestream-iina](https://github.com/n3d1117/acestream-iina) — Play Ace Streams on macOS with IINA.
- [fullmetalsheep/mpv-iina-scripts](https://github.com/fullmetalsheep/mpv-iina-scripts) — mpv Lua scripts made/forked to work with IINA.
- [wpdevelopment11/remote_mpv](https://github.com/wpdevelopment11/remote_mpv) — Remote-control mpv/IINA playback over HTTP from your phone or another PC.

## Forks

- [xjbeta/iina-plus](https://github.com/xjbeta/iina-plus) — IINA fork with extra danmaku support (bilibili etc.).

## Plugin Development

- [Plugin API docs](https://docs.iina.io/) — Official documentation for the IINA plugin API.
- [iina/iina-plugin-template](https://github.com/iina/iina-plugin-template) — Template for creating IINA plugins using iina-cli.
- [iina/iina-plugin-definition](https://github.com/iina/iina-plugin-definition) — TypeScript type definitions for the plugin API (npm: `iina-plugin-definition`).
- [iina/deps-buildscripts](https://github.com/iina/deps-buildscripts) — Build scripts for IINA's dependencies (mpv, ffmpeg, …) since 1.5.0.
- [iina/homebrew-mpv-iina](https://github.com/iina/homebrew-mpv-iina) — Legacy homebrew tap for IINA's custom mpv/ffmpeg (no longer maintained).
- [plugins.json](https://github.com/iina/iina/blob/develop/plugins.json) — The Plugin Center index; submit a PR against the `develop` branch to list your plugin.

## Community & Resources

- [IINA on Wikipedia](https://en.wikipedia.org/wiki/IINA) — Background and history.
- [mpv manual](https://mpv.io/manual/master/) — IINA exposes most mpv options in its advanced settings; the mpv manual is the reference for them.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) — Powers online-media playback in IINA and many plugins.

## Contribute

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first (placeholder — PRs welcome to flesh this out).

- To add a plugin: open a PR with a one-line entry in the right section, linking the repo.
- To get listed in IINA's official Plugin Center, PR [`plugins.json`](https://github.com/iina/iina/blob/develop/plugins.json) on the `develop` branch of iina/iina.

## License

[MIT](LICENSE)
