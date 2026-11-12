# Prospekterat

Grundläggande hemskalskalkyllare för prospekterat.se.

## Vad finns här

- `index.html` med en enkel startsida
- `styles.css` med ett grundtema inspirerat av Kugghuset-stilen
- `logo-emblem.svg`, `favicon.svg`, `favicon.ico` och `apple-touch-icon.png`
- `CNAME` för `prospekterat.se`

## Publicering

Sajten serveras av Caddy på ax42 från `/var/www/prospekterat` och publiceras
genom att filerna kopieras dit med `rsync`. Kontrollera efteråt med `curl`.
GitHub Pages används inte; workflow-filen i `.github/workflows/` publicerar
ingenting.
