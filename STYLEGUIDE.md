# Styleguide für die Community-Server-Dokumentation

Dieser Styleguide legt fest, wie Inhalte in der Community-Server-Dokumentation geschrieben, formatiert und gepflegt werden sollen.

Ziel ist eine einheitliche, verständliche und natürliche Dokumentation ohne Informationsverlust.

## Grundsätze

- Schreibe alle Inhalte auf Deutsch.
- Schreibe klar, freundlich und direkt.
- Erhalte bestehende Informationen vollständig.
- Formuliere nur um, wenn die Aussage gleich bleibt.
- Vermeide unnötig komplizierte Sätze.
- Verwende aktive Sprache, wenn sie natürlicher klingt.
- Achte darauf, dass Regeln, Warnungen und technische Hinweise nicht abgeschwächt oder verschärft werden.

## Ansprache

Die Dokumentation verwendet grundsätzlich die direkte Ansprache mit **„du“**.

Beispiele:

- „Du kannst den Server über die Lobby betreten.“
- „Wenn du Hilfe brauchst, erstelle ein Support-Ticket.“
- „Du erhältst eine Belohnung, sobald du das Ziel erreicht hast.“

Vermeide uneinheitliche Wechsel zwischen „du“, „ihr“, „man“ und „die Spieler“.

### Wann ist „ihr“ erlaubt?

„Ihr“ darf nur verwendet werden, wenn tatsächlich eine Gruppe gleichzeitig angesprochen wird.

Beispiele:

- „Wenn ihr gemeinsam an einem Event teilnehmt, achtet auf die Eventregeln.“
- „Sprecht euch im Team ab, bevor ihr mit dem Bau beginnt.“

Wenn eine einzelne Person gemeint sein kann, verwende „du“.

## Gender-Regeln

Die Dokumentation verwendet keine gegenderte Sprache mit Sonderzeichen oder künstlichen Ersatzformen.

Nicht verwenden:

- `Spielende`
- `Nutzende`
- `Teilnehmende`
- `jede*r`
- `Nutzer:innen`
- `Spieler/innen`
- `SpielerInnen`

Stattdessen verwenden:

- `Spieler`
- `Nutzer`
- `Teilnehmer`
- `jeder`

Natürlich neutrale Formulierungen sind erlaubt, wenn sie unauffällig und gut lesbar sind.

Gute Beispiele:

- „die Community“
- „alle“
- „das Team“
- „Mitglieder“
- „Personen“

Nicht zwanghaft neutralisieren. Die Formulierung soll natürlich bleiben.

## Einheitliche Begriffe

Verwende folgende Schreibweisen einheitlich:

| Verwenden | Nicht verwenden |
|---|---|
| Community-Server | Community Server |
| Survival-Server | Survival Server |
| Event-Server | Event Server |
| SMP-Server | SMP Server |
| Serverregeln | Server Regeln |
| Shopsystem | Shop System |
| Skillsystem | Skill System |
| Skillmenü | Skillmenu |
| Befehl | Command, wenn kein Eigenname |
| Modifikation | Modification |
| Minecraft-Version | Minecraft Version |
| TNT-Duper | TNT Duper |
| AutoClicker | Autoclicker, Auto Clicker |

Eigennamen, Itemnamen, Plugin-Namen, UI-Bezeichnungen und Befehle bleiben unverändert.

Beispiele:

- `/skill` bleibt `/skill`
- `%main_currency%` bleibt `%main_currency%`
- `<player>` bleibt `<player>`
- `Simple Voice Chat` bleibt `Simple Voice Chat`

## Typografie

### Geschützte Leerzeichen

Verwende geschützte Leerzeichen bei zusammengehörigen Ausdrücken.

Beispiele:

- `z. B.`
- `d. h.`
- `u. a.`
- `10 %`
- `550 Spielstunden`

Bei Prozentangaben steht ein Leerzeichen zwischen Zahl und Prozentzeichen.

Richtig:

```md
10 %
```

Falsch:

```md
10%
10 %
```

Wichtig: Variablen wie `%main_currency%` oder `%dc_link%` dürfen nicht verändert werden.

