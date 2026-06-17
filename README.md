# Marabou Adventsveckor

Statisk Vercel-version av en kundagd Marabou-inspirerad adventskalender aktiverad av ClearOn.

- 4 veckoluckor
- 2000 kuponger per lucka
- Responsiv layout for mobil och desktop
- Preview-lage ar aktivt som standard sa alla luckor kan demonstreras
- Lagg till `?live=1` i URL:en for datumstyrd oppning vecka for vecka

## Deploy via GitHub och Vercel

1. Ladda upp innehållet i den här mappen till ett eget GitHub-repo.
2. Importera repot i Vercel som ett nytt projekt.
3. Lämna framework som `Other` / statisk site.
4. Build command kan vara tom.
5. Output directory kan vara tom eller `.`.

`vercel.json` är redan med och aktiverar clean URLs.
