# Lakeland Angler – Bucharchitektur v1.0

## Zweck

Dieses Dokument definiert die verbindliche redaktionelle Architektur des **Lakeland Angler – Catch & Cook Guide**. Es übersetzt das Inhaltsverzeichnis v1.1 in wiederverwendbare Seitentypen und legt fest, welche Informationen auf jeder Seite vorkommen dürfen beziehungsweise müssen.

Die Bucharchitektur gilt vor dem visuellen Layout. Konkrete Schriften, Farbwerte, Abstände und Satzspiegel werden später im Layoutsystem festgelegt.

## Leitprinzip

> Mehr Zeit mit Angeln. Weniger Zeit mit Lesen.

Jede Seite muss mindestens eine konkrete Frage beantworten. Die wichtigste Antwort muss innerhalb weniger Sekunden auffindbar sein.

## Produktionsgrundlagen

- Format: A5 Hochformat, 148 × 210 mm
- Zielumfang: 60 Seiten einschliesslich Cover
- Sprache: Deutsch mit englischen Fachbegriffen in Klammern
- Ansprache: Du
- maximal zwei Textspalten pro Seite
- kurze Absätze, Listen und Tabellen statt Textblöcken
- Inhalte und Assets bleiben voneinander getrennt
- keine GPS-Koordinaten, QR-Codes, Preise oder Öffnungszeiten
- rechtliche, gesundheitliche und sicherheitsrelevante Angaben benötigen Quelle und Prüfdatum in den Produktionsdaten

## Informationshierarchie

Jede Inhaltsseite folgt derselben Leserichtung:

1. **Orientierung:** Seitentitel und unmittelbarer Nutzen
2. **Entscheidung:** wichtigste Empfehlung oder Kernaussage
3. **Anwendung:** konkrete Schritte, Auswahl oder Fangstrategie
4. **Absicherung:** Fehler, Warnung oder Einschränkung
5. **Merksatz:** kompakte Zusammenfassung

Nicht jeder Seitentyp muss alle fünf Ebenen als sichtbare Überschrift verwenden. Die Reihenfolge bleibt dennoch erhalten.

## Inhaltsbudgets

Die Wortbudgets sind Richtwerte für den redaktionellen Rohtext ohne Quellenangaben und Produktionsnotizen.

| Seitentyp | Umfang | Richtwert |
| --- | ---: | ---: |
| Standard- oder Infoseite | 1 Seite | 180–280 Wörter |
| Checkliste oder Warnseite | 1 Seite | 100–180 Wörter |
| Monatsprofil | 1 Seite | 120–180 Wörter |
| Fischprofil | 2 Seiten | 350–500 Wörter |
| Köderübersicht | 1 Seite | 140–220 Wörter |
| Montagezeichnung | 1 Seite | 120–200 Wörter |
| Ausrüstungsseite | 1 Seite | 140–220 Wörter |
| Gewässerprofil | 1 Seite | 160–240 Wörter |
| Prozessseite | 1 Seite | 130–220 Wörter |
| Rezeptseite | 1 Seite | 160–230 Wörter |
| Quick Reference Card | 1 Seite | maximal 120 Wörter |

## Wiederkehrende Komponenten

### Seitenkopf

- Kapitelname oder Kapitelnummer
- eindeutiger Seitentitel
- optional ein kurzer Untertitel mit konkretem Nutzen

### Schnellinfo-Leiste

Je nach Seitentyp drei bis sechs kompakte Werte, zum Beispiel:

- beste Monate
- beste Uhrzeit
- Schwierigkeitsgrad
- Ufer beziehungsweise Boot
- Hauptköder
- Kücheneignung

### Infoboxen

Es werden ausschliesslich die im Designsystem definierten Typen verwendet:

- **Tipp:** direkt umsetzbare Empfehlung
- **Achtung:** Gefahr, Regel oder typischer Fehler
- **Profi-Tipp:** weiterführende Technik
- **Gut zu wissen:** hilfreicher Kontext

Pro Seite sind höchstens zwei Infoboxen vorgesehen. Eine Warnung hat Vorrang vor ergänzendem Kontext.

