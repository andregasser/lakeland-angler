# Lakeland Angler – P1-Musterset v1.0

## Zweck

Das Musterset legt die visuelle und technische Referenz für alle späteren Assets fest. Erst nach gemeinsamer Abnahme werden Serienassets produziert. So bleiben Icons, Fische und Montagezeichnungen über das gesamte Buch konsistent.

## Umfang des Mustersets

| Asset-ID | Musterfunktion | Zielseite | Ergebnis |
| --- | --- | ---: | --- |
| ICON-BOAT-ACCESS-001 | komplexes Zugangs-Icon | 43–51 | SVG und PNG |
| ICON-SHORE-ACCESS-001 | einfaches Zugangs-Icon | 43–51 | SVG und PNG |
| ICON-TIME-001 | rundes Funktions-Icon | 55–57 | SVG und PNG |
| ICON-TEMPERATURE-001 | schmales Funktions-Icon | 55–57 | SVG und PNG |
| FISH-BLACK-CRAPPIE-001 | Referenz für alle Fischillustrationen | 21–22 | transparentes PNG |
| RIG-BOBBER-001 | Referenz für alle Montagezeichnungen | 35 | SVG und PNG |

Diese sechs Assets decken einfache und komplexe Silhouetten, organische Formen, feine anatomische Details sowie technische Linien ab.

## Verbindliche Farbwerte

Die benannten Farben des Designsystems werden für das Musterset mit folgenden Arbeitswerten konkretisiert:

| Farbtoken | Hex | Verwendung |
| --- | --- | --- |
| Deep Lake Blue | `#173F4F` | Hauptfarbe, Linien und dunkle Flächen |
| Florida Blue | `#2E748F` | Wasser, sekundäre Flächen |
| Fresh Green | `#64805A` | Vegetation und positive Orientierung |
| Sand Beige | `#D8C7A5` | helle Flächen und ruhige Hintergründe |
| Sunset Orange | `#D97932` | sparsame Akzente und Fokus |
| Safety Red | `#B44336` | ausschließlich Warnungen |
| Ink | `#202B30` | technische Linien und Beschriftung im Layout |
| Paper | `#FAF8F2` | Illustrations- und Seitenhintergrund |

Die Werte gelten als Arbeitsstandard. Eine spätere drucktechnische CMYK-Anpassung verändert nicht die Farbhierarchie.

## Iconstandard

- quadratisches SVG mit `64 × 64` ViewBox
- einfarbige Primärversion in Deep Lake Blue
- Strichstärke `3` ViewBox-Einheiten
- runde Linienenden und runde Verbindungen
- optische Sicherheitszone von mindestens `6` Einheiten
- keine Texte, Verläufe, Schlagschatten oder perspektivischen Effekte
- gefüllte Flächen nur, wenn die Silhouette sonst bei kleiner Größe zerfällt
- PNG-Export: `1024 × 1024 px`, transparenter Hintergrund

### Zielgröße im Buch

- regulär: 6–8 mm
- kleinste zulässige Darstellung: 5 mm
- bei 5 mm müssen Motiv und Funktion ohne Legende unterscheidbar bleiben

## Fischstandard

### Black-Crappie-Muster

- wissenschaftlich plausible perfekte Seitenansicht
- Kopf nach links, Schwanz nach rechts
- vollständige Silhouette einschließlich Schwanz- und geschlossener Flossen
- natürliche Körperhaltung ohne starke Krümmung
- arttypischer hoher, seitlich abgeflachter Körper
- unregelmäßige dunkle Flecken statt vertikaler Bänder
- zusammenhängende Rückenflosse mit erkennbaren Hart- und Weichstrahlen
- neutrales weiches Tageslicht von links oben
- keine Angelschnur, Hände, Wasser, Boden oder dekorative Pflanzen
- transparenter Hintergrund und weicher, nicht eingebrannter Kontaktschatten als separate Variante

### Technische Ausgabe

- PNG mit transparentem Hintergrund
- mindestens 3600 px Breite
- verlustfrei, sRGB-Arbeitsdatei
- zusätzliche verkleinerte Prüfausgabe in vorgesehener A5-Druckgröße
- alle fünf Fischarten erhalten später dieselbe Blickrichtung, Lichtquelle und relative Darstellungslogik

## Montagestandard

### Bobber-Rig-Muster

- weißer beziehungsweise Paper-Hintergrund
- vertikale Leserichtung von Hauptschnur zu Haken
- Komponenten: Hauptschnur, kleine Pose, Split Shot, 6–12 Zoll Abstand, Einzelhaken und kompakter Naturköder
- Hauptschnur in Deep Lake Blue, technische Konturen in Ink
- Sunset Orange nur für Pose oder nummerierten Fokus
- durchgehende Grundlinienstärke `2.5` ViewBox-Einheiten
- Pfeile und Nummern als separate Layout-Ebene; keine fest eingebrannten erklärenden Texte
- Hakenform und Schnurstärke bleiben in allen Montagen identisch

### Technische Ausgabe

- SVG-Master mit logisch benannten Gruppen
- PNG-Prüfexport mit mindestens 3000 px langer Kante
- vollständige Montage und Detailausschnitt des Hakens
- Lesbarkeit bei einer gedruckten Breite von 55–65 mm prüfen

## Dateistruktur

```text
Assets/
├── P1_Musterset/
│   ├── Icons/
│   ├── Fische/
│   └── Montagen/
└── Proofs/
    └── P1_Musterset/
```

Dateinamen folgen der Asset-ID:

```text
ICON-BOAT-ACCESS-001_v1.svg
ICON-BOAT-ACCESS-001_v1.png
FISH-BLACK-CRAPPIE-001_v1.png
RIG-BOBBER-001_v1.svg
RIG-BOBBER-001_v1.png
```

## Abnahmereihenfolge

1. Farbfelder und vier Icons gemeinsam bei 5, 6 und 8 mm prüfen.
2. Black Crappie auf Anatomie, Silhouette, Licht und Detailgrad prüfen.
3. Bobber Rig auf Aufbau, Linienstärke und A5-Lesbarkeit prüfen.
4. Alle sechs Muster nebeneinander auf gemeinsame visuelle Sprache prüfen.
5. Erst nach Abnahme die entsprechenden Asset-Status auf `Fertig` setzen.

## Abnahmekriterien

- Motiv ist in der Zielgröße sofort erkennbar.
- Keine sichtbaren KI-Artefakte, unlogischen Überlagerungen oder uneinheitlichen Linien.
- Fischmerkmale und Montageaufbau sind fachlich korrekt.
- Farben funktionieren auf Paper und in Graustufen ausreichend unterscheidbar.
- Transparenz, Auflösung, Dateiname und Format entsprechen der Asset-Spezifikation.
- Das Musterset wirkt wie eine zusammenhängende Fachbuchserie, nicht wie sechs Einzelstile.

## Noch nicht freigegeben

Die Farbwerte, Strichstärken und Musterbeschreibungen sind Produktionsvorgaben, aber noch keine fertigen Assets. Ihre endgültige Freigabe erfolgt anhand der tatsächlichen Proofs in A5-Größe.
