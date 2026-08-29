# Reasons or Results

An illustrated, interactive guide for ages 12+ on the difference between having a reason and getting a result, told through Chuck Yeager's 1947 flight past the sound barrier.

- `index.html` — the interactive version (sorting game, a "find your broom handle" prompt, and a quiz)
- `reading.html` — the same article with the activities removed, for straight reading or printing

Both files are fully self-contained. No build step, no server, no dependencies, no tracking, and nothing is collected from the reader — the one activity that stores an answer keeps it in the reader's own browser and never sends it anywhere.

## Publishing

**GitHub Pages** — push this folder to a public repo, then Settings → Pages → Deploy from a branch → `main` / `/root`.

**Vercel** — import the repo, framework preset "Other", leave the build command empty and set the output directory to the folder containing these files. Or drag the folder onto the Vercel dashboard.

## License

CC BY-NC-SA 4.0. See `LICENSE`. Translations are welcome and encouraged.
