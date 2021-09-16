# Favorite apps and services

## Contents

<!-- toc -->

- [Goals](#goals)
- [Media](#media)
- [Documents and Coding](#documents-and-coding)
  * [Hosting](#hosting)
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
- Make sure no sites / services are [US based.](https://www.privacytools.io/providers/#ukusa)

## Media

- Download all music / movies locally, using torrents, behind a VPN. ([Don't use Tor for torrenting](https://blog.torproject.org/bittorrent-over-tor-isnt-good-idea))
  - Use [AirVPN](https://airvpn.org/), [Mullvad](https://mullvad.net/), [NordVPN](https://nordvpn.com/)
  - Use [qbittorrent](https://www.qbittorrent.org/), [deluge](https://www.deluge-torrent.org/), or [transmission](https://transmissionbt.com/) for PC, [LibreTorrent](https://github.com/proninyaroslav/libretorrent) for android.
- Use [MPV](https://mpv.io/) or [VLC](https://www.videolan.org/vlc/download-windows.html), open source media players to play media.
- Use [Jellyfin](https://github.com/jellyfin/jellyfin) as a home media server.
- Use [Navidrome](https://github.com/deluan/navidrome) for a self-hosted music server, and [DSub](https://github.com/daneren2005/Subsonic) for an android client.
- Instead of centralized, hosted youtube alternatives with upload limits, use torrents / torrent sites. 

## Documents and Coding

- Install [Syncthing](https://syncthing.net/), and put all your documents in a synced folder. Use [Syncthing-Fork](https://github.com/Catfriend1/syncthing-android) for Android.
- Write all documents and notes in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
  - Use [Typora](https://typora.io/), [MarkText](https://marktext.github.io/website/), or vim as markdown editors / notes. 
- Use vim with [vimrc](https://github.com/amix/vimrc) and [coc.nvim](https://github.com/neoclide/coc.nvim) for code.
  - Do not use vscode, it's [difficult to impossible to turn off keylogging](https://stackoverflow.com/questions/40451596/visual-studio-code-still-accessing-internet-after-update-and-telemetry-was-disab). If you must, use [VSCodium](https://github.com/VSCodium/vscodium#why-does-this-exist), which removes the built-in telemetry.
- Spreadsheets in [Libreoffice](https://www.libreoffice.org/).

### Hosting

- [Codeberg.org](https://codeberg.org) is a good shared code host.
- Otherwise, self host a [Gitea](https://gitea.io/) instance.

## Tasks / Todos

- Use a [todo.txt](http://todotxt.org/) file for a personal task list, synced with syncthing.
  - [QTodoTxt2](https://github.com/QTodoTxt/QTodoTxt2) as a desktop client, [todo.txt-vim](https://github.com/freitass/todo.txt-vim), [Simpletask Cloudless](https://play.google.com/store/apps/details?id=nl.mpcjanssen.simpletask&hl=en_US) for Android.
- For shared task lists, use [Hedgedoc](https://hedgedoc.org/).

## Collaboration

- Use [Hedgedoc](https://hedgedoc.org/), a live / collaborative markdown editor.

## Browsing

- Use Firefox or Tor Browser, with the addons:
  - [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
  - [Facebook Container](https://addons.mozilla.org/en-US/firefox/addon/facebook-container) - Keeps all Facebook stuff in it's own container.
  - [Google Container](https://addons.mozilla.org/en-US/firefox/addon/google-container/)
- [Startpage](https://www.startpage.com/), [Searx](https://searx.me/) ([onion service](http://searchb5a7tmimez.onion/)), as a search engine
- If using Tor, use onion services if possible.

## Passwords

- Use [KeePassXC](https://keepassxc.org/) for PC, [KeePassDX](https://www.keepassdx.com/) for android.
  - Install the Firefox KeePassXC plugin.
  - Use a long master pass phrase, with at least 10 words. 
  - Sync your password file everywhere you need using Syncthing.
- [Bitwarden](https://bitwarden.com/) if you want to host a server. 

## Mobile keyboard

- Use a secure keyboard on android if you don't want your passwords stolen by google.
- [Florisboard](https://github.com/florisboard/florisboard), [MessageEase](https://play.google.com/store/apps/details?id=com.exideas.mekb&hl=en_US&gl=US), [OpenBoard](https://f-droid.org/en/packages/org.dslul.openboard.inputmethod.latin/), or [AnySoftKey](https://anysoftkeyboard.github.io/) work.

## Calendars / Contacts

- Use Syncthing + [DecSync](https://github.com/39aldo39/DecSync) for calendar and contact sync from android to desktop. [Radicale is a server based solution. ](https://radicale.org/)

## Chat / Communication

- Use Matrix / [Element](https://element.io/).
- Use [Briar](https://briarproject.org/) for extreme security.
- Use [Thunderbird](https://www.thunderbird.net/en-US/) for email, e2ee with pgp if possible. 
- [Don't use Signal.](why_not_signal.md)

## Social Media

- Reddit : [Lemmy (I'm a dev)](https://github.com/LemmyNet/lemmy), [Lobste.rs](https://github.com/lobsters/lobsters).
- Twitter alternative : [Pleroma](https://pleroma.social/), [Mastodon](https://mastodon.social/)
- Facebook : [Friendica](https://friendi.ca/)
- Medium : [Plume](https://github.com/Plume-org/Plume), [WriteFreely](https://github.com/writeas/writefreely)
- YouTube : Torrents, or [Peertube](https://github.com/Chocobozzz/PeerTube). 
- Instagram : [Pixelfed](https://pixelfed.org/)

## Operating system

- Use Linux. I like Arch Linux. 

## Links

- [PrivacyTools.io](https://www.privacytools.io/)
