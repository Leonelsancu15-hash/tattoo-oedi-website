# Tattoo Oedi – Website

Statische Website, keine Abhängigkeiten, kein Build nötig.

**Live:** https://leonelsancu15-hash.github.io/tattoo-oedi-website/ · Repo: https://github.com/Leonelsancu15-hash/tattoo-oedi-website (Dateien dort flach mit Präfixen `img-`, `fonts-`, `video-`)

In diesem Repository liegen alle Dateien flach im Hauptverzeichnis (Präfixe `img-`, `fonts-`, `video-`, `vendor-`), weil sie über den GitHub-Web-Upload eingespielt wurden. Die Original-Struktur mit Unterordnern liegt im Obsidian Vault unter `Projekte/tattoo-oedi-website/`.

## Inhalt

| Datei / Ordner | Zweck |
|---|---|
| `index.html` | Die komplette Seite (HTML, CSS, JS in einer Datei) |
| `impressum.html` | Impressum + Datenschutz – **Platzhalter vor Livegang ausfüllen** (rot markiert) |
| `img-*.webp` | Galerie-Bilder als WebP in 640 px und 1200 px, Hero-Bild in 900/1600 px |
| `video-*` | 6-Sekunden-Clip vom Stechen (stumm, Loop) + Poster |
| `fonts-*` | Archivo und IBM Plex Mono, lokal eingebunden (SIL Open Font License) |

## Vor dem Livegang

1. `impressum.html`: Nachname, Anschrift, E-Mail, Umsatzsteuer-Angabe, Hosting-Anbieter eintragen.
2. Studio-Adresse: In `index.html` nach `Adresse folgt` suchen und ersetzen (Abschnitt Kontakt).
3. `og:image` in `index.html` zeigt auf `img/loewe-blumen-1200.webp` – für Social-Media-Vorschau ggf. absolute URL eintragen, sobald die Domain steht.

## Anfrage-Formular

Das Formular sendet nichts an einen Server. Beim Absenden wird WhatsApp mit einer fertigen Nachricht an **+49 163 8462849** geöffnet (Motiv, Körperstelle, Größe, Stil, Cover-up). Nummer ändern: in `index.html` nach `491638462849` suchen (3 Stellen).

## Bilder austauschen oder ergänzen

Galerie-Kacheln sind `<figure data-cat="bg|fl|an">` im Abschnitt `#portfolio`. Pro Bild zwei WebP-Größen (640 und 1200 px breit, Format 4:5) ablegen und einen Block kopieren. `data-cat`: `bg` = Black & Grey, `fl` = Fineline, `an` = Anime. Alt-Text bitte beschreibend halten – er ist auch die Bildunterschrift in der Großansicht.

## Erstellt

06.09.2026 mit den Skills aus `~/Desktop/agent-skills` (build-awwwards-quality-sites, editorial-portfolio-chapters, landing-page, staggered-word-reveal, animation-on-scroll, number-details, css-alpha-masking, solar-duotone-bold, company-logos, no-ai-design-slop, audit-ai-design-slop).
