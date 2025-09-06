# Edwin – Bilder & Beschreibungen

Dieses Repository dient dazu, einzelne Bilder (Öl auf Leinwand) mit jeweils eigener Markdown-Beschreibung zu verwalten und – wenn gewünscht – über GitHub Pages als kleine Website anzuzeigen.

## Ordnerstruktur
- `images/` – hier kommen die Bilddateien (JPG/PNG) hinein.
- `beschreibungen/` – hier liegt zu jedem Bild eine `.md`-Datei mit der Beschreibung.
- `templates/` – Vorlagen, z.B. die Markdown-Vorlage für eine Bildbeschreibung.

## Dateibenennung (Empfehlung)
- Bild: `70x50_04242.jpg`
- Beschreibung: `70x50_04242.md` (identischer Stammname wie das Bild!)

## Minimaler Workflow (ohne Kommandozeile)
1. Auf GitHub **neues Repository** erstellen (z.B. `edwin-bilder`).
2. Die Inhalte dieses Starter-Kits hochladen (drag & drop im GitHub-Webinterface).
3. Für jedes Bild:
   - Datei in `images/` hochladen.
   - Dazu passende `.md`-Datei in `beschreibungen/` anlegen (siehe Vorlage in `templates/`).
4. Änderungen **Committen** (Speichern).

## Optional: GitHub Pages aktivieren
- In den **Repository Einstellungen** → **Pages** → Source auf `main` (oder `master`) und Root setzen.
- Die Datei `index.md` ist bereits vorhanden und verlinkt alle Beschreibungen.

## Git LFS (optional, empfohlen für große Bilder)
- Git LFS lokal installieren und im Repo aktivieren, wenn du sehr große Bilddateien speicherst (siehe `.gitattributes`).

Viel Erfolg!