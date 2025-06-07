# Richtlinien für Codex Agents

Diese Datei erläutert, wie Änderungen in diesem Repository vorgenommen werden sollen. Das Repository verwendet [Writerside](https://www.jetbrains.com/help/writerside/) von JetBrains für die Dokumentation. Writerside basiert auf Markdown, bietet jedoch zusätzliche Funktionen wie Snippets, Variablen und spezielle Tags.

## Allgemeine Regeln
- Schreibe alle neuen Inhalte auf Deutsch.
- Achte auf eine freundliche, leicht verständliche Ausdrucksweise.
- Bestehende Dateien dürfen nicht ohne Grund gelöscht werden.
- Nutze Pull Requests mit aussagekräftigen Beschreibungen.

## Writerside-spezifische Hinweise
 - Writerside unterstützt Standard-Markdown sowie erweiterte Tags und eine XML-basierte Semantik.
    - Wiederverwendbare Inhalte definierst du mit `<snippet id="...">...</snippet>`.
    - Über `<include from="DATEI" element-id="ID"/>` bindest du Snippets in andere Seiten ein.
    - Variablen aus `Writerside/v.list` kannst du über `%varname%` nutzen.
    - Hinweise und Warnungen werden mit `{style="note"}` bzw. `{style="warning"}` erzeugt.
    - Registerkarten lassen sich mit `<tabs>` und `<tab title="Titel" id="name">` aufbauen.
    - Definitionen verwendest du mit `<deflist>` und `<def title="...">`.
    - Neue Dokumentationsdateien legst du unter `Writerside/topics/` an. Die Struktur sollte zu den vorhandenen Unterordnern passen.
    - Bilder kommen in `Writerside/images/`, Videos in `Writerside/videos/`.
 - Achte darauf, IDs für Überschriften zu vergeben (`## Titel {id="..."}`), damit Links stabil bleiben.
 - Bevor du Inhalte veröffentlichst, führe das Writerside-Build-Skript aus (falls vorhanden), um sicherzustellen, dass die Dokumentation fehlerfrei gerendert wird.

### Kurzübersicht zum Writerside-Markup
Writerside kombiniert CommonMark mit zahlreichen XML‑Tags. Ein paar der wichtigsten Funktionen aus der Dokumentation sind:

- **Absätze und Text**: Einfache Absätze brauchen keine besonderen Tags. Für Textblöcke kannst du `<p>` verwenden und über `{id="..."}` eigene IDs setzen.
- **Strukturelle Blöcke**: Verwende `<chapter>` für längere Themenblöcke oder `<procedure>` mit `<step>` für Schritt‑an‑Schritt-Anleitungen. Inhaltslisten baust du mit `<list type="ordered">` oder `<list type="unordered">`, Tabellen mit `<table>`, `<tr>`, `<td>`.
- **Ein- und ausklappbare Abschnitte**: `<collapsible>` bzw. `<expander>` ermöglichen Akkordeon-ähnliche Inhalte.
- **Links und Querverweise**: `[Linktext](url)` funktioniert wie gewohnt. Für interne Verweise gibt es `<xref href="topic.id"/>`.
- **Medieneinbindung**: Bilder bindest du über `![Alt-Text](path)` oder `<img src="path" alt="Text">` ein, Videos mit `<video src="..." poster="...">`.
- **Weitere Blöcke**: `tabs` mit `tab` für Registerkarten, `code-block` für längere Beispiele, `diagram` für Mermaid-, PlantUML- oder D2-Grafiken, `math` für Formeln.
- **Inline-Tags**: `link`, `control`, `path`, `var`, `shortcut` oder `tooltip` ergänzen Textstellen semantisch. Für kurze Code-Snippets nutzt du `` `code` `` oder `<code>`.
- **Hinweiskästen**: `{style="note"}`, `{style="tip"}`, `{style="warning"}`, `<tldr>` oder `<summary>` heben wichtige Informationen hervor.
- **Weitere Funktionen**: Dateien zum Download deklarierst du mit `<download>`, Startseiten über `<section-starting-page>`, Beschriftungen mit `labels="tag1,tag2"`.
Eine kompakte Übersicht aller Elemente steht in der [Semantic Markup Reference](https://www.jetbrains.com/help/writerside/semantic-markup-reference.html). Weitere Infos zu Paragraphs, Structural Elements und anderen Themen findest du in den Writerside-Seiten.
## Writerside lokal oder mit Docker bauen

Um deine Änderungen zu testen, kannst du den in Writerside integrierten Builder oder das von JetBrains bereitgestellte Docker-Image verwenden.

1. **Docker-Image herunterladen**

   ```bash
   docker pull jetbrains/writerside-builder:2025.04.8412
   ```

2. **Dokumentation bauen**

   Starte den Build aus dem Projektstammverzeichnis heraus und mounte die Quelldateien in den Container:

   ```bash
   docker run --rm -v "$PWD":/opt/sources \
     -e SOURCE_DIR=/opt/sources \
     -e MODULE_INSTANCE=Writerside/hi \
     -e OUTPUT_DIR=/opt/sources/output \
     -e RUNNER=other \
     jetbrains/writerside-builder:2025.04.8412
   ```

   Das Ergebnis findest du anschließend im Ordner `output`.

## Projektstruktur
- `Writerside/writerside.cfg` steuert die wichtigsten Einstellungen des Projekts.
- Kategorien und Labels befinden sich in `Writerside/c.list` und `Writerside/labels.list`.
- In `templates/` findest du Vorlagen, die du bei Bedarf einbinden kannst.

## Hinweise für Pull Requests
- Stelle sicher, dass die Git-Historie sauber ist (`git status` sollte keine Änderungen zeigen).
- Führe vor dem Commit alle im Projekt definierten Tests oder Builds aus.
- Beschreibe im PR-Text kurz, welche Dateien du geändert hast und warum.
- Füge der PR-Beschreibung eine Zusammenfassung auf Deutsch hinzu.

