# Minecraft Spanish Cards Deck

A personalized 40-card Spanish deck for Truco, with Minecraft-inspired artwork and a matching card back.

[View the deck](https://biancamzullo.github.io/Minecraft-Spanish-Cards-Deck/)

The responsive grid contains all four suits—Espadas, Bastos, Oros, and Copas—with ranks 1–7 and 10–12, plus one back design. Each card measures 65 × 95 mm and uses the Fira Code font.

Fira Code is bundled locally with its dotted-zero variant enabled for card numbers. The font's SIL Open Font License is included in `fonts/OFL.txt`.

## Local preview

Run this command from the repository directory:

```sh
python3 -m http.server 8765
```

Open <http://localhost:8765/> in a browser. The page needs no build step. Its CSS is embedded in `index.html`, and all artwork lives alongside that file. Some SVG assets contain embedded PNG artwork.

## Publishing

GitHub Pages publishes the repository root from the `main` branch. `.nojekyll` keeps the site as plain static files.

For physical-size printing, use 100% scale and enable background graphics in the browser print settings.