### Anführungszeichen

Im normalen Fließtext werden deutsche Anführungszeichen verwendet.

Richtig:

```md
„Das ist ein Beispiel.“
```

Gerade Anführungszeichen bleiben in Code, XML-Attributen, Markdown-Syntax und technischen Kontexten erhalten.

Beispiele:

```xml
<def title="Wie installiere ich den Sprachchat?" id="install-voicechat">
```

```md
`Connected your Twitch to Discord`
```

## Markdown und Writerside

Dieses Repository verwendet Writerside. Writerside basiert auf Markdown und erweitert es um eigene XML-Tags, Includes, Variablen und Attribute.

Erhalte Writerside-Markup unverändert, wenn es technisch relevant ist.

Nicht ohne Grund ändern:

* `<include from="..." element-id="..."/>`
* `<tabs>`
* `<tab title="..." id="...">`
* `<deflist>`
* `<def title="..." id="...">`
* `<chapter title="..." id="...">`
* `<tooltip term="...">`
* `{style="note"}`
* `{style="warning"}`
* `{title="..." style="tip"}`
* `%variable%`

### IDs und Links

IDs, Anker und Linkziele dürfen nicht geändert werden, außer es gibt einen zwingenden technischen Grund.

Nicht ändern:

```md
## Handel {id="economy-trading"}
```

```md
[support]: support.md "Support, Erstattungen & Bugreport"
```

```xml
<card href="rules.md" badge="check-list" summary="..."/>
```

Sichtbare Linktexte dürfen verbessert werden, wenn das Ziel gleich bleibt.

## Regeln für Umformulierungen

Beim Überarbeiten gilt:

* Keine Informationen entfernen.
* Keine Zahlen verändern.
* Keine Befehle verändern.
* Keine Links verändern.
* Keine Variablen verändern.
* Keine Regeln abschwächen.
* Keine Regeln verschärfen.
* Keine neuen Behauptungen hinzufügen.
* Keine Beispiele löschen.
* Keine Warnungen oder Hinweise entfernen.

Wenn eine Formulierung unklar ist, bleibe nah am Original.

## Beispiele für gute Überarbeitung

### Ansprache vereinheitlichen

Vorher:

```md
Ihr könnt verschiedene Skills leveln und Belohnungen freischalten.
```

Nachher:

```md
Du kannst verschiedene Skills leveln und Belohnungen freischalten.
```

### Genderform entfernen

Vorher:

```md
Alle Spielenden müssen sich an die Serverregeln halten.
```

Nachher:

```md
Alle Spieler müssen sich an die Serverregeln halten.
```

### Natürlich neutral formulieren

Vorher:

```md
Spielerinnen und Spieler können dem Team Fragen stellen.
```

Nachher:

```md
Die Community kann dem Team Fragen stellen.
```

Nur verwenden, wenn es natürlich klingt.

### Typografie korrigieren

Vorher:

```md
Du erhältst 10% mehr Erfahrung, z. B. beim Mining.
```

Nachher:

```md
Du erhältst 10 % mehr Erfahrung, z. B. beim Mining.
```

## Checkliste vor einem Pull Request

Vor dem Erstellen eines Pull Requests prüfen:

* [ ] Die Ansprache ist einheitlich und verwendet grundsätzlich „du“.
* [ ] Es gibt keine gegenderten Sonderformen wie `Spielende`, `jede*r` oder `Nutzer:innen`.
* [ ] Begriffe wie Survival-Server, Event-Server und Skillsystem sind einheitlich geschrieben.
* [ ] Abkürzungen wie `z. B.` und Prozentangaben wie `10 %` sind korrekt formatiert.
* [ ] Links, IDs, Variablen und Includes funktionieren weiterhin.
* [ ] Markdown- und Writerside-Struktur sind intakt.
* [ ] Keine Information wurde entfernt.
* [ ] Regeln, Warnungen und Hinweise behalten ihre ursprüngliche Bedeutung.
* [ ] Der Writerside-Build wurde ausgeführt oder die geänderten Dateien wurden manuell geprüft.