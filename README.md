# NIGHT BROADCAST

**Live:** https://htmlpreview.github.io/?https://github.com/cw4dpcd7p9-bot/night-broadcast/blob/main/index.html

Type any sentence. Watch a city grow out of it.

A single HTML file. No build step, no packages, no backend. The string you type is hashed into a seed. That seed decides the skyline, the station name, the frequency, which windows stay on, and how the highway moves.

Same sentence, same city. Every time.

## Open it locally

Clone it and double-click `index.html`, or serve the folder:

```bash
python3 -m http.server 8080
```

Then go to `http://localhost:8080`.

The phrase lives in the URL hash, so you can send someone a specific city:

```
index.html#q=the%20city%20only%20talks%20after%20midnight
```

## Keys

- type anything in the transmit field
- `enter` locks the signal
- `s` saves a still
- `/` focuses the field

## Why this exists

Most “generative” pages look like a shadertoy demo wearing a trench coat. This one is supposed to feel like a late-night radio station that only exists while you are looking at it.

The architecture is deterministic on purpose. A lyric, a wallet, a name, a lie — each one gets a skyline that will not change unless you change the words.

## Files

```
index.html   the whole broadcast
LICENSE      MIT
```

That’s the repo.
