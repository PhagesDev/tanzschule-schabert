# Tanzschule Schabert – Beta Website

Statische Beta-Seite für GitHub Pages.

## Start lokal testen

Einfach `index.html` im Browser öffnen.

Besser mit lokalem Server:

```bash
python -m http.server 8000
```

Dann öffnen:

```txt
http://localhost:8000
```

## GitHub Pages

1. Repo erstellen
2. Alle Dateien aus diesem Ordner hochladen
3. Repository → Settings → Pages
4. Source: Deploy from branch
5. Branch: main
6. Folder: /root
7. Speichern

## Bilder ändern

Bilder liegen unter:

```txt
assets/images/
```

Wenn du Dateinamen änderst, musst du sie in `index.html` anpassen.

## Logo ändern

Logo liegt unter:

```txt
assets/logo/logo-black.png
```

## Wichtig

Für echtes Kontaktformular braucht GitHub Pages einen externen Dienst wie Formspree, Netlify Forms oder ein eigenes Backend.
Aktuell arbeitet die Anmeldung per `mailto:` Link.
