# Status — 2026-09-25

## Shipped on `main`
- Audio engine: bit-perfect ALSA output with lossless container negotiation,
  hardware pause, gapless, native-rate switching, ReplayGain/preamp, mute,
  seekable HTTP spooling, ICY titles, clean stop on device loss.
- Library v2: incremental parallel scan + watcher, FTS5 search, albums /
  artists / genres / favorites / history / playlists (M3U), cover cache with
  Cover Art Archive fallback, synced lyrics (.lrc, tags, lrclib).
- Controller: stable queue ids, shuffle/repeat, session restore, play counts,
  event bus; scrobbling (ListenBrainz, Last.fm) with offline queues.
- UPnP: AVTransport + OpenHome renderer on one device, MediaServer with
  hierarchy/search/range serving, SSDP fixes. MPRIS with Raise/Quit.
- Desktop app (Slint): full redesign, EN/FR, tray, notifications,
  single instance, headless snapshot mode for screenshots.

## Next candidates
- Real-device reports for the control-point matrix (docs/CONTROLS.md).
- Device capabilities panel (supported rates/containers of the selected DAC).
- Parametric EQ / convolution (optional, non bit-perfect).
- DSD (DoP), CUE sheets, multi-disc box sets view, composer/work view for
  classical.
- Flatpak / AppImage packaging.

## Rules
- Never test with `hw:` devices — only `null` / `file:` sinks.
- No streaming-service private API code, ever.
- Builds are capped at 4 jobs (`.cargo/config.toml`, not committed).
