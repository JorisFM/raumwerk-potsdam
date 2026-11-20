# Raumwerk – Referenzwebseite

Statische Fake-Referenzseite für ein Innenarchitektur-Studio aus Potsdam (fiktive Daten).
Reines HTML/CSS/JS, kein Build-Schritt. Live über GitHub Pages.

## Struktur
- `index.html` – Startseite (Hero, Tabs-Leistungen, Projekt-Vorschau, Prozess, Testimonials, Journal)
- `projekte.html` – 6 Fallstudien (bewusst NICHT klickbar, nur zum Anschauen)
- `leistungen.html`, `ueber-uns.html` (nur die zwei Gründer), `kontakt.html`
- `impressum.html`, `datenschutz.html`
- `style.css`, `script.js` – geteilt von allen Seiten
- Bilder: Unsplash-URLs (images.unsplash.com), nur Innenraum-Motive verwenden

## Workflow (immer so)
1. Änderungen an den Dateien vornehmen
2. Lokal prüfen (index.html im Browser öffnen)
3. `git add -A && git commit -m "<kurze Beschreibung>" && git push`
4. GitHub Pages deployt automatisch vom Branch `main` (Root) – nach ca. 1 Minute live

## Konventionen
- Sprache der Seite: Deutsch
- Kein eigener Cursor-Effekt (wurde bewusst entfernt)
- Firmendaten konsistent halten: Raumwerk Innenarchitektur GmbH, Brandenburger Straße 42, 14467 Potsdam, +49 331 270 89 45, studio@raumwerk-potsdam.de, HRB 31427 P
