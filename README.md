# Dataset of July 05 2025
Datasets of MusicBrainz, Tidal, Spotify, Deezer

You can use these tables for MiniMedia's database, it will save you huge amounts of time, instead calling the API's yourself

Tidal, Spotify, Deezer datasets were obtained through their API, took months of calling their API's 24/7

MusicBrainz came mostly through their own published dataset + API

Note for Deezer dataset: The Preview Url (to listen to the first x seconds of a song) and TrackToken (for playback) fields will be empty, it took too much space to store all of this for me

Packed: ?GB

Unpacked ?GB

Loving the work I do? buy me a coffee https://buymeacoffee.com/musicmovearr

## MusicBrainz
You can officially download it here: https://metabrainz.org/datasets/postgres-dumps#musicbrainz

But the official dataset is huge, a lot larger then I'm sharing, this is because I saved it more efficiently

## Contains:
Total Size: ~20GB in postgres, 270GB provided by MusicBrainz in json-format

Artists: 2.5mil

Albums: 4.8mil

Tracks: 49mil

## Spotify

## Contains:
Total Size: ~3GB in postgres

Artists: 214k

Albums: 408k

Tracks: 2.1mil


## Tidal
## Contains:
Total Size: ~15GB in postgres

Artists: 456k

Albums: 2.3mil

Tracks: 14.6mil

## Deezer
## Contains:
Total Size: ~120GB in postgres

Artists: 4.1mil

Albums: 21.7milx

Tracks: 118.7mil


# Dataset of June 07 2025
Datasets of MusicBrainz, Tidal, Spotify

These datasets contain zero modifications from myself, they're straight from the source

You can use these tables for MiniMedia's database, it will save you huge amounts of time, instead calling the API's yourself

Tidal, Spotify datasets were obtained through their API, took months of calling their API's 24/7

MusicBrainz came mostly through their own published dataset + API

Packed: 4.5GB

Unpacked 44.6GB

Loving the work I do? buy me a coffee https://buymeacoffee.com/musicmovearr


## MusicBrainz
You can officially download it here: https://metabrainz.org/datasets/postgres-dumps#musicbrainz

But the official dataset is huge, a lot larger then I'm sharing, this is because I saved it more efficiently

## Contains:
Total Size: ~20GB in postgres, 270GB provided by MusicBrainz in json-format

Artists: 2.5mil

Albums: 4.8mil

Tracks: 49mil

## Spotify

## Contains:
Total Size: ~1GB in postgres

Artists: 64k

Albums: 196k

Tracks: 1.1mil


## Tidal
## Contains:
Total Size: ~3GB in postgres

Artists: 118k

Albums: 403k

Tracks: 2.5mil

# FAQ:
## Why is Spotify's dataset so "small" compared to MusicBrainz? 
Spotify has a pain in the ass rate limit, I can only call their API every 10seconds to not trigger their rate limiter too fast and then it will block the API key for ~15hours...

Plus keep in mind that the dataset of Spotify is not complete, I can only fetch ~500 artists in a day...

## Why is Tidal's dataset so "small" to MusicBrainz? 
Tidal's api rate limiter is alright but I can only make ~200 API calls per (15 minutes?), it's not super fast but compared to spotify it doesn't block me for ~15hours

Plus keep in mind that the dataset of Tidal is not complete
