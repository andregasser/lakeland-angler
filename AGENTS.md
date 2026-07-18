# AGENTS.md

## Projekt

Dieses Repository enthält die Planung, Gestaltung und spätere Produktion des deutschsprachigen Angelguides **Lakeland Angler** für Lakeland, Florida.

Die bestehenden Spezifikationen in `Projekt/`, `Design/` und `LAKELAND_ANGLER_Konzept_v1.md` sind vor Änderungen zu lesen und als verbindliche Projektgrundlage zu behandeln.

## Arbeitsweise

- Inhalte und Illustrationen werden getrennt entwickelt.
- Dokumente werden in Markdown (`.md`) gepflegt.
- Bestehende Versionsnummern und Benennungskonventionen werden beibehalten.
- Änderungen sollen klein, nachvollziehbar und auf die jeweilige Aufgabe begrenzt sein.
- Widersprüche zwischen Spezifikationen dürfen nicht stillschweigend aufgelöst werden. Sie sind zu dokumentieren oder mit dem Projektverantwortlichen abzustimmen.
- Neue Inhalte folgen der deutschen Du-Ansprache sowie dem kurzen, verständlichen und professionellen Outdoor-Stil des Guides.
- Für alle deutschen Texte gilt Schweizer Rechtschreibung: In Fliesstexten, Titeln, Bildprompts und eingebetteten Seitentexten wird ausnahmslos `ss` verwendet; das scharfe S ist ausgeschlossen.
- Tagesaktuelle fachliche Angaben, insbesondere Gesetze, Vorschriften und Sicherheitsinformationen, müssen vor der Verwendung anhand verlässlicher Quellen geprüft werden.

## Qualität

- Markdown muss sauber strukturiert und gut lesbar sein.
- Tabellen, Listen und Überschriften sollen konsistent formatiert werden.
- Inhalte müssen modular und später unabhängig vom Layout wiederverwendbar bleiben.
- Visuelle Assets müssen den Vorgaben im Verzeichnis `Design/` entsprechen.
- Unnötige Änderungen an nicht betroffenen Dateien sind zu vermeiden.

## Git und Commits

Für dieses Projekt werden **Conventional Commits** verwendet.

Commit-Nachrichten folgen diesem Schema:

```text
<type>(<scope>): <kurze Beschreibung>
```

Geeignete Typen sind insbesondere:

- `feat`: neue Inhalte oder Funktionen
- `fix`: Korrekturen
- `docs`: Änderungen an Dokumentation und Guide-Texten
- `design`: Änderungen am Designsystem oder an visuellen Vorgaben
- `refactor`: strukturelle Änderungen ohne inhaltliche Erweiterung
- `chore`: Wartung, Organisation und sonstige Hilfsarbeiten

Beispiele:

```text
docs(project): convert specifications to markdown
docs(content): add quick-start chapter
design(assets): define fish illustration requirements
fix(content): correct lake name in spot overview
```

- Die Beschreibung wird im Imperativ formuliert, beginnt klein und endet ohne Punkt.
- Ein Commit enthält möglichst nur eine logisch zusammengehörige Änderung.
- Breaking Changes werden mit `!` und bei Bedarf mit einem `BREAKING CHANGE:`-Footer gekennzeichnet.
- Commits dürfen erst erstellt werden, wenn sie ausdrücklich angefordert wurden.
