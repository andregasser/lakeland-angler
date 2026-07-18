# Lakeland Angler

> Ein deutschsprachiger Catch-&-Cook-Guide für Lakeland, Florida – kompakt, visuell und direkt am Wasser nutzbar.

**Lakeland Angler** ist ein hochwertig konzipierter Angelguide für deutschsprachige Urlauber, Familien, Einsteiger und Hobbyangler in Central Florida. Das Buch verbindet saisonale Fangstrategien, konkrete Gewässerprofile und einfache Montagen mit sicherer Fischversorgung und unkomplizierten Rezepten.

Das Ziel ist ein druckfähiger A5-Guide mit 60 Seiten, vielen Tabellen, Karten und Illustrationen – und möglichst wenig unnötigem Fliesstext.

> **Mehr Zeit mit Angeln. Weniger Zeit mit Lesen.**

## Das Buch auf einen Blick

| Merkmal | Umsetzung |
| --- | --- |
| Region | Lakeland und umliegende Gewässer in Florida |
| Sprache | Deutsch mit etablierten englischen Angelbegriffen |
| Format | A5 Hochformat, Print-PDF und digitale Ausgabe |
| Umfang | 60 Seiten |
| Schwerpunkt | Catch & Cook, Einsteigerfreundlichkeit und zeitlose Planung |
| Stil | professionelles Outdoor- und Reisehandbuch |

## Die fünf Zielfische

- Black Crappie
- Blue Tilapia
- Bluegill
- Redear Sunfish – auch Shellcracker genannt
- Largemouth Bass

Alle fünf Arten erhalten denselben redaktionellen Umfang: Erkennung, beste Monate und Tageszeiten, Standplätze, Köder, Montagen, Ausrüstung, häufige Fehler, Versorgung und Kücheneignung.

## Behandelte Gewässer

- Tenoroc
- Lake Parker
- Saddle Creek
- Lake Gibson
- Banana Lake
- Lake Crago
- Lake Ariana
- Lake Hartridge

Eine regionale Übersicht ordnet alle Gewässer rund um Lakeland ein. Die Profile verzichten bewusst auf geheime GPS-Spots, Preise und schnell veraltende Öffnungszeiten.

## Buchstruktur

| Seiten | Teil |
| ---: | --- |
| 1–8 | Einstieg, Quick Start, Regeln und Sicherheit |
| 9–20 | Monatsplaner Januar bis Dezember |
| 21–30 | fünf gleich gewichtete Fischprofile |
| 31–34 | Naturköder, Minnows, Jigs und Bassköder |
| 35–38 | Montagen und Knoten |
| 39–42 | Grundausrüstung und Sicherheit |
| 43–51 | Seen rund um Lakeland |
| 52–54 | Fang versorgen, kühlen und filetieren |
| 55–57 | drei einfache Fischrezepte |
| 58–60 | Quick Reference Cards |

Das verbindliche Seitenmodell steht im [Inhaltsverzeichnis](Projekt/03_Inhaltsverzeichnis_v1.3.md), die redaktionellen Pflichtfelder in der [Bucharchitektur](Projekt/05_Bucharchitektur_v1.0.md).

## Aktueller Produktionsstand

- alle 60 Buchseiten sind in 55 modularen Markdown-Dateien abgedeckt
- 53 Module sind redaktionell freigegeben
- Lake Gibson bleibt unter Datenvorbehalt
- im Impressum fehlen noch persönliche und verlegerische Pflichtangaben
- alle fünf Fischillustrationen sind produziert und genehmigt
- das vollständige P1-Kernset aus Icons, Montagen und Knoten ist technisch vorhanden
- Montagen und Knotendiagramme warten noch auf die fachliche und didaktische Abnahme
- 81 kanonische Asset-IDs sind im Produktionsregister erfasst

Details liefern das [Produktionsaudit](Projekt/07_Produktionsaudit_v1.0.md) und die [Assetproduktionsliste](Design/15_Assetproduktionsliste_v1.0.md).

## Repository-Struktur

```text
lakeland-angler/
├── Assets/       # produzierte Illustrationen, Icons und Diagramme
├── Design/       # Designsystem, Bildstil und Asset-Spezifikationen
├── Inhalte/      # modulare Buchtexte mit YAML-Frontmatter
├── Projekt/      # Anforderungen, Architektur und Produktionsplanung
├── Recherche/    # Faktenstände und versioniertes Quellenregister
├── AGENTS.md     # verbindliche Arbeits- und Git-Regeln
└── README.md
```

Jedes Inhaltsmodul besitzt eine Dokument-ID, Zielseite, Version, Status, Prüfdatum sowie Quellen- und Asset-IDs. Dadurch lassen sich Texte, Fakten und Illustrationen unabhängig voneinander aktualisieren.

## Wichtige Dokumente

- [Projektanforderungen](Projekt/02_Anforderungen_v1.3.md)
- [Inhaltsverzeichnis](Projekt/03_Inhaltsverzeichnis_v1.3.md)
- [Entscheidungsprotokoll](Projekt/04_Entscheidungsprotokoll_v1.2.md)
- [Bucharchitektur](Projekt/05_Bucharchitektur_v1.0.md)
- [Designsystem](Design/10_Designsystem_v1.0.md)
- [Bildstil](Design/12_Bildstil_v1.0.md)
- [Asset-Spezifikation](Design/13_Assetspezifikation_v1.0.md)
- [P1-Musterset](Design/16_P1_Musterset_v1.0.md)
- [Quellenregister](Recherche/00_Quellenregister_v1.6.md)

## Qualitätsprinzipien

- Inhalte bleiben modular und unabhängig vom späteren Layout.
- Alle Seiten folgen festen Wortbudgets und wiederverwendbaren Seitentypen.
- Die fünf Zielfische werden gleichwertig behandelt.
- Rechtliche, gesundheitliche und sicherheitsrelevante Aussagen benötigen offizielle Quellen und ein Prüfdatum.
- Veränderliche Regeln werden vor Layout- und Druckfreigabe erneut kontrolliert.
- Illustrationen müssen fachlich korrekt, stilistisch konsistent und in A5-Grösse lesbar sein.
- Karten dienen der didaktischen Orientierung und nicht der Navigation.

## Mitarbeit und Git-Workflow

Das Projekt verwendet **Conventional Commits**:

```text
<type>(<scope>): <kurze Beschreibung>
```

Beispiele:

```text
docs(content): add lake profiles
design(assets): complete P1 core asset set
fix(content): correct fishing regulation reference
```

Vor Änderungen sind [AGENTS.md](AGENTS.md) und die jeweils betroffenen Spezifikationen zu lesen. Änderungen sollen klein, nachvollziehbar und fachlich belegt bleiben.

## Sicherheit und Aktualität

Dieses Repository ist eine Buchproduktion, kein amtliches Regelwerk. Angelberechtigungen, Fanglimits, Sonderregeln, Gewässerzugänge, Wetter-, Algen- und Verzehrhinweise können sich ändern. Vor Veröffentlichung und vor jedem praktischen Einsatz müssen die aktuellen Informationen der zuständigen Behörden geprüft werden.

Besonders die Illustrationen zu Betäubung, Ausbluten und Filetieren bleiben bis zur fachpraktischen Validierung gesperrt.

## Lizenz und Veröffentlichung

Das Buch befindet sich in Produktion. Urheber-, Veröffentlichungs- und Lizenzangaben sind noch nicht abschliessend festgelegt. Bis zur ausdrücklichen Veröffentlichung einer Lizenz bleiben alle Rechte vorbehalten.
