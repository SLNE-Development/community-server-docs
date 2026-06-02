# Richtlinien für Agents

Diese Datei beschreibt, wie KI-Agents und andere automatisierte Werkzeuge Änderungen in diesem Repository durchführen sollen.

Das Repository verwendet Writerside von JetBrains für die Dokumentation. Writerside basiert auf Markdown und erweitert es um XML-Tags, Includes, Variablen und spezielle Attribute.

Der verbindliche Sprach- und Formatierungsstandard steht in [`STYLEGUIDE.md`](STYLEGUIDE.md).

## Grundregeln

- Schreibe alle neuen und überarbeiteten Inhalte auf Deutsch.
- Befolge den Styleguide in [`STYLEGUIDE.md`](STYLEGUIDE.md).
- Verwende grundsätzlich die direkte Ansprache mit „du“.
- Verwende keine gegenderte Sprache wie `Spielende`, `jede*r`, `Nutzer:innen` oder ähnliche Formen.
- Erhalte alle vorhandenen Informationen vollständig.
- Lösche keine bestehenden Inhalte ohne klaren Grund.
- Ändere keine Regeln, Warnungen oder Hinweise inhaltlich.
- Verwende eine freundliche, klare und leicht verständliche Sprache.
- Erstelle Pull Requests mit aussagekräftiger Beschreibung.

## Wichtige Arbeitsweise

Bei jeder Änderung gilt:

1. Lies die betroffene Datei vollständig genug, um den Kontext zu verstehen.
2. Ändere nur das, was zur Aufgabe gehört.
3. Erhalte Struktur, Reihenfolge und Bedeutung der Inhalte.
4. Prüfe nach der Änderung, ob keine Information verloren gegangen ist.
5. Prüfe Links, IDs, Variablen und Writerside-Markup besonders sorgfältig.

Wenn eine Formulierung unklar ist, formuliere konservativ um oder lasse sie unverändert.

## Sprachstil

Die Dokumentation spricht Leser grundsätzlich mit „du“ an.

Bevorzugte Formulierungen:

- „du kannst …“
- „du erhältst …“
- „du findest …“
- „wenn du …“
- „beachte …“

Vermeide unnötige Wechsel zwischen:

- „du“
- „ihr“
- „man“
- „die Spieler“

„Ihr“ ist nur erlaubt, wenn eindeutig eine Gruppe gemeinsam angesprochen wird.

## Gender-Regeln

Verwende keine gegenderte Sprache mit Sonderzeichen oder künstlichen Ersatzformen.

Nicht verwenden:

- `Spielende`
- `Nutzende`
- `Teilnehmende`
- `jede*r`
- `Nutzer:innen`
- `Spieler/innen`
- `SpielerInnen`

Verwende stattdessen das generische Maskulinum oder eine natürliche neutrale Formulierung.

Beispiele:

- `Spieler`
- `Nutzer`
- `Teilnehmer`
- `jeder`
- `die Community`
- `alle`
- `das Team`

Neutrale Formulierungen sind erlaubt, wenn sie natürlich und unauffällig wirken.

## Einheitliche Terminologie

Verwende die Schreibweisen aus dem Styleguide.

Besonders wichtig:

- `Community-Server`
- `Survival-Server`
- `Event-Server`
- `SMP-Server`
- `Serverregeln`
- `Shopsystem`
- `Skillsystem`
- `Skillmenü`
- `Befehl`
- `Modifikation`
- `Minecraft-Version`
- `TNT-Duper`

Eigennamen, Itemnamen, Plugin-Namen, UI-Bezeichnungen, Variablen und Befehle dürfen nicht unnötig verändert werden.

## Typografie

Achte auf korrekte deutsche Typografie.

Beispiele:

- `z. B.`
- `d. h.`
- `u. a.`
- `10 %`
- `550 Spielstunden`

Verwende geschützte Leerzeichen, wo Begriffe nicht getrennt werden sollen.

Verändere keine technischen Variablen wie:

