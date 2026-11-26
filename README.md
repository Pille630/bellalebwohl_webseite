# bellalebwohl – Webseite

One-Page-Website der Band bellalebwohl (Ska & Folkpunk, Stuttgart). Reines HTML/CSS/JS, keine Build-Schritte, keine externen Dienste beim Laden (DSGVO).

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Die Startseite (Inhalt, Design und Skripte in einer Datei) |
| `impressum.html`, `datenschutz.html`, `legal.css` | Rechtstexte (gelbe `<mark>`-Platzhalter vor dem Livegang ausfüllen!) |
| `404.html` | Fehlerseite |
| `robots.txt`, `sitemap.xml` | Für Suchmaschinen |
| `logo.png`, `favicon.*`, `apple-touch-icon.png` | Logo und Tab-Symbol |
| `bandfoto.jpg` | Foto in der Box „Band" |
| `galerie1.jpg` … `galerie4.jpg` | Galerie (aktuell in `index.html` mit `hidden` verborgen) |
| `vorschau.jpg` | Vorschaubild für Link-Vorschauen (1200×630 px) |
| `hero.mp4` | Hintergrundvideo der ersten Box (ohne Ton, ca. 1–3 MB) |
| `01_Bellalebwohl_Pressetext_250921.pdf`, `Bellalebwohl_Pressebilder.zip` | Downloads im Bereich „Presse" |
| `fonts/` | Schrift Knewave (lokal, mit Lizenz) |

## Häufige Änderungen

- **Foto/Video austauschen:** Datei mit dem gleichen Namen auf GitHub hochladen (Add file → Upload files), sie ersetzt die alte.
- **Termine:** In `index.html` die Liste `TERMINE` bearbeiten (Datum `TT.MM.JJJJ`, Zeit, Ort, Info, Tag, optional Link). Vergangene Termine verschwinden automatisch.
- **Video auf der Seite:** In `index.html` bei `data-video-id` die YouTube-ID austauschen.
- **Galerie einblenden:** In `index.html` beim Abschnitt `id="galerie"` das Wort `hidden` entfernen.

## Kontakt

Booking & allgemeine Anfragen: **kontakt@bellalebwohl.de**
