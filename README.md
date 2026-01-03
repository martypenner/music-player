This is my version of a browser-based audio player for managing and playing playlists with crossfade support, controllable over websocket by e.g. [Chataigne](https://github.com/benkuper/Chataigne) or other show control software.

## Features:

- Import audio from folders or M3U files
- Crossfade, fade-in, and fade-out with configurable durations
- Volume normalization with adjustable target loudness
- Shuffle and loop modes
- Trim tracks with waveform editor
- Export/import backups (optionally including audio files)
- WebSocket remote control for external automation
- Persistent storage (playlists and settings saved in browser and exportable)

## Remote Commands (via WebSocket):

- play, pause, stop, hardstop, next, prev
- playtrack "Track Name", playplaylist "Playlist Name"
- volume, shuffle, loop, and more.

Open player.html in your browser, click once anywhere to tell the browser you're a human, and you should be good to go!