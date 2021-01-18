# Transcriptions for the Hello Internet podcast

This project will help people search for segments and possibly create new episodes using machine learning!


See the episode list [here](Episodes.md)

## Contributing
If you want to transcribe an episode, make an issue so we know who is working on what. If you find an already transcribed episode, put it there also. If you can't bother to make a GitHub account, send me a private message on Reddit (u/muhammed_smith).

## Format
All files are in plain text.
### Header Format
- Podcast name, episode number, and name
- Date published in ISO format YYYY-MM-DD
- Runtime
- List of contributors
- Empty Line

Example:
```
Hello Internet #135: Place Your Bets
2020-01-23
1:30:06
Transcribed by (...).

Brady: (...)
```

### File Structure
- Main episodes (have a number) are stored in `/episode/(num).txt`, where num is a three digit number. For example: `/episode/020.txt` is the 20th episode.
- 12 days of Hello Internet are placed in `/12days/(num).txt`
- Extra cuts (from the YouTube channel) are placed in `/extra/(cutname).txt` For example: `/extra/060.1.txt`
- If there are any extra clips that don't have a number (Vinyl episode, wax cylinder edition), place them in `/extra/` with their name.

### Transcript Structure
When a new person talks, start with their name and a colon.
Example:
```
Brady: (...)
Grey: (...)
Brady: (...)
```
Put notes like: laughing, chuckles, etc. in square brackets. `[laughs]`.
When there is transitional music put a new line then: `*Intro music*`, or `*Transitional Music*`, then another new line.
Other than that, use whatever format you would like.
Following these is important so something like a machine learning algorithm can understand that they are not spoken words.


## Helpful tools
### Liniarc's transcribing tool
http://liniarc.github.io/transcriber/ is a useful tool to upload an audio file and navigate while transcribing.

### Automatically-generated captions
Obviously, they are often inaccurate and do not specify who is talking, but you may find it faster to copy and edit than to write from scratch.
They are stored here: http://podcastsearch.david-smith.org/shows/6

### Subreddit
There is also a dedicated subreddit for this, https://reddit.com/r/T_HIP, although it is inactive.
