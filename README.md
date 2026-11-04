# tfblanken.com

Statische versie van mijn website, gehost via GitHub Pages. Geen WordPress, geen database, geen plugins.

## Iets aanpassen (in de browser)

1. Open het bestand op github.com (zie de lijst hieronder).
2. Klik rechtsboven op het potloodje (*Edit this file*).
3. Pas de tekst aan en klik op **Commit changes**.
4. Na ongeveer een minuut staat de wijziging live.

Elke pagina heeft een blok tussen
`<!-- ============ PAGE CONTENT STARTS HERE ============ -->` en `... ENDS HERE ...`.
Alleen dat stuk hoef je aan te passen. Menu en opmaak staan erbuiten en zijn op alle pagina's gelijk.

| Pagina | Bestand |
|---|---|
| Home | `index.html` |
| About | `about/index.html` |
| Papers | `papers/index.html` |
| Presentations | `presentations/index.html` |
| Media | `media/index.html` |
| Projects | `projects/index.html` |
| Network Intervention Analysis | `network-intervention-analysis/index.html` |
| GIN (placeholder) | `gin/index.html` |
| Psychological Systems (placeholder) | `psych-systems/index.html` |
| Opmaak (kleuren, lettertypen) | `assets/css/style.css` |

## Veelvoorkomende klussen

**Nieuwe publicatie toevoegen**: in `papers/index.html`, onder het juiste jaartal, een regel kopiëren en aanpassen:

```html
<p>Achternaam A, <strong>Blanken TF</strong>, et al. Titel van het artikel. <em>Tijdschrift</em> 2026; 1: 1-10. <a href="https://doi.org/..." target="_blank" rel="noopener">[PDF]</a></p>
```

Voor een nieuw jaar kopieer je een heel blok (`<h2 class="section">2026</h2>` plus de `<div class="text">...</div>` eronder).

**Nieuw CV**: upload de nieuwe PDF in de map `cv/` met precies dezelfde naam `CV_TFBlanken.pdf`
(*Add file → Upload files*). De link op de About-pagina blijft dan werken. Pas eventueel de datum aan in `about/index.html` ("updated September 2026").

**Nieuwe afbeelding**: upload hem in `assets/img/` en verwijs ernaar met `/assets/img/bestandsnaam.jpg`.

**Nieuwe kaart (media, presentations, projects)**: kopieer een bestaand `<a class="card" ...> ... </a>`-blok en pas link, afbeelding, titel en tekst aan.

**Placeholderpagina invullen**: in `gin/index.html` en `psych-systems/index.html` staan `<!-- TODO -->`-opmerkingen op de plekken waar tekst, publicaties en presentaties moeten komen. Vervang "More information about this project will follow soon." en "Coming soon." door je eigen tekst. Wat tussen `<!--` en `-->` staat, is onzichtbaar op de site.

## Technisch

- `CNAME` bevat het domein (tfblanken.com). Niet verwijderen.
- `.nojekyll` zorgt dat GitHub de bestanden ongewijzigd publiceert.
- Lettertype Roboto staat zelf in `assets/fonts/`, dus er gaan geen verzoeken naar Google.
- `404.html` is de pagina voor links die niet bestaan.
