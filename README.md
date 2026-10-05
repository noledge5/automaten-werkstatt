# Automaten-Werkstatt

Zustandsautomaten zeichnen, ausprobieren und automatisch prüfen lassen. Gedacht für den Informatikunterricht
(Klasse 10, Modul „Automaten“), läuft komplett im Browser: auf Schulrechnern, Tablets und Handys.

## Benutzen

- **Bauen:** „+ Zustand“, Zustände verschieben, mit dem Werkzeug „Pfeil ziehen“ Übergänge zeichnen. Pro Pfeil
  werden Eingabe und Ausgabe gewählt. Zweimal auf denselben Zustand tippen erzeugt eine Schleife.
- **Testen:** Bedienfeld mit Eingängen (Taster) und Ausgängen (Lampen). Zeigt Zustand, Anzahl der Eingaben und
  Ausgaben und ein Protokoll.
- **Prüfen:** Vergleicht das Verhalten mit der Musterlösung (nicht die Zeichnung). Zustandsnamen sind frei wählbar.
  Bei Abweichung zeigt eine Tabelle die erste Eingabefolge, bei der es schiefgeht.
- **Hinweise** unter der Zeichnung: mehrdeutige Pfeile, Sackgassen, unerreichbare Zustände.

## Direktlinks zu Aufgaben (für QR-Codes)

Adresse der Seite plus `?a=` und die Kennung:

| Kennung | Aufgabe |
|---|---|
| `becher` | Becher-O-Mat nachbauen |
| `lampe` | Taschenlampe |
| `alarm` | Alarmanlage |
| `umbau1`, `umbau2`, `umbau3` | Becher-O-Mat reparieren (drei Fehlerarten) |
| `schranke` | Parkschranke |
| `ampel` | Fußgängerampel |
| `fahrstuhl` | Fahrstuhl |
| `schloss` | Zahlenschloss |
| `frei` | Eigener Automat |

Beispiel: `https://DEIN-KONTO.github.io/automaten-werkstatt/?a=becher`

## Eigene Aufgaben teilen

Aufgabe „Eigener Automat“ öffnen, Eingaben und Ausgaben festlegen, den Automaten als Musterlösung zeichnen,
unter „Als Aufgabe teilen“ Titel und Text eintragen und „Link erzeugen“ drücken. Der Link enthält die ganze
Aufgabe (und damit auch die Musterlösung). Es wird nichts auf einem Server gespeichert.

## Datenschutz

Es werden keine Daten an Server gesendet und keine fremden Dateien nachgeladen (die Schrift ist eingebettet).
Zeichnungen, Vorname und Fortschritt bleiben im Browser des jeweiligen Geräts (localStorage). Es gibt keine
Auswertung für die Lehrkraft.

## Veröffentlichen mit GitHub Pages

1. Neues Repository anlegen (z. B. `automaten-werkstatt`, öffentlich).
2. Die Dateien `index.html` und `README.md` hochladen (Add file, Upload files).
3. Settings, Pages: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`, speichern.
4. Nach etwa einer Minute ist die Seite unter `https://DEIN-KONTO.github.io/automaten-werkstatt/` erreichbar.

## Lizenzhinweis

Die eingebettete Schrift Carlito steht unter der SIL Open Font License 1.1.
