# Lernzentrale

Kleine Lernspiele für die Schule, gebaut für Tablet und Handy. Jedes Spiel behandelt ein Thema aus dem Unterricht, zum Beispiel ein Wortfeld in Deutsch.

**Zur Lernzentrale:** https://breitec.github.io/lernzentrale/

## Spiele

- **[Erd-Atlas](https://breitec.github.io/lernzentrale/2026-11_Geographie-Erde-Sonnensystem-Klima/)** – Geographie: Kopernikus, Sonnensystem, Besonderheiten der Erde und Treibhauseffekt.
- **[Sagen-Sonne](https://breitec.github.io/lernzentrale/2026-10_Wortfeld-Sagen/)** – Deutsch, Wortfeld „sagen“: 62 Verben kennenlernen, abfragen und in Sätze einsetzen.
- **[Vokabel-Bus](https://breitec.github.io/lernzentrale/2026-10_Englisch-Vokabeln/)** – Englisch, Vokabeln aus dem Heft: 168 Wörter und Sätze hören, nachsprechen und schreiben, dazu das Alphabet.
- **[Bio-Labor](https://breitec.github.io/lernzentrale/2026-10_Biologie-Lebewesen-Zellen-Sinne/)** – Natur und Technik, Biologie: Kennzeichen von Lebewesen, Zellen, Sinnesorgane und Reiz-Reaktions-Kette.

## Auf dem iPad oder iPhone einrichten

1. Die Lernzentrale in Safari öffnen.
2. Auf „Teilen“ tippen, dann „Zum Home-Bildschirm“.
3. Die Lernzentrale startet danach wie eine App. In jedem Spiel führt „‹ Lernzentrale“ zurück zur Übersicht.

## So funktionieren die Spiele

- Jedes Spiel hat mehrere Stufen: erst kennenlernen (Karteikarten), dann abfragen, dann anwenden (z. B. Lückensätze).
- Ein Begriff gilt als gelernt, wenn er dreimal hintereinander richtig beantwortet wurde. Ein Fehler setzt ihn zurück, Begriffe mit Fehlern kommen öfter dran.
- Bei einer falschen Antwort zeigt das Spiel sofort die richtige Lösung mit Erklärung und Beispiel.
- Punkte, Serien, Sterne und eine Fortschrittsanzeige pro Heft sorgen für Motivation. Zeitdruck gibt es nur in der freiwilligen Blitzrunde.
- Ein Elternbereich in jedem Spiel zeigt die schwierigsten Begriffe und kann den Fortschritt zurücksetzen.

## Datenschutz

- Kein Konto, keine Anmeldung, kein Tracking, keine Cookies.
- Der Spielstand liegt nur im Browser des jeweiligen Geräts (`localStorage`) und wird nirgends hingeschickt. iPad und iPhone haben deshalb getrennte Spielstände.
- Keine Verbindungen zu anderen Anbietern. Auch die Schriftarten (Andika und Playpen Sans, SIL Open Font License) liegen hier im Repository unter `fonts/`.
- Die Seiten sind für Suchmaschinen gesperrt (`noindex`).

## Aufbau

```
index.html              Lernzentrale (Übersicht aller Spiele)
icon.png                App-Symbol für den Home-Bildschirm
fonts/                  Schriftarten mit Lizenztexten (OFL)
JJJJ-MM_Thema/index.html  ein Spiel pro Ordner
```

Jedes Spiel ist eine einzige HTML-Datei mit eingebettetem CSS und JavaScript, ohne Build-Schritt und ohne Bibliotheken. Die Inhalte (Begriffe, Erklärungen, Beispielsätze) stehen als Datenliste direkt im Spiel.

Dieses Repository enthält nur die veröffentlichten Seiten. Erstellt und gepflegt werden sie lokal und mit einem Skript hierher übertragen. Änderungen direkt in diesem Repository werden beim nächsten Veröffentlichen überschrieben.

---

Erstellt von [Breitec](https://breitec.de) mit Unterstützung von Claude.
