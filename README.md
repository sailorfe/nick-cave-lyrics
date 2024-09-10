# Nick Cave lyric database

Lyrics Nick Cave has published for The Birthday Party, Nick Cave & The Bad Seeds, Grinderman, and *Carnage* compiled from [his official website](https://www.nickcave.com/lyrics/) and *Nick Cave The Complete Lyrics 1978–2013* (Penguin Books, 2013).

## Editorial Notes

- "Mutiny in Heaven:" Really looks best on a printed page. My indentations are a sorry approximation of the form he intended. Quite sculptural!
- "Hollywood:" Includes his four-asterisk divider.
- "White Elephant:" Includes his dedication to Thomas Houseago.
- The Bad Seeds and Grinderman lyrics are verbatim from his website, with exceptions:
    - "There Is A Kingdom:" Added linebreak that looked missing between "Just like a bird  / That sings up the sun"
    - "Babe, I'm On Fire:" Replaced his "Chorus"'s with the chorus text.
    - "Let the Bell Ring:" Replaced his "(Chorus)"'s with thie chorus text.
    - "O Children:" Was missing spaces after each "Hey little train!"
    - All of *Grinderman 2* except for "Palaces of Montezuma:" Removed double linebreaks.
    - "Anthrocene:" Removed double linebreaks.
    - "I Need You:" Removed double linebreaks.
    - "Distant Sky:" [Does not currently have a lyric up](https://www.nickcave.com/lyric/distant-sky/), so this is transcribed.
    - "Skeleton Tree:" Removed double linebreaks.
    - All of *Carnage*: Removed double linebreaks.
    - "Wild God": Removed double linebreaks, and I suspect will do for the rest of the album.
- 1984–2013 non-album exclusions are listed in `exclusions.md`. 

## Changelog

### 2024-09-10

- Added *Wild God*.

### 2024-08-27

- Fixed verse breaks on "Mickey Mouse and the Goodbye Man" and "Heathen Child."
- Removed "Long Time Man."
- Added "Needle Boy" and "Lightning Bolts."
- Deleted `songs.csv`.
- Created `album-map.json`.

### 2024-08-26
- Removed "Avalanche" and *Kicking Against the Pricks*.
- Added 1978-83 lyrics to `lyrics.csv`.
- Added 1978-83 songs from *The Complete Lyrics* to `songs.csv`.
- Added artist to `lyrics.json` for future filtering.

### 2024-08-25
- Inserted choruses on "Babe, I'm On Fire" and "Let the Bells Ring."
- Created `lyrics.json` with individual, previous, and next lines.

### 2024-08-24
- Only files now are `songs.csv` and `songs.json`.
- Updated license.
- Deleted `album_map.json` and `song_titles.txt`.

### 2024-08-23
- *Abattoir Blues / The Lyre of Orpheus* are back to being one album;
    `album_map.json`, `lyrics.csv`, `lyrics.json`, `songs.csv` edited.

### 2024-08-22
- Created `album_map.json`, `lyrics.csv`, `lyrics.json`, `songs.csv` and `song_titles.txt`.
- Deleted `scraper.py`, `local.py.default` and `requirements.txt`.

## thank you 🫶

- [csvkit](https://github.com/wireservice/csvkit)
- [csv2json](https://github.com/julien-f/csv2json)
- listening on [spotify-player](https://github.com/aome510/spotify-player)
- Shayna Kothari, I didn't end up using the Genius API scraper but the structure of [shaynak/taylor-swift](https://github.com/shaynak/taylor-swift) inspired this!!
