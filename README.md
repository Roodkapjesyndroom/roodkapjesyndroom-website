# De wolf, de mens en het Roodkapjesyndroom — website

Statische website (platte HTML/CSS, geen build-stap nodig) van 3 pagina's voor het boek van Marc van der Sterren.

## Bestandsstructuur

```
index.html          → Home
over.html            → Over het boek & de schrijver
nieuwsbrief.html     → Nieuwsbrief-pagina
styles.css           → Gedeelde opmaak voor alle pagina's
assets/              → Alle afbeeldingen (webp, geoptimaliseerd)
```

## Uploaden naar GitHub (voor IONOS Deploy Now)

1. Maak op github.com een nieuwe **repository** aan (bijv. `roodkapjesyndroom-website`).
2. Klik op **Add file → Upload files**.
3. Sleep **alle bestanden en de hele `assets`-map** in één keer naar het uploadvak — zorg dat `index.html` direct in de hoofdmap van de repository staat, niet in een submap.
4. Klik op **Commit changes**.
5. Koppel deze repository in IONOS Deploy Now als **Static Project**.

## Later bijwerken

Wil je later tekst aanpassen?

1. Open het bestand (bijv. `over.html`) in een teksteditor, pas de tekst aan, sla op.
2. Upload dat ene bestand opnieuw naar dezelfde GitHub-repository — je kunt het bestaande bestand direct overschrijven via **Add file → Upload files** (GitHub vraagt of je het wilt vervangen) of via **potloodicoontje bij het bestand → bewerken**.
3. IONOS Deploy Now merkt de wijziging automatisch op en publiceert binnen enkele minuten de nieuwe versie. Je hoeft verder niets te doen bij IONOS zelf.

Geen kennis van Git-commando's nodig — alles kan via de GitHub-website in de browser.
