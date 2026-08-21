# machinezr

Gamer, Coder, Bastler — Windows-Apps die ich selber nice finde.

## Struktur

```
├── index.html              ← Hauptseite (Netlify startet hier)
├── 404.html                ← Eigene 404-Seite (Netlify serviert sie automatisch)
├── robots.txt              ← Crawler-Regeln + Sitemap-Referenz
├── sitemap.xml             ← Sitemap für Suchmaschinen
├── assets/
│   ├── img/
│   │   ├── Machine Logo.png
│   │   ├── steam.webp
│   │   └── projects/       ← App-Screenshots
│   └── ...
├── netlify.toml             ← Netlify-Konfig
├── .gitignore
└── README.md
```

## Deployment (Netlify)

1. Repo auf GitHub pushen: `git push origin main`
2. Auf [Netlify](https://netlify.com) anmelden
3. **"Add new site" → "Import an existing project"**
4. GitHub verbinden und `AlexSch95/Machinezr` auswählen
5. **Fertig** — keine Build-Einstellungen, kein `npm`, nichts.
   Netlify erkennt automatisch `index.html` im Root.

👉 Live unter: `https://machinezr.netlify.app` (oder eigener Domain)

## Lizenz

MIT — mach damit was du willst 🤘