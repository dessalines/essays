# Images.csv

An open source repository of images, and image hosting server.

It consists of:

- A CSV file, containing a list of images, and torrent_infohashes.
- An image upload server, that can serve any of those images on demand.

csv columns: `image_hash, torrent_infohash, tags, filename, ip`

- Someone runs a server, it has a simple image file upload API. 
- The front end does an image hash check before uploading against a primary images.csv source hosted somewhere.
- If the hash is new, the upload goes through, and a change to that file is done somehow. The server creates a torrent, and seeds it, and adds that line. 
- if the hash already exists, the server torrents the file, and serves it as an upload. 
- A `size_limit` is given to make sure the server doesn't seed above a certain limit, and removes older files. Maybe ~100MB by default.
- Periodic scrapes ensure that everything is always available.

## Links

- https://github.com/lolney/rust-bittorrent-client
