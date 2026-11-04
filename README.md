# Mathe-Tierpark 🐾

Ein Lernspiel fürs Tablet: Mathe für die 4. Klasse und Englisch-Vokabeln für die 5. Klasse. Kinder üben kurze Runden mit 8 Aufgaben, sammeln Sterne und adoptieren damit 17 Tiere für ihren eigenen Tierpark, vom Hasen über den Wolf bis zum Einhorn.

**Spielen:** https://kuhtzlars-collab.github.io/mathe-tierpark/

## Übungsbereiche

| Bereich | Stufe 1 | Stufe 2 | Stufe 3 |
|---|---|---|---|
| 🐿️ Plus-Wald | bis 100 mit Zehnerübergang | über den Hunderter (470 + 260) | dreistellig (496 + 114) |
| 🐐 Minus-Berg | bis 100 mit Zehnerübergang | über den Hunderter (730 − 260) | dreistellig (503 − 388) |
| 🐄 Mal-Wiese | Einmaleins | mit Zehnerzahlen (40 · 7) | zweistellig mal einstellig (38 · 7) |
| 🦆 Teil-Teich | Einmaleins rückwärts | mit Zehnerzahlen (280 : 7) | großes Ergebnis (84 : 4) |

- Nach 5 richtigen Antworten hintereinander geht es eine Stufe höher, nach 2 verpassten Aufgaben hintereinander eine zurück.
- Beim ersten Fehler gibt es einen Tipp, beim zweiten den Rechenweg Schritt für Schritt.
- Aufgaben können vorgelesen werden.
- Wird ein neues Tier adoptiert, hüpft es in einer kleinen Animation durch das Tierpark-Tor zu den anderen Tieren.
- Unten auf der Startseite zeigt „Meine Tiere“ alle gesammelten Tiere mit Fortschrittsbalken und wie viele Sterne bis zum nächsten Tier fehlen.
- Im Bereich „Für Eltern“ sieht man den Fortschritt und kann die Stufe selbst einstellen.
- Für Plus und Minus lässt sich dort auch die Darstellung wählen: automatisch (Stufe 3 untereinander), immer hintereinander oder immer untereinander.
- Untereinander gibt es eine Zeile mit kleinen Kästchen für Merkzahlen (Übertrag), und das Ergebnis wird wie im Heft von rechts nach links eingetragen. Tipps und Rechenweg erklären Plus spaltenweise mit Übertrag und Minus im Ergänzungsverfahren.

## Englisch-Vokabeln (Klasse 5)

Auf der Startseite lässt sich zwischen **Mathe** und **Englisch** umschalten. Es gibt 9 Lektionen mit je 15 Vokabeln: Schule, Familie & Freunde, Zuhause, Freizeit, Essen & Trinken, Tiere, Farben & Kleidung, Zeit & Wetter, Wichtige Verben.

| Stufe | Abfrage |
|---|---|
| 1 | Englisch → Deutsch, aus 4 Antworten auswählen |
| 2 | Deutsch → Englisch, aus 4 Antworten auswählen |
| 3 | Deutsch → Englisch selbst schreiben |

- Beim Schreiben sind Groß- und Kleinschreibung und ein vorangestelltes „to“ bei Verben egal. Ist nur ein Buchstabe falsch, sagt die App „Ganz knapp!“.
- Nach jeder Antwort wird das englische Wort vorgelesen (wenn die Töne an sind).
- Wörter, die oft falsch waren, kommen häufiger dran.
- **Eigene Listen:** Unter „Neue Liste“ die Vokabelseite fotografieren. Die Texterkennung ([Tesseract.js](https://github.com/naptha/tesseract.js)) läuft direkt auf dem Gerät; beim ersten Mal lädt sie ihre Sprachdaten aus dem Internet. Danach kann man jede Zeile prüfen, verbessern, löschen oder ergänzen. Alternativ lassen sich Vokabeln eintippen oder einfügen („dog - Hund“, eine pro Zeile).
- Eigene Listen lassen sich im Bereich „Für Eltern“ bearbeiten oder löschen.

## Datenschutz

Der Fortschritt und eigene Vokabellisten werden nur im Browser des Geräts gespeichert (`localStorage`). Es gibt kein Konto. Fotos werden auf dem Gerät gelesen und nicht hochgeladen; nur die Texterkennung selbst und ihre Sprachdaten werden beim ersten Mal aus dem Internet geladen.

## Technik

Eine einzige Datei: `index.html` mit HTML, CSS und JavaScript, ohne Build-Schritt. Zum Ausprobieren die Datei einfach im Browser öffnen.

## Auf dem Tablet wie eine App nutzen

Die Spiel-Adresse im Browser öffnen und „Zum Startbildschirm hinzufügen“ wählen (Safari: Teilen-Menü, Chrome: Drei-Punkte-Menü).
