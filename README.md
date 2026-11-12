# Geo Master

A mobile-first geography learning app. Memorize all 195 countries: capitals, continents, flags and where they are on the map.

- **Map**: explore, find the country, find the continent, name the highlighted country
- **Flashcards**, **Quiz** (4 choices), **Type-it** (typo-tolerant)
- **Spaced repetition** (Leitner boxes): missed cards come back sooner
- Hints, stats and trophies
- Progress is saved in your browser (use Settings to back it up)

No build step: it is a single `index.html` plus a manifest and service worker, so it installs to your phone's home screen and keeps working offline after the first load.

Map shapes come from the Datamaps world topology (cdnjs). Flags come from the `country-flag-icons` package (jsDelivr). If either cannot load, the app falls back to a dot map and emoji flags.
