# Chatty

![Chatty](docs/screenshot.png)

**A Twitch chat client for streamers, with OBS overlays built in.**

Chatty is a desktop chat client for Windows and Linux. It puts every channel you
care about in one window, gives you the moderation tools you would otherwise go
to the Twitch site for, and doubles as the alert and chat overlay system for your
stream — so you are not running a separate browser-source service alongside it.

[**Download the latest release →**](../../releases/latest)

---

## What it does

### Chat

- **Multi-pane** — split the window into as many channels as you want, across
  tabs, in whatever arrangement suits you. Your layout comes back after a restart.
- **Every emote** — Twitch, BTTV, FFZ and 7TV, in chat and in an emote picker
  that lists everything your account can actually type, grouped per channel.
- **Badges and name colours** exactly as they appear on Twitch.
- **Whispers** in a dockable panel, with whispers mirrored into your own channel
  so you notice them mid-stream.
- **Notification sounds** for mentions and whispers — two soft cues, one rising,
  one falling, so you can tell them apart without looking. Off-switchable.
- **Chat logs** written to disk per channel, if you want them.

### Streaming and moderation

- **Full slash commands** — `/ban`, `/timeout`, `/mod`, `/vip`, `/raid`,
  `/announce`, `/settitle`, `/setgame`, `/marker`, `/shoutout` and more, with
  autocomplete.
- **`/poll`** — start a poll without leaving the app, and watch it fill in on a
  banner above chat with live vote counts, bars and a countdown.
- **Raid banner** — who you are raiding, how long is left, and a Cancel button.
- **Activity Feed and Mod Actions** panels, embedded and always current.
- **User cards** with a viewer's history in your channel.

### OBS overlays

Chatty runs a small local server and hands you three browser-source URLs. No
account anywhere else, no subscription, nothing leaves your machine.

- **Alerts** — a bar that slides in for follows, subs, resubs, gifted subs,
  cheers and raids, with per-type text, colours and hold times. Bring your own
  sound for any alert type, or use the built-in cue.
- **Chat overlay** — your chat on stream, with badges, real name colours and
  emotes. Optional transparent background box with adjustable colour, opacity,
  corner radius and padding for when chat sits over bright gameplay.
- **Event glow** — the chat overlay blooms in the colour of whatever just
  happened: sky blue for a follow, violet for subs, pink for gifted subs, amber
  for bits, rose for a raid, orange for a hype train. Every colour is yours to
  change, and the whole thing has an off switch.
- **Trigger Board** — fire your own sounds and clips on stream from a grid.

Overlays reload themselves when the app is updated, so an OBS source can never
sit there serving a stale page after an upgrade.

---

## Install

### Windows

Download **`Chatty-Setup.exe`** from the
[latest release](../../releases/latest) and run it. You can choose the install
location. Chatty will offer to update itself from here when a new version lands.

### Linux

Download **`Chatty.AppImage`**, make it executable, and run it:

```bash
chmod +x Chatty.AppImage
./Chatty.AppImage
```

No installation, no package manager, no dependencies to chase — an AppImage is
a single self-contained file that runs on any modern distribution.

Chatty updates itself from this page: when a new version is out it downloads
the new AppImage and replaces itself in place. Keep it somewhere you can write
to (your home folder is ideal) so it can do that.

---

## About this repository

This repository hosts **release builds and this README only** — there is no
source code here. Chatty is developed privately.

Made by **d3mon** — [d3mon.gg](https://d3mon.gg)

If Chatty is useful to you, consider creating an account on
[d3mon.gg](https://d3mon.gg) and subscribing from your
[account settings](https://d3mon.gg/account/subscription).
