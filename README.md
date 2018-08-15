# lyrics-crawler
[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/willamesoares)

Get the lyrics for the song currently playing on Spotify or search for any song passing its title and artist name in the command line.

### Setup
In order to use this script you have to create your own [Genius API](https://docs.genius.com) Access Token and place it into the `constants.py`

like this `TOKEN='YOUR_GENIUS_API_TOKEN'`.

### Default search
`python3 get-lyric.py`

### Custom search
`python3 get-lyric.py [song_title] [artist_name]`