- `%main_currency%`
- `%dc_link%`
- `%required_game_version%`

## Writerside-spezifische Hinweise

Writerside unterstützt Standard-Markdown sowie zusätzliche XML- und Attribut-Syntax.

Erhalte insbesondere:

- `<include from="..." element-id="..."/>`
- `<tabs>`
- `<tab title="..." id="...">`
- `<deflist>`
- `<def title="..." id="...">`
- `<chapter title="..." id="...">`
- `<tooltip term="...">`
- `{style="note"}`
- `{style="tip"}`
- `{style="warning"}`
- `%variable%`

Ändere keine technischen IDs, wenn es nicht ausdrücklich notwendig ist.

Dazu gehören:

- Überschriften-IDs wie `{id="economy-trading"}`
- XML-IDs wie `id="install-voicechat"`
- Include-IDs wie `element-id="mod-pack"`
- Linkziele und Anker
- Dateipfade
- Bildpfade

Sichtbare Texte in Attributen dürfen sprachlich korrigiert werden, wenn technische Werte unverändert bleiben.

Beispiele für sichtbare Texte:

- `title`
- `summary`
- `<title>`
- `<description>`
- `<def title="...">`

## Dateien und Struktur

Neue Dokumentationsdateien gehören grundsätzlich nach `Writerside/topics/`.

Bilder gehören nach:

```md
Writerside/images/
```

Videos gehören nach:

```md
Writerside/videos/
```

Achte darauf, dass neue Dateien zur vorhandenen Struktur passen.

## Formatierung

* Erhalte Markdown-Listen, Tabellen, Blockquotes und Codeblöcke.
* Erhalte absichtliche Zeilenumbrüche mit `\`, wenn sie für das Rendering nötig sind.
* Entferne keine Codeblöcke.
* Ändere keinen Inhalt in Codeblöcken, außer die Aufgabe verlangt es ausdrücklich.
* Korrigiere offensichtliche Tippfehler im Fließtext.
* Entferne doppelte Leerzeichen und unnötige Leerzeilen.
* Achte auf saubere Einrückung in XML- und Writerside-Dateien.

## Qualitätsprüfung

Vor dem Abschluss einer Änderung prüfen:

* Ist die Ansprache einheitlich?
* Wurden gegenderte Formen entfernt?
* Sind Begriffe einheitlich geschrieben?
* Sind Prozentangaben und Abkürzungen korrekt formatiert?
* Sind Links, IDs, Variablen und Includes unverändert funktionsfähig?
* Ist die Writerside-/Markdown-Struktur intakt?
* Wurde keine Information entfernt?
* Hat sich die Bedeutung von Regeln, Warnungen oder Hinweisen nicht verändert?

## Build-Prüfung

Wenn möglich, führe den Writerside-Build aus.

Beispiel:

```bash
docker run --rm -v "$PWD":/opt/sources \
  -e SOURCE_DIR=/opt/sources \
  -e MODULE_INSTANCE=Writerside/hi \
  -e OUTPUT_DIR=/opt/sources/output \
  -e RUNNER=other \
  jetbrains/writerside-builder:2025.04.8412
```

Wenn der Build nicht ausgeführt werden kann, prüfe die geänderten Dateien manuell auf offensichtliche Markdown-, XML- und Writerside-Fehler.

## Pull-Request-Beschreibung

Eine Pull-Request-Beschreibung soll enthalten:

* kurze Zusammenfassung der Änderung
* betroffene Bereiche oder Dateien
* Hinweis, ob der Writerside-Build ausgeführt wurde
* Hinweis, falls nur manuell geprüft wurde

Beispiel:

```md
## Zusammenfassung

- Ansprache in mehreren Dokumentationsseiten auf „du“ vereinheitlicht
- gegenderte Formen entfernt
- Typografie bei Abkürzungen und Prozentangaben korrigiert
- Writerside-Markup unverändert erhalten

## Prüfung

- Writerside-Build erfolgreich ausgeführt
```