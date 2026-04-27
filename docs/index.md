# Projektuebersicht

Dieses Repository ist eine kleine Uebung zu Git und Python.
Der Schwerpunkt liegt auf einem einfachen Rechenmodul und einem separaten Test-Unterordner.

## Inhalte

- `calc.py`: Enthalten sind drei Grundrechenarten als Funktionen:
	- `add(a, b)` fuer Addition
	- `sub(a, b)` fuer Subtraktion
	- `mult(a, b)` fuer Multiplikation
- `ccde_test_fork/README.md`: Kurzes Readme zum Test-Unterprojekt.
- `ccde_test_fork/test.py`: Beispielhafte Test-/Vergleichsfunktion fuer `add`.
- `docs/index.md`: Diese Dokumentationsseite.

## Projektstruktur

```text
uebung/
|- calc.py
|- ccde_test_fork/
|  |- README.md
|  |- test.py
`- docs/
	 `- index.md
```

## Ausfuehren

Das Hauptskript kann direkt gestartet werden:

```bash
python calc.py
```

Beispielausgaben:

- `5 + 3 = 8`
- `5 - 3 = 2`
- `5 * 3 = 15`

## Hinweise

- In `ccde_test_fork/test.py` ist die Funktion `add(a, b)` aktuell so implementiert, dass sie `a - b` zurueckgibt.
- Falls das als Test fuer Fehlersuche gedacht ist, kann es so bleiben.
- Falls es echte Addition sein soll, muesste es auf `a + b` geaendert werden.

## Lernziel

Dieses Projekt eignet sich gut, um folgende Grundlagen zu ueben:

- Git-Workflows (Aenderungen, Commits, Branches)
- einfache Python-Funktionen
- Dokumentation in Markdown
