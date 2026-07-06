# 📚 Lesestube

Eine kleine Progressive-Web-App, die Fotos (per Texterkennung), PDFs oder eigenen Text in ein Buch zum Lesen verwandelt – mit Umblätter-Animation, mehreren Themes (Papier/Sepia/Modern), Suche, Notizen, Kapitel-Erkennung und Vorlesen.

Läuft komplett im Browser, keine Anmeldung, keine Server-Datenbank – alle Bücher werden lokal auf dem Gerät gespeichert (`localStorage`).

## Live-Version

👉 **https://andrejblentovic.github.io/Buchapp/**

## Dateien in diesem Projekt

| Datei | Zweck |
|---|---|
| `index.html` | Die komplette App (HTML, CSS, JavaScript in einer Datei) |
| `manifest.json` | PWA-Manifest – ermöglicht "Zum Home-Bildschirm hinzufügen" mit eigenem Icon |
| `sw.js` | Service Worker für grundlegende Offline-Fähigkeit |
| `icon-192.png` / `icon-512.png` | App-Icons für Home-Bildschirm und Store-Darstellung |

## Funktionen

- 📷 Foto → automatische Texterkennung (Claude Vision, mit Tesseract.js als Fallback)
- 📄 PDF → Text automatisch ausgelesen (inkl. OCR-Fallback für gescannte Seiten)
- ✍️ Eigenen Text direkt einfügen/eintippen
- 🔖 Umblättern (3D-Animation) oder Scroll-Modus
- 📜 Drei Lese-Themes: Papier, Sepia, Modern (inkl. automatischer Dark Mode)
- 🔍 Volltextsuche im Buch
- 📝 Notizen pro Seite
- ☰ Automatische Kapitel-Erkennung
- 🔊 Vorlesen (Text-to-Speech)
- 🗂️ Kategorien, Sortierung, eigenes Foto als Cover
- ⇅ Backup/Export & Wiederherstellen (JSON-Datei)

## Aktualisieren

Um die App zu aktualisieren: einfach die neue `index.html` über **Add file → Upload files** hochladen (überschreibt die alte). GitHub Pages veröffentlicht die Änderung automatisch innerhalb von 1–2 Minuten.

## Lizenz / Nutzung

Privates Projekt für den persönlichen Gebrauch.
