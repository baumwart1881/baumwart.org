# baunwart.org

Website für Baumwart Alb, als statische GitHub-Pages-Seite vorbereitet.

## Struktur
- `index.html` = aktive Startseite
- `17.10.26.html` = früherer Entwurf / Vorschau
- `Website` und `Website 16.10.` = alte Versionen

## Lokal testen
```bash
cd /pfad/zu/baunwart.org
python3 -m http.server 8000
```
Danach im Browser:
```text
http://localhost:8000/
```

## GitHub Pages aktivieren
1. In GitHub auf `Settings` → `Pages`
2. Source: `Deploy from a branch`
3. Branch wählen: `in-Arbeit` oder `main`
4. Folder: `/ (root)`
5. Save

## Wichtiger Hinweis zur Domain
Für eine eigene Domain musst du später eine Datei `CNAME` erstellen mit genau deiner Domain, zum Beispiel:
```text
baumwart-alb.de
```
Danach DNS einrichten:
- Apex-Domain: A-Records auf die GitHub Pages IPs
- Subdomain www: CNAME auf `baumwart1881.github.io`

## Nächster Schritt
Wenn du deine echte Domain schickst, ergänze ich dir direkt die genaue `CNAME`- und DNS-Anleitung für genau deinen Fall.
