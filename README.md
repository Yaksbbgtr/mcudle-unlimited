# MCU-dle Unlimited

A personal Wordle-style Marvel Cinematic Universe character-guessing game (films and Disney+ shows) with unlimited rounds. Built from the Cosmeredle Unlimited engine.

## Columns

Character · Debut (▲/▼ by release order) · Phase (▲/▼) · Affiliation · Species · Gender · Role · Status

## Updating the data

- `tools/titles.json`: every film/show in release order as `[title, phase]`
- `tools/characters.source.json`: the characters (format at the top of `tools/build_data.py`)

Then run `python3 tools/build_data.py`.

Marvel characters belong to Marvel/Disney. This is a fan project for personal use only.