### Merksatz

Ein Satz mit der wichtigsten Handlungsempfehlung. Maximal 20 Wörter.

### Produktionsmetadaten

Jede Inhaltsdatei enthält einen YAML-Block mit:

- Dokument-ID
- Titel
- Seitentyp
- Zielseiten
- Version
- Status
- Datum der letzten fachlichen Prüfung
- referenzierten Quellen-IDs
- benötigten Asset-IDs

Diese Metadaten erscheinen nicht im gedruckten Buch.

## Seitentyp A – Quick Start

**Ziel:** Der Leser kann mit minimaler Vorbereitung noch am selben Tag angeln gehen.

### Pflichtinhalte

- minimal benötigte Ausrüstung
- einfache, universelle Montage
- geeigneter Einstiegsköder
- erfolgversprechende Tageszeit
- Auswahl eines geeigneten Gewässers
- Regeln vor dem Start prüfen
- Kühlung und Sicherheitsausrüstung

### Aufbau

1. Schnellentscheidung „Nimm das mit“
2. Montage in wenigen Schritten
3. Platz und Tageszeit auswählen
4. erster Wurf und Köderführung
5. Fang versorgen oder sicher zurücksetzen
6. Warnbox

### Abnahmekriterium

Ein Einsteiger kann die Seite ohne Kenntnis anderer Kapitel praktisch anwenden.

## Seitentyp B – Regeln und Sicherheit

**Ziel:** Risiken und Prüfpflichten verständlich machen, ohne tagesabhängige Regelwerke abzudrucken.

### Pflichtinhalte

- was vor dem Angeln offiziell geprüft werden muss
- Lizenz, Entnahme, Fanglimit und lokale Sonderregeln
- Hitze, Gewitter und Sonnenschutz
- Alligatoren und Schlangen
- Kinder, Haken und Schneidwerkzeuge
- Notfallgrundsatz

### Redaktionsregel

Veränderliche Zahlenwerte werden nur aufgenommen, wenn sie für den Nutzwert unverzichtbar sind. Jeder Wert benötigt eine offizielle Quelle und ein Prüfdatum.

## Seitentyp C – Monatsprofil

**Ziel:** Für einen konkreten Monat schnell Fisch, Zeit, Köder und See auswählen.

### Pflichtfelder

- Rangfolge der Zielfische
- beste Zeitfenster
- typische Wetter- und Wasserbedingungen
- zwei bis vier Köderempfehlungen
- zwei bis vier geeignete Gewässer
- erfolgversprechende Bereiche
- „Das lohnt sich weniger“
- Monatstipp

### Layoutlogik

- oberes Drittel: Monat, Bedingungen und beste Zeit
- mittlerer Bereich: Zielfische und Köder
- unteres Drittel: Seen, ungünstige Methoden und Monatstipp

### Abnahmekriterium

Die Kernaussage muss ohne Fliesstext allein aus Rangfolge, Tabelle und Icons verständlich sein.

## Seitentyp D – Fischprofil

**Ziel:** Einen Hauptzielfisch sicher erkennen, gezielt fangen und angemessen versorgen.

Dieser Seitentyp gilt ohne Abweichung für Black Crappie, Tilapia, Bluegill, Redear Sunfish und Largemouth Bass. Alle fünf Arten erhalten denselben Umfang, dieselbe Informationshierarchie und dasselbe Layout.

### Doppelseite links – Erkennen und Finden

- deutscher und englischer Name
- wissenschaftlicher Name
- eindeutige Erkennungsmerkmale
- mögliche Verwechslungen
- beste Monate und Tageszeiten
- typische Standplätze
- geeignete Gewässer
- grosse Fischillustration
- Standplatzskizze

### Doppelseite rechts – Fangen und Verwerten

- beste Köder
- bevorzugte Montage
- geeignete Ausrüstung
- kurze Schrittfolge der Fangstrategie
- häufige Fehler
- Umgang nach dem Fang
- Kücheneignung und Geschmacksprofil
- passendes Erfolgsrezept
- Quick Reference

