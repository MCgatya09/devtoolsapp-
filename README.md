# DevTools App

Ingyenes, kliensoldali fejlesztői eszköztár. Minden feldolgozás a böngészőben történik — az adataid soha nem hagyják el az eszközödet.

🔗 **Éles oldal:** [https://devtoolsapp.com](https://devtoolsapp.com)

## 🛠️ Eszközök

| Eszköz | Leírás |
|--------|--------|
| JSON Formatter | Formázás, validálás, szintaxis kiemelés |
| JSON ↔ XML | Kétirányú konvertálás |
| Base64 | Szöveg és fájl kódolás/dekódolás |
| URL Encode/Decode | URL komponensek kódolása |
| UUID v4 Generator | Véletlenszerű UUID generálás |
| JWT Decoder | Token header és payload dekódolás |
| Regex Tester | Valós idejű regex tesztelés |
| Markdown Preview | GitHub-stílusú élő előnézet |

## 🌍 Nyelvek

- 🇭🇺 Magyar (alapértelmezett)
- 🇬🇧 Angol (`/en/` path prefix)

## 🚀 Technológiák

- 100% kliensoldali (nincs backend)
- Path-alapú routing (`/jsonformatter`, `/base64` stb.)
- Automatikus SEO meta tag frissítés tool-váltáskor
- JSON-LD Structured Data
- Hreflang támogatás
- Autosave (localStorage)
- PWA-ready

## 📁 Projekt struktúra

```
├── index.html      # Fő alkalmazás (SPA)
├── vercel.json     # Vercel rewrite szabályok
├── robots.txt      # Keresőmotor crawler irányelvek
├── sitemap.xml     # URL térkép (8 eszköz × 2 nyelv)
└── README.md       # Ez a fájl
```

## 📝 Deploy

A projekt automatikusan deploy-olódik Vercel-re minden GitHub push-nál.

## 🔒 Adatvédelem

Minden feldolgozás helyben, a böngésződben történik. Semmilyen adat nem kerül elküldésre szerverre.
