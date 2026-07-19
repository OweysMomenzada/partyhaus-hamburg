# Partyhaus Hamburg – Website

Landing page für **Partyhaus Events & Catering**, Eventlocation und internationales
Catering in Hamburg (Hochzeiten, Abibälle, Verlobungen, Firmenfeiern – seit 2006).

Die gesamte Seite ist eine einzige, eigenständige `index.html`: HTML, CSS und
JavaScript sind inline. Kein Build-Schritt, keine Abhängigkeiten, kein Framework –
einfach die Datei im Browser öffnen oder per GitHub Pages ausliefern.

## Dateien

| Datei | Zweck |
| --- | --- |
| `index.html` | Komplette Website (Struktur, Styles, Skripte) |
| `partyhaus-hero.mp4` | Hintergrundvideo im Hero-Bereich |
| `partyhaus-hero-poster.jpg` | Standbild, bis das Video geladen ist |

> Fehlt das Video, blendet die Seite es automatisch aus und zeigt stattdessen
> das Hintergrundbild – die Seite bleibt also immer funktionsfähig.

## Lokal ansehen

Datei direkt im Browser öffnen:

```bash
open index.html
```

Oder mit einem kleinen lokalen Server (empfohlen, damit relative Pfade sauber laden):

```bash
python3 -m http.server 8000
# dann http://localhost:8000 im Browser öffnen
```

## Veröffentlichen mit GitHub Pages

1. Repository auf GitHub anlegen und diesen Ordner pushen.
2. **Settings → Pages** öffnen.
3. Unter *Build and deployment* → *Source* **„Deploy from a branch"** wählen.
4. Branch **`main`** und Ordner **`/ (root)`** auswählen, speichern.
5. Nach kurzer Zeit ist die Seite unter
   `https://<benutzername>.github.io/<repository>/` erreichbar.

## Vor dem Live-Gang anpassen

- In `index.html` die Platzhalter-URLs `https://www.partyhaushamburg.com/`
  (in `canonical`, Open Graph und JSON-LD) auf die tatsächliche Adresse setzen.
- Im Impressum die **USt-IdNr.** ergänzen und die Rechtstexte
  (Impressum & Datenschutz) juristisch prüfen lassen.
