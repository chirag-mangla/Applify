# Spotify to Apple Music

### 1. Export your Spotify Playlist to a CSV file

The first step is getting the songs you want to import into Apple Music into a CSV file. The simplest way to do this is to use [Exportify](https://watsonbox.github.io/exportify/).

### 2. Match the Spotify songs with their Apple Music identifier and upload them to Apple Music

Run this Command
```bash
python3 convertsongs.py spotify.csv
```

or

```bash
python3 convertsongs.py spotifydir
```


