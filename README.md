# Datenmanagement & -analyse (DMA) - SS2026

Vorlesungsmaterialien für den Kurs **Datenmanagement & -analyse** an der Julius-Maximilians-Universität Würzburg.

## Kursübersicht

| Vorlesung | Thema | Slides | Notebook |
|-----------|-------|--------|----------|
| 1 | SQL-Grundlagen | [PDF](pdf/01-sql-grundlagen.pdf) | [marimo](marimo/01-sql-grundlagen.py) |
| 2 | SQL für Datenexploration | [PDF](pdf/02-sql-exploration.pdf) | [marimo](marimo/02-sql-exploration.py) |
| 3 | Aggregation & Gruppierung | [PDF](pdf/03-sql-aggregation.pdf) | [marimo](marimo/03-sql-aggregation.py) |
| 4 | CRISP-DM & Fallstudien | [PDF](pdf/04-crisp-dm-cases.pdf) | [marimo](marimo/04-crisp-dm-cases.py) |
| 5 | Warum mehrere Tabellen? | [PDF](pdf/05-redundanz-anomalien.pdf) | [marimo](marimo/05-redundanz-probleme.py) |
| 6 | Entity-Relationship-Modellierung | [PDF](pdf/06-er-modellierung.pdf) | [marimo](marimo/06-er-modellierung.py) |
| 7 | Relationales Modell & Transformation | [PDF](pdf/07-relationales-modell.pdf) | [marimo](marimo/07-er-zu-sql.py) |
| 8 | Normalisierung | [PDF](pdf/08-normalisierung.pdf) | [marimo](marimo/08-normalisierung.py) |
| 9 | JOINs | [PDF](pdf/09-joins.pdf) | [marimo](marimo/09-joins.py) |

## Struktur

```
.
├── pdf/          # Kompilierte Vorlesungsfolien
├── tex/          # LaTeX-Quelldateien
│   └── figures/  # Abbildungen
└── marimo/       # Interaktive Notebooks
    └── public/   # Datensätze (CSV)
```

## Notebooks ausführen

Die interaktiven Notebooks nutzen [marimo](https://marimo.io/). Installation:

```bash
pip install marimo
```

Notebook starten:

```bash
marimo edit marimo/01-sql-grundlagen.py
```

## Slides kompilieren

Die Folien nutzen das IMS Beamer-Theme. Kompilierung mit pdflatex:

```bash
cd tex
pdflatex 01-sql-grundlagen.tex
pdflatex 01-sql-grundlagen.tex  # Zweimal für Referenzen
```

## Features

- **Klickbare Navigation**: Agenda-Einträge und Progress-Dots verlinken zu den jeweiligen Phasen
- **TikZ-Diagramme**: ER-Modelle, Venn-Diagramme, Flussdiagramme
- **Live-Daten**: Notebooks laden aktuelle Bundesliga-Tabelle

## Dozent

**Prof. Dr. Christoph M. Flath**
Lehrstuhl für Wirtschaftsinformatik und Business Analytics
Julius-Maximilians-Universität Würzburg

## Lizenz

© 2026 Christoph M. Flath. Alle Rechte vorbehalten.
