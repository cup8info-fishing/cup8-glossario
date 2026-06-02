# cup8-glossario — CDN pubblico del glossario ittico

Pacchetto **pubblicato** delle schede pesce di cup8, servito via GitHub Pages.
È **generato automaticamente** da Atlas (CMS) quando una scheda viene marcata
"Pronto / Pubblica" — non modificare a mano.

## Struttura
- `glossario/index.json` — lista delle specie pubblicate (id, nome, scientifico, cover)
- `glossario/<slug>.json` — scheda completa (formato `FishSpecies` dell'app)
- `glossario/<slug>/*.png` — immagini della specie

## Consumatori
- App **cap8** (glossario ittico) — fetch + fallback offline
- Sito **cup8** (glossario / tutti-i-pesci)

URL base: `https://cup8info-fishing.github.io/cup8-glossario/`
