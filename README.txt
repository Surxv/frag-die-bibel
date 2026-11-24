# Frag die Bibel – erste Testversion

## Enthalten
- `index.html`: App-Oberfläche und Demo-Interaktionen
- `manifest.json`: Einstellungen für die Installation als Web-App
- `sw.js`: einfacher Offline-Cache

## Wichtig
Dies ist ein Frontend-Prototyp. Die Schaltfläche zeigt eine vorbereitete Demo-Antwort,
keine echte KI-Antwort. Es werden noch keine vollständigen Bibeltexte eingebunden.
Vor einer Veröffentlichung müssen die Nutzungsrechte der gewählten Bibelausgabe
und die Herkunft/Genauigkeit aller Bibelzitate geprüft werden.

## Online stellen
Die Dateien müssen auf einem HTTPS-Webhosting veröffentlicht werden. Danach kann
die Seite in Safari auf dem iPhone geöffnet und über „Teilen“ → „Zum Home-Bildschirm“
hinzugefügt werden.

## Nächste technische Schritte
1. Sichere Server-Funktion für KI-Anfragen einrichten.
2. KI-Schlüssel ausschließlich serverseitig speichern, niemals in `index.html`.
3. Eine rechtmäßig nutzbare und verlässliche Bibeltext-Datenquelle anbinden.
4. Antworten auf echte Versstellen prüfen und bei Unsicherheit keine Zitate erfinden.
5. Datenschutz, Altersangemessenheit und Löschfunktion prüfen.
