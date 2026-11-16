# Potterdle Unlimited

A personal Wordle-style Harry Potter character-guessing game with unlimited rounds. Built from the Cosmeredle Unlimited engine.

## Play

Open `index.html` in a browser. There's no build step and no server.

## Columns

Character · House · First book (▲/▼ if the answer appears later or earlier) · Blood status · Affiliation · Family

## Updating the character list

Edit `tools/characters.source.json` (the format is described at the top of `tools/build_data.py`), then run:

```sh
python3 tools/build_data.py
```

Harry Potter characters and settings belong to their owners. This is a fan project for personal use only.
