# Why Torrents are better than streaming servers as a self hosted solution.

Instead of using plex or emby, consider using a dedicated torrent server, and torrent clients elsewhere.

## Quality

- Streaming servers can **never** have the same quality as local music / video players.
  - Video streaming servers like plex or emby, often have to transcode / convert the video to lower-quality formats. Native video players can handle `x265`.
  - Audio streaming servers often can't handle high quality formats like `flac`, whereas local media players can handle these easily.

## Amount of Content

- The content on streaming services are limited to what you *specifically* have downloaded. This can never match the hundreds of thousands of torrents being shared by people across the globe. Search sites like [Torrents.csv](https://torrents-csv.ml/) have often faster searching than self-hosted solutions (and you can self host the searching if you wish).
- Which is better, having a collection of *my music*, or having a collection of *all music*?

## Choice of media player

- With torrents, I can use **any media player I want**. Most OSs make this as simple as a double-click to play media. VLC / MPV can natively play high quality video and audio, x265, flac, opus, etc.
- With streamers, I'm forced either to use a web client, or their own (often proprietary, sometimes paid) app. I prefer open-source standards like VLC.

## Availability / Reliability

- Torrents have effectively solved the data distribution problem: content is shared in a web of connections, and a torrent with more than one seeder is already more resilient than the strongest streaming server.
  - Why should there be 10,000 separate streaming services, not helping each other host or share the data, when torrents have made it so 10,000 clients **are helping each other share the data**?
- Services like plex don't offer this shared hosting.
- Music / content is often removed from services like youtube frequently. Torrents can never be removed.
- People often goto video streaming sites, and these are taken down rapidly. Many torrents have been reliably shared for 10+ years.
- What about hardware failure? If your streaming servers hard drive goes down, you lost everything. With torrents, any with more than one seeder is safe.

## Ease of use

- Streaming servers require you to set up a web server, often requiring you to learn nginx / apache, as well as follow various setup processes for the services themselves. This is understandable for some tech-oriented people, but what about a non-techie, who just likes music / movies? Why should they be required to learn these tools? 
  - Content should be available **for all**, regardless of technical skill, or ability.
- Downloading a torrent, and enjoying the media, involves:
  - Clicking a download magnet link. Wait for it to finish.
  - Open it.

## Caching / Saving / Streaming

- Many of us don't have data, or are often in areas where data is spotty. 
  - Its often a *feature* of services like plex to be able to save media locally, to avoid this problem. This is default with torrents.
- Torrent clients like qbittorrent and libretorrent for android let you *download files in sequential order*, IE stream, at the click of a button.
- Services like [Torrents.csv](https://torrents-csv.ml) let you search for files within torrents, so you can easily download / stream individual songs.
- Its your choice where things are downloaded to. You can have a desktop or server with a highly available torrent client, and/or a smartphone torrent client.