### Abnahmekriterium

Bestimmung, Fangstrategie und Versorgung sind fachlich geprüft und ohne Widerspruch zu Monats-, Köder- oder Montageseiten.

## Seitentyp E – Köderübersicht

**Ziel:** Den richtigen Köder auswählen und korrekt einsetzen.

### Pflichtfelder je Köder

- Name auf Deutsch und Englisch
- geeignete Fischarten
- beste Situation
- Grösse oder relevante Auswahlmerkmale
- Haken beziehungsweise Montage
- einfache Führung oder Präsentation
- ein typischer Fehler

### Redaktionsregel

Zeitlose Eigenschaften stehen vor Marken oder Produktbeispielen. Verpackungen und Preise werden nicht gezeigt.

## Seitentyp F – Montage

**Ziel:** Eine Montage anhand einer Zeichnung korrekt nachbauen und verwenden.

### Pflichtinhalte

- Einsatzbereich
- geeignete Fischarten
- benötigte Komponenten
- Aufbau in nummerierten Schritten
- technische Montagezeichnung
- relevante Grössenbereiche
- Anwendung am Wasser
- häufigster Fehler

### Abnahmekriterium

Die Montage muss allein anhand von Zeichnung, Komponentenliste und Schritten nachbaubar sein.

## Seitentyp G – Ausrüstung

**Ziel:** Eine funktionale Ausrüstung ohne unnötige Käufe zusammenstellen.

### Pflichtinhalte

- Einsatzzweck
- zeitlose Auswahlkriterien
- sinnvolle Grössen- oder Leistungsklasse
- Zuordnung zu Fischarten und Methoden
- Einsteigerempfehlung
- optional austauschbare Produktbeispiele
- Hinweise zu Transport, Pflege oder Sicherheit

### Redaktionsregel

Produktbeispiele dürfen niemals die einzige Empfehlung darstellen.

## Seitentyp H – Gewässerprofil

**Ziel:** Das Potenzial eines Gewässers einschätzen und geeignete Angelbereiche erkennen.

### Pflichtfelder

- Gewässername und Einordnung
- relevante Zielfische
- beste Jahreszeit und Tageszeit
- geeignete Ufer- beziehungsweise Bootsbereiche
- Strukturen und Vegetation
- zwei bis vier geeignete Methoden
- Besonderheiten und Gefahren
- didaktische Kartenskizze

### Ausschlüsse

- keine GPS-Koordinaten
- keine Öffnungszeiten
- keine Preise
- keine lange Ortsgeschichte
- keine Satellitenbilder

### Abnahmekriterium

Das Profil bleibt auch dann nützlich, wenn sich Zugänge oder operative Details ändern.

## Seitentyp I – Prozessseite Fischversorgung

**Ziel:** Einen gefangenen Fisch sicher, hygienisch und nachvollziehbar versorgen.

### Pflichtinhalte

- benötigtes Werkzeug
- Vorbereitung
- nummerierte Arbeitsschritte
- klare Stopp- oder Warnpunkte
- Hygiene und Kühlkette
- häufige Fehler
- Endzustand des jeweiligen Prozesses

### Redaktionsregel

Jeder sicherheits- oder gesundheitsrelevante Schritt benötigt eine belastbare Quelle. Illustrationen zeigen nur notwendige Handgriffe und vermeiden dekorative Details.

## Seitentyp J – Rezept

**Ziel:** Den Fang mit einfacher Urlaubsküchen-Ausrüstung zuverlässig zubereiten.

### Pflichtfelder

- geeignete Fischarten
- Portionen
- Vorbereitungs- und Garzeit
- kurze Zutatenliste
- benötigte Ausrüstung
- maximal sechs Zubereitungsschritte
- Merkmal für sicheren Garzustand
- eine einfache Variation

### Abnahmekriterium

Das Rezept funktioniert ohne Spezialgerät und lässt sich auf mindestens zwei Hauptzielfische übertragen.

## Seitentyp K – Quick Reference Card

**Ziel:** Entscheidungen am Wasser ohne erklärenden Fliesstext ermöglichen.

