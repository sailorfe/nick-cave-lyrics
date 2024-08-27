# Nick Cave lyric database

Lyrics Nick Cave has published for The Birthday Party, Nick Cave & The Bad Seeds, Grinderman, and *Carnage* compiled from [his official website](https://www.nickcave.com/lyrics/) and *Nick Cave The Complete Lyrics 1978–2013* (Penguin Books, 2013).

The Bad Seeds and Grinderman lyrics are verbatim from his website, with exceptions:

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

Not quite editorializations but other things to note:

- "Mutiny in Heaven:" Really looks best on a printed page. My indentations are a sorry approximation of the form he intended. Quite sculptural!
- "Hollywood:" Includes his four-asterisk divider.
- "White Elephant:" Includes his dedication to Thomas Houseago.

As of 2024-08-27, I have no plans to include these 1984–2013 songs included in *The Complete Lyrics* but not part of any albums:

- 1984: "The Moon is in the Gutter," "Just a Closer Walk with Thee," "The Six Strings that Drew Blood," "Oh I Love You Too Much"
- 1985: "Scum"
- 1986: "God's Hotel"
- 1988: "Girl at the Bottom of My Glass," "That's What Jazz is to Me"
- 1990: "The Train Song"
- 1992: "Faraway, So Close!", "Cassiel's Song," "Blue Bird"
- 1994: "Sail Away," "(I'll Love You) Till the End of the World," "What Can I Give You?"
- 1996: "The Ballad of Robert Moore and Betty Coltrane," "There is a Light," "Time Jesum Transeuntum Et Non Revertentum"
- 1997: "Little Empty Boat," "Come Into My Sleep," "Rigth Now, I am A-Roaming," "Babe, I Got You Bad," "The Bridle Path," "Wife," "Opium Tea," "The Sweetest Embrace," "Little Water Song," "Still Your Face Comes Shining Through," "Sweet Little Sleep," "Sheep May Safely Graze"
- 2001: "Little Janey's Gone," "A Grief Came Riding," "A Good, Good Day," "Bless His Ever-Loving Heart"
- 2003: "Shoot Me Down," "Swing Low," "Everything Must Converge"
- 2004: "She's Leaving You," "Under His Moon"
- 2005: Music from *The Proposition* (Soundtrack from the Film, 2005)
- 2007: "Chain of Flowers"
- 2013: "Needle Boy," "Lightning Bolts"

## Changelog

### 2024 Aug 26
- Removed "Avalanche" and *Kicking Against the Pricks*.
- Added 1978-83 lyrics to `lyrics.csv`.
- Added 1978-83 songs from *The Complete Lyrics* to `songs.csv`.
- Added artist to `lyrics.json` for future filtering.

### 2024 Aug 25
- Inserted choruses on "Babe, I'm On Fire" and "Let the Bells Ring."
- Created `lyrics.json` with individual, previous, and next lines.

### 2024 Aug 24
- Only files now are `songs.csv` and `songs.json`.
- Updated license.
- Deleted `album_map.json` and `song_titles.txt`.

### 2024 Aug 23
- *Abattoir Blues / The Lyre of Orpheus* are back to being one album;
    `album_map.json`, `lyrics.csv`, `lyrics.json`, `songs.csv` edited.

### 2024 Aug 22
- Created `album_map.json`, `lyrics.csv`, `lyrics.json`, `songs.csv` and `song_titles.txt`.
- Deleted `scraper.py`, `local.py.default` and `requirements.txt`.

## thank you 🫶

- [csvkit](https://github.com/wireservice/csvkit)
- [csv2json](https://github.com/julien-f/csv2json)
- listening on [spotify-player](https://github.com/aome510/spotify-player)
- Shayna Kothari, I didn't end up using the Genius API scraper but the structure of [shaynak/taylor-swift](https://github.com/shaynak/taylor-swift) inspired this!!
