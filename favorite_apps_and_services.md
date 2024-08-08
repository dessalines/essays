# Favorite apps and services

## Contents

<!-- toc -->

- [Goals](#goals)
- [Media](#media)
- [Documents and Coding](#documents-and-coding)
  - [Hosting](#hosting)
- [Tasks / Todos](#tasks--todos)
- [Collaboration](#collaboration)
- [Browsing](#browsing)
- [Passwords](#passwords)
- [Mobile keyboard](#mobile-keyboard)
- [Calendars / Contacts](#calendars--contacts)
- [Chat / Communication](#chat--communication)
- [Social Media](#social-media)
- [Operating system](#operating-system)
- [Links](#links)

<!-- tocstop -->

## Goals

- Privacy conscious, [end-to-end encrypted (E2EE)](https://en.wikipedia.org/wiki/End-to-end_encryption).
- Decentralized, **no reliance** on cloud providers like Google, Microsoft, Apple, Spotify, Netflix Youtube, etc.
  - Self-hosted and self-reliant.
  - Simple files preferred over running services.
- Make sure no sites / services are [US based.](https://en.wikipedia.org//wiki/Five_Eyes)

## Media

- Download all music / movies locally, using torrents, behind a VPN. [Don't use Tor for torrenting](https://blog.torproject.org/bittorrent-over-tor-isnt-good-idea).
  - Use [Mullvad](https://mullvad.net/) or a similar Wireguard-capable VPN.
  - Use [qbittorrent](https://www.qbittorrent.org/), [deluge](https://www.deluge-torrent.org/), or [transmission](https://transmissionbt.com/) for PC, [LibreTorrent](https://github.com/proninyaroslav/libretorrent) for android.
- Use [MPV](https://mpv.io/) or [VLC](https://www.videolan.org/vlc/download-windows.html), open source media players to play media.
- Use [Jellyfin](https://github.com/jellyfin/jellyfin) as a home media server.
- Use [Navidrome](https://github.com/deluan/navidrome) for a self-hosted music server, and [Tempo](https://github.com/CappielloAntonio/tempo) for an android client.
- Instead of centralized, hosted youtube alternatives with upload limits, use torrents / torrent sites, such as [1337x.to](https://133x.to), or [torrents-csv.com](https://torrents-csv.com)

## Documents and Coding

- Install [Syncthing](https://syncthing.net/), and put all your documents in a synced folder. Use [Syncthing-Fork](https://github.com/Catfriend1/syncthing-android) for Android.
- Write all documents and notes in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
  - Use [Markor for android](https://github.com/gsantner/markor), or any text editor for markdown notes. [Obsidian](https://obsidian.md/mobile) is great, but not open source.
  - Or use [Hedgedoc](https://hedgedoc.org) for an online, collaborative solution.
- Use [helix](https://helix-editor.com/), or vim with [vimrc](https://github.com/amix/vimrc) and [coc.nvim](https://github.com/neoclide/coc.nvim) for code.
  - Do not use vscode, it's [difficult to impossible to turn off keylogging](https://stackoverflow.com/questions/40451596/visual-studio-code-still-accessing-internet-after-update-and-telemetry-was-disab). If you must, use [VSCodium](https://github.com/VSCodium/vscodium#why-does-this-exist), which removes the built-in telemetry.
- Spreadsheets in [Libreoffice](https://www.libreoffice.org/).

### Code Hosting

- [Codeberg.org](https://codeberg.org) is a good shared code host.
- Otherwise, self host a [Gitea](https://gitea.io/) instance.

## Tasks / Todos

- Use [tasks.org](https://tasks.org).
- For shared task lists, use [Hedgedoc](https://hedgedoc.org/).

## Collaboration

- Use [Hedgedoc](https://hedgedoc.org/), a live / collaborative markdown editor.
- [NextCloud](https://nextcloud.com/) for a more expansive document store.

## Browsing

- [Use Librewolf](https://librewolf.net/) on desktop, or use Firefox or Tor Browser, with the addons:
  - [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
- Use [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/) or [Fennec](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid/) for android.
- Use [Searx](https://searx.me/), as a search engine

## Passwords

- Use [KeePassXC](https://keepassxc.org/) for PC, [KeePassDX](https://www.keepassdx.com/) for android.
  - Install the [Firefox KeePassXC plugin](https://addons.mozilla.org/en-US/firefox/addon/keepassxc-browser/).
  - Use a long master pass phrase, with at least 10 words.
  - Sync your password file everywhere you need using Syncthing.
- [Bitwarden](https://bitwarden.com/) if you want to host a server.

## Mobile keyboard

- Use a secure keyboard on android if you don't want your passwords stolen by google.
- Use my keyboard, [Thumb-Key](https://github.com/dessalines/thumb-key), or [Heliboard](https://github.com/Helium314/HeliBoard) for a QWERTY layout.

## Calendars / Contacts

- Use tasks.org for calendar / date related items.

## Chat / Communication

- Matrix / [Element](https://element.io/) for SMS and chatrooms.
- [Briar](https://briarproject.org/) for extreme security.
- [Don't use Signal.](why_not_signal.md)
- [Don't use Discord.](https://spyware.neocities.org/articles/discord)

### Email

- [Thunderbird](https://www.thunderbird.net/en-US/) for desktop email, e2ee with pgp if possible.
- [FairEmail](https://email.faircode.eu/) for android.

## Social Media

- Reddit : [Lemmy (I'm a dev)](https://github.com/LemmyNet/lemmy), [Lobste.rs](https://github.com/lobsters/lobsters).
- Twitter alternative : [Pleroma](https://pleroma.social/), [Mastodon](https://mastodon.social/)
- Facebook : [Friendica](https://friendi.ca/)
- Medium : [Plume](https://github.com/Plume-org/Plume), [WriteFreely](https://github.com/writeas/writefreely)
- YouTube : Torrents, or [Peertube](https://github.com/Chocobozzz/PeerTube).
- Instagram : [Pixelfed](https://pixelfed.org/)

## Operating system

- Use Linux. I like [Arch Linux](https://archlinux.org/).
- On mobile, use a de-googled android with google play services removed.

## Links

- [PrivacyGuides.org](https://www.privacyguides.org/)
