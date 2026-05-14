# Typographic CV System

Minimalistisches LaTeX basiertes Lebenslaufsystem mit Fokus auf Typografie, Lesbarkeit und strukturierte Informationsdarstellung.

## Überblick

Dieses Projekt beschäftigt sich mit der Schnittstelle zwischen:

* Typografie,
* technischer Dokumentation,
* Informationsarchitektur,
* maschinenlesbarer Struktur,
* und minimalistischem Dokumentdesign.

Ziel war nicht die Gestaltung eines möglichst auffälligen Lebenslaufs, sondern die Entwicklung eines ruhigen, konsistenten und langfristig wartbaren Dokumentensystems.

Das Layout verzichtet bewusst auf:

* Icons,
* Fortschrittsbalken,
* Bewertungsskalen,
* starke Farbelemente,
* und dekorative Grafiken.

Stattdessen liegt der Fokus auf:

* klarer Informationshierarchie,
* typografischer Konsistenz,
* kontrolliertem Weißraum,
* semantischer Struktur,
* ATS Kompatibilität,
* und hoher Lesbarkeit.

## Gestaltungsprinzipien

### Lesbarkeit für Mensch und Maschine

Das Dokument wurde so entwickelt, dass es sowohl für Menschen als auch für automatisierte Parsing Systeme gut lesbar bleibt.

Die Struktur priorisiert:

* klare Abschnittstrennung,
* geringe visuelle Komplexität,
* vorhersehbare Formatierung,
* und eine ruhige Informationsführung.

### Typografisches System

Verwendet werden:

* Inter als Hauptschrift,
* Montserrat SemiBold für Überschriften,
* mikrotypografische Optimierung mittels `microtype`,
* konsistente Abstände und Seitenränder,
* reduzierte Abschnittsgestaltung.

Der typografische Ansatz soll:

* technische Präzision,
* moderne Lesbarkeit,
* und zurückhaltende Gestaltung
  miteinander verbinden.

### Minimalismus statt Dekoration

Viele moderne Lebenslauf Templates setzen stark auf visuelle Effekte.

Dieses Projekt verfolgt bewusst einen anderen Ansatz:
weniger visuelle Ablenkung, mehr strukturelle Klarheit und bessere Wartbarkeit.

## Technischer Aufbau

Verwendete Technologien und Pakete:

* LaTeX
* fontspec
* microtype
* hyperref
* enumitem
* geometry
* titlesec

## Repository Struktur

```text
.
├── src/
│   └── cv.tex
├── output/
│   └── preview.pdf
├── screenshots/
│   └── preview.png
├── README.md
└── .gitignore
```

## Projektziele

* Entwicklung eines typografisch konsistenten Lebenslaufsystems
* Verbesserung von Lesbarkeit und Informationsdichte
* Erhalt hoher ATS Kompatibilität
* Erforschung strukturierter Dokumentgestaltung
* Aufbau eines reproduzierbaren und versionierbaren Layoutsystems

## Mögliche Erweiterungen

* Markdown basierte Content Pipeline
* Automatisierte PDF Generierung
* GitHub Actions Workflow
* Semantische Trennung von Inhalt und Layout
* Mehrsprachige Varianten
* Modulare Abschnittsstruktur

## Projektgedanke

Dieses Repository versteht einen Lebenslauf weniger als dekoratives Dokument, sondern eher als strukturiertes technisches Informationssystem.

Das Projekt spiegelt ein persönliches Interesse an:

* Informationsdesign,
* technischer Dokumentation,
* typografischen Systemen,
* und iterativer Optimierung
  wider.
