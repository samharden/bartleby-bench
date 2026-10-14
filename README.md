# Bartleby Bench

Three AI models were given the same prompt:

> Create a playable web-based rpg with melee and ranged attacks, character classes, and quests, all based on the classic tale of Bartleby the Scrivener

Each produced a single self-contained HTML file. They're collected here, unedited, so anyone can play them side by side.

**Play them:** https://samharden.github.io/bartleby-bench/ (or open any `games/*/index.html` locally in a browser).

| Model | Game | Original filename |
| --- | --- | --- |
| Argon | [Bartleby, the Scrivener: Chronicles of Wall-Street](games/argon/index.html) | `gemini-code-1791942189014.html` |
| Opus 5.5 | [Bartleby of Wall Street](games/opus-5.5/index.html) | `Bartleby of Wall Street.html` |
| Sol 6.1 | [Bartleby · The Dead Letter Office](games/sol-6.1/index.html) ([model's notes](games/sol-6.1/README.md)) | `dist/index.html` |

## Layout

```
index.html            landing page linking to all three
assets/               title-screen screenshots for the landing page
games/<model>/        each model's game, renamed to index.html
.nojekyll             serve files as-is on GitHub Pages
```

The game files are byte-for-byte the models' output; only their names and folders changed.
