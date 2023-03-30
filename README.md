# iptv
`iptv` is a CLI IPTV player for M3U playlists with fuzzy finding, right in your terminal.

![iptv](https://user-images.githubusercontent.com/4785263/228887981-3efb80a9-e40d-4076-b234-8fa737527018.gif)

The playlist will be updated once a day whenever you run `iptv`.

## Dependencies
- [curl](https://github.com/curl/curl)
- [fzf](https://github.com/junegunn/fzf)
- [mpv](https://github.com/mpv-player/mpv)

All dependencies can be installed with your package manager.

## Installation
```
sudo wget https://raw.githubusercontent.com/shahin8r/iptv/master/iptv -qO /usr/local/bin/iptv && sudo chmod +x /usr/local/bin/iptv
```

Run `iptv` with your playlist URL to load all the channels (only needed on first run).
```
iptv https://raw.githubusercontent.com/Free-TV/IPTV/master/playlist.m3u8
```

## Usage
Run `iptv`.
