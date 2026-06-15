# DOMUS novio Auswahlseite

Kleine statische Auswahlseite fuer QR-Code- und NFC-Aufrufe. Besucher waehlen zwischen einem Terminformular und einer Effizienzanalyse und werden anschliessend zum passenden fluks-Formular weitergeleitet.

## Links ersetzen

Aktuell sind Stage-Links hinterlegt. Beim Wechsel auf Prod muessen in `index.html` diese beiden `href`-Werte ersetzt werden:

- Button `Termin buchen`: aktueller Stage-Link beginnt mit `https://forms.fluks.cloud/?sig=...`
- Button `Effizienzanalyse starten`: aktueller Stage-Link beginnt mit `https://forms.fluks.cloud/?sig=...`

## GitHub Pages

GitHub Pages ist fuer den Branch `main` aus dem Root-Verzeichnis vorgesehen. Die Seite wird direkt aus `index.html` ausgeliefert.

## Logo

Die Logo-Dateien liegen im Root-Verzeichnis neben `index.html`:

- `logo-domus-novio.png`
- `logo-domus-innovation-days-2026.png`

Die Logos werden in der Seite mit relativen Pfaden eingebunden:

```html
<img src="./logo-domus-novio.png" alt="DOMUS novio Logo">
<img src="./logo-domus-innovation-days-2026.png" alt="DOMUS Innovation Days 2026 Logo">
```

## Spaetere Aenderungen veroeffentlichen

1. Gewuenschte Datei lokal bearbeiten.
2. Aenderung committen.
3. Branch `main` zu GitHub pushen.
4. GitHub Pages veroeffentlicht die aktualisierte Version automatisch.
