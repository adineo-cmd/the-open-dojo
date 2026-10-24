# The Open Dojo — a free martial arts reference library

A pure-static, 15-page martial arts reference site: no frameworks, no build step, no tracking. Open `index.html` in a browser and it works.

## The library

| Page | Contents |
|---|---|
| `index.html` | Home — section cards, featured styles, kata spotlight, home-dojo guide, book shelf |
| `styles.html` | ~139 martial arts catalogued by region and method |
| `profiles.html` | 28 major arts in depth — history, typical classes, famous figures |
| `kata.html` | Kata & forms tables: Shotokan, Shito-Ryu, Goju-Ryu, Taegeuk, ITF patterns, Tang Soo Do, judo & kobudo kata, Chinese taolu |
| `techniques.html` | 20 technique groups: stances, guards, footwork, strikes, kicks, clinch, throws, pins, submissions, ukemi |
| `terminology.html` | Counting, commands, ranks, and vocabulary in Japanese, Korean, and Chinese |
| `glossary.html` | A–Z glossary of terms from every art |
| `ranks.html` | Belt history, kyu & dan systems, promotion methods, dojo etiquette |
| `sparring.html` | Formats, scoring, and gear across the arts |
| `self-defense.html` | Awareness, de-escalation, escapes, and the law |
| `weapons.html` | Kobudo, sword arts, Filipino, Chinese, and European weapons |
| `history.html` | Regional timelines, warrior codes, dō vs jutsu, modern era |
| `fitness.html` | Conditioning, injury prevention, training circuits |
| `syllabi.html` | Representative curricula: taekwondo kups, BJJ white→blue, judo kyu ladder |
| `search.html` | Client-side search over ~330 library entries |

## Running it

No dependencies. Either open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

Fonts (Source Serif 4, IBM Plex Sans, Noto Serif JP) load from Google Fonts when online, with system fallbacks offline.

## Notes

- All reference content is original writing built on factual, historical data.
- The safety note applies everywhere: this is information, not instruction — train under qualified supervision.
- © 2026 The Open Dojo.
