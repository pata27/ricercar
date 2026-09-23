# Session state — 2026-09-23

Everything is committed on `main` (5 commits). Working tree clean. Nothing lost by reboot.

## Done
- All 5 crates implemented and green: `cargo test --workspace` = 16/16, clippy `-D warnings` clean, fmt clean.
- Verified end-to-end (under `dbus-run-session`, device `null` only — no sound ever hit hardware):
  - UPnP MediaRenderer: SSDP, device.xml, SetAVTransportURI→Play→SetNext→gapless switch→STOPPED, GENA, volume
  - MPRIS: registered `org.mpris.MediaPlayer2.ricercar`, Properties.Get, Play/OpenURI work
  - daemon + cli + ui binaries run (`ricercar-ui --headless` works; slint UI compiles, not yet smoke-tested on a real display)

## Pending (next session)
1. `git push origin main` — LAST ATTEMPT FAILED with HTTP 408 (transient/network). Retry; if it keeps failing check push size (`git count-objects -v`) / try ssh.
2. `cargo build --release --workspace` — was NOT started (push failed first in the `&&` chain).
3. Tag + GitHub release `v0.1.0-alpha` via `gh release create` with the release binaries/tarball.
4. Optional before release: smoke the slint UI on the real desktop; test against BubbleUPnP on the LAN.

## Reminders
- NEVER test with `hw:` devices — only `null` / `file:` sinks.
- Repo: https://github.com/pata27/ricercar (public). Strategy doc: /home/antoine/Code/qbz/plan.md
- No Qobuz code ever; control points push URLs only.