### Pflichtinhalte

- klare Vergleichsmatrix oder nummerierte Kurzfolge
- konsistente Icons und Kurzbegriffe
- nur Informationen aus bereits erklärten Kapiteln
- Warnhinweise nur, wenn für die unmittelbare Anwendung notwendig

### Abnahmekriterium

Die Karte ist eigenständig verständlich und bei A5-Ausgabe aus Armlänge lesbar.

## Kapitelübergreifende Konsistenzregeln

- Fisch-, Monats-, Köder-, Montage- und Gewässerempfehlungen verwenden dieselben Bezeichnungen.
- Jede Methode verweist auf eine im Buch erklärte Montage.
- Jeder empfohlene Köder erscheint in der Köderübersicht oder wird direkt erklärt.
- Gewässerzuordnungen werden gegen Fischprofile und Monatsplaner geprüft.
- Rezepte versprechen keine artspezifische Eignung, die dem Fischprofil widerspricht.
- Warnhinweise werden nicht verkürzt, wenn dadurch die Bedeutung verändert wird.
- Englische Begriffe werden einheitlich geschrieben.

## Dateistruktur für die Inhaltsproduktion

```text
Inhalte/
├── 01_Einstieg/
├── 02_Monatsplaner/
├── 03_Fischarten/
├── 04_Koeder/
├── 05_Montagen/
├── 06_Ausruestung/
├── 07_Seen/
├── 08_Fischversorgung/
├── 09_Rezepte/
└── 10_Quick_Reference/
```

Dateinamen folgen dem Schema:

```text
<Kapitelnummer>_<Thema>_v<Major.Minor>.md
```

## Statusmodell

Jedes Inhaltsmodul durchläuft:

1. `Geplant`
2. `Recherche läuft`
3. `Recherche abgeschlossen`
4. `Rohfassung`
5. `Fachlich geprüft`
6. `Redaktionell freigegeben`
7. `Assets vollständig`
8. `Im Layout`
9. `Final freigegeben`

Ein Status darf erst gesetzt werden, wenn alle Pflichtfelder der betreffenden Stufe erfüllt sind.

## Seitentyp Frontmatter – Titeleinstieg und Buchnavigation

**Ziel:** Das Buch eröffnen, Pflichtangaben aufnehmen und die Nutzung verständlich machen.

### Cover

- Titel und Untertitel
- klares Lakeland- und Angelmotiv
- keine zusätzlichen Erklärtexte
- aus A5-Ansicht eindeutig lesbar

### Impressum

- Titel, Version und Veröffentlichungsjahr
- verantwortliche Personen
- Urheber- und Bildnachweise
- rechtliche Hinweise und Haftungsausschluss
- Stand der fachlichen Prüfung

### Vorwort

- persönlicher Anlass für den Guide
- Zielgruppe und Nutzen
- Catch-&-Cook-Schwerpunkt
- verantwortungsvoller Umgang mit Fisch und Natur
- 180 bis 250 Wörter

### Inhaltsverzeichnis

- alle zehn Hauptteile
- Seitenzahlen
- konsistente Kurzbezeichnungen
- keine Untergliederung, die die A5-Seite überlädt

### So benutzt du diesen Guide

- Leselogik und wiederkehrende Icons
- Bedeutung der vier Infobox-Typen
- einheitliche Struktur aller fünf Zielfischprofile
- Hinweis auf die Prüfung aktueller Regeln
- Verweis auf Quick Reference Cards

### Abnahmekriterium

Nach Seite 5 versteht der Leser Zweck, Grenzen und Navigationslogik des Guides.

## Freigabe von Produktionsschritt 2

Produktionsschritt 2 ist abgeschlossen, wenn:

- jeder Inhalt aus dem Inhaltsverzeichnis einem Seitentyp zugeordnet ist
- für jeden Seitentyp Pflichtfelder und Abnahmekriterien definiert sind
- Wortbudgets und Seitenumfang feststehen
- Vorlagen für die Inhaltsproduktion verfügbar sind
- offene visuelle Detailentscheidungen nicht vorweggenommen wurden
