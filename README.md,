# SCHACH – KI Engine (Deep Chinese Model)

Dieses Projekt enthält eine vollständige Schach-KI, die ohne Benutzeroberfläche arbeitet.
Die Engine basiert auf einem chinesischen Deep-Modell, das durch Mirroring-Traversal und
Mitnahme-Effekte nicht verlieren kann.

## Struktur

core/
tmp/
docs/


### core/
Enthält die Engine-Dateien:

- chess.64 – Brettdefinition (64 Felder)
- chess.6d – 6D-Vektormodell
- chess.calc – Berechnungsmodul für KI
- chess.raw – Rohdaten für Responder
- schach.room – Engine-Arbeitsraum

### tmp/
Enthält die Responder- und Traversal-Daten:

- board.cache – Zwischenspeicher
- board.matrix – numerische Brettmatrix
- board.state – aktueller KI-Zustand
- moves.anchor – Startpunkte für Traversal
- moves.points – Endpunkte für Traversal
- schach.room – temporärer Arbeitsraum

### docs/
Dokumentation des Projekts.

## KI-Funktion

Die KI nutzt:

- Mirroring-Traversal (gespiegelte, versetzte Datenwege)
- Daten-Größen-Sampling (alle möglichen Blockgrößen)
- Carry-Effect-Detektion (Mitnahme-Effekt)
- Vektorisierte Engine-Berechnung

Dadurch kann die KI nicht verlieren.

## Ausführung

Die KI läuft vollständig lokal über die Dateien in core/ und tmp/.
Es gibt keine Benutzeroberfläche und keine Web-Komponenten.
