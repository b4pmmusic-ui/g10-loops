# g10-loops
# library for g10 loops AI
# B4pm Music
This repository serves as a public library of audio loops (WAV/MP3) for web app use. Loops are organized by genre.

## Structure

```
ai-loops-samples/
 ┣ lofi/
 ┃ ┣ dreamy_loop1.wav
 ┃ ┣ dusty_tape2.wav
 ┣ retro/
 ┃ ┣ neon_synth1.wav
 ┣ samples.json
```

## `samples.json` Example

Each entry should reference the correct raw file URL for public access:

```json
[
  {
    "title": "Dreamy Loop 1",
    "genre": "lofi",
    "url": "https://raw.githubusercontent.com/b4pmmusic-ui/g10-loops/main/lofi/dreamy_loop1.wav"
  },
  {
    "title": "Dusty Tape 2",
    "genre": "lofi",
    "url": "https://raw.githubusercontent.com/b4pmmusic-ui/g10-loops/main/lofi/dusty_tape2.wav"
  },
  {
    "title": "Neon Synth 1",
    "genre": "retro",
    "url": "https://raw.githubusercontent.com/b4pmmusic-ui/g10-loops/main/retro/neon_synth1.wav"
  }
]
```

## How to Add More Loops

1. Place your audio file in the appropriate genre folder.
2. Add a corresponding entry in `samples.json` with the correct file name and URL.
3. Commit and push your changes.

---

Feel free to copy this layout into your repository, upload your audio samples, and fill in the `samples.json` metadata!