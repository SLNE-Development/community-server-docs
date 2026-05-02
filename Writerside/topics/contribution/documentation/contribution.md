# Dokumentation Contribution Guide

Willkommen beim Leitfaden für die Mitarbeit an unserer Dokumentation.\
In diesem Dokument erfährst du, wie du mithilfe von **IntelliJ**, **Writerside** und **GitHub** neue Inhalte erstellst
und bestehende überarbeiten kannst.

## Voraussetzungen

Bevor du beginnst, stelle sicher, dass du über Folgendes verfügst:

- Einen [GitHub Account](https://github.com)
- [JetBrains IntelliJ IDEA](https://www.jetbrains.com/de-de/writerside/download/) (installiert und startbereit)
- Grundkenntnisse im Umgang mit Markdown und Git

> Eine saubere, fehlerfreie und übersichtliche Schreibweise ist die Grundvoraussetzung für die Annahme deiner
> Änderungen.
>
{style="note" title="Hinweis"}

## 1. Benötigte Plugins installieren {collapsible="true"}

Wenn du bereits IntelliJ IDEA nutzt, musst du keine separate IDE installieren. Writerside kann einfach als Plugin
hinzugefügt werden.
Damit Commits und Pull Requests automatisch korrekt formatiert werden, benötigst du zusätzlich das Plugin Conventional
Commit.

<procedure title="Writerside Plugin installieren" id="install-plugin-writerside">
<step>
Öffne IntelliJ IDEA.
</step>
<step>

Klicke links unten in der Ecke auf das Zahnrad und Wähle `Settings` aus.
</step>
<step>

Klicke im Einstellungsfenster auf `Plugins`.
</step>
<step>
Stelle sicher, dass der Reiter <code>Marketplace</code> ausgewählt ist, und suche nach <code>Writerside</code>.
</step>
<step>

Klicke auf `Install` neben dem Writerside Plugin.
</step>
<step>
Anschließend muss die IDE neugestartet werden.
</step>
<step>
Nach dem Neustart ist das Plugin installiert und es befindet sich das <b>Writerside Tool Window</b> am linken Rand in geöffneten Projekte.
</step>
</procedure>

<procedure title="Conventional Commit Plugin installieren" id="install-plugin-conventional-commit">
<step>
Öffne IntelliJ IDEA.
</step>
<step>

Klicke links unten in der Ecke auf das Zahnrad und Wähle `Settings` aus.
</step>
<step>

Klicke im Einstellungs-Fenster auf `Plugins`.
</step>
<step>
Stelle sicher, dass der Reiter <code>Marketplace</code> ausgewählt ist, und suche nach <code>Conventional Commit</code>.
</step>
<step>

Klicke auf `Install` neben dem Writerside Plugin.
</step>
<step>
Anschließend muss die IDE neugestartet werden.
</step>
<step>
Nach dem Neustart ist das Plugin installiert.
</step>
</procedure>

## 1. Repository vorbereiten {collapsible="true"}

Damit du Änderungen einreichen kannst, arbeitest du in einer eigenen Kopie des Projekts. Dies nennt man **Fork**.

<procedure title="Repository forken" id="repo-fork">
<step>
Gehe auf die <a href="%git-repo-link%">GitHub Seite der Dokumentation</a>.
</step>
<step>
Stelle sicher, dass du in GitHub mit deinem Account angemeldet bist.
</step>
<step>
Klicke oben rechts auf den Knopf <code>Fork</code>.
<img src="fork-repo-first.png" alt="Fork Repository" style="block" thumbnail="true"/>
</step>
<step>
Klicke auf <code>Create Fork</code>. Nun hast du eine Kopie des Projekts in deinem eigenen GitHub-Account.
</step>
</procedure>

<procedure title="Repository clonen &amp; Projekt öffnen" id="repo-clone">
<step>
Öffne IntelliJ IDEA und wähle <code>Get from VCS</code>.
</step>
<step>
Füge die URL <b>deines geforkten Repositories</b> ein und klicke auf <code>Clone</code>.
<img src="install-writerside-second.png" alt="Get from VCS" style="block" thumbnail="true"/>
</step>
<step>
Das Projekt wird anschließend geöffnet und geladen.
</step>
</procedure>

## 2. Neuen Branch anlegen {collapsible="true"}

Arbeite für jede Änderung in einem eigenen Branch, um die Übersicht zu behalten und Konflikte und Chaos zu vermeiden.

<procedure title="Neuen Branch erstellen" id="create-branch">
<step>
Klicke oben links auf den aktuellen Branch-Namen (meist <code>main</code> oder <code>master</code>).
</step>
<step>
Wähle <code>+ New Branch</code> aus. Nutze für den Namen ein Präfix, um die Art deiner Änderung direkt zu kennzeichnen.

| Präfix      | Beschreibung                              | Beispiel                          |
|:------------|:------------------------------------------|:----------------------------------|
| `feat/`     | Für neue Funktionen oder Features         | `feat/new-login-system`           |
| `fix/`      | Für Fehlerbehebungen (Bugfixes)           | `fix/button-click-issue`          |
| `ver/`      | Für Versionierung und Releases            | `ver/1.0.0`                       |
| `dev/`      | Für Entwicklungszwecke und Experimente    | `dev/experimental-feature`        |
| `chore/`    | Für Routineaufgaben und Wartung           | `chore/update-dependencies`       |
| `refactor/` | Code-Refactorings ohne Funktionsänderung  | `refactor/improve-modularization` |
| `test/`     | Für Änderungen an Tests                   | `test/add-new-unit-tests`         |
| `hotfix/`   | Dringende Korrekturen (Sofort-Deployment) | `hotfix/security-patch`           |
| `docs/`     | Für Änderungen an der Dokumentation       | `docs/update-readme`              |
| `perf/`     | Für Performance-Verbesserungen            | `perf/optimize-query-performance` |
| `style/`    | Für Code-Stil und Formatierungsänderungen | `style/fix-indentation`           |
| `opt/`      | Für allgemeine Optimierungsaufgaben       | `opt/7-optimize-packet-operation` |

</step>

<step>
Es wird nun ein neuer Branch mit dem angegebenen namen erstellt. In diesem arbeitest du nun weiter.
</step>

> Achte darauf, dass du dich **vor dem Erstellen des Branches** auf dem aktuellen Stand des `master`-Branches befindest,
> um spätere Konflikte zu vermeiden.
>
{style="warning" title="Wichtig"}

</procedure>

## 3. Dokumentation bearbeiten {collapsible="true"}

Wenn du einen neuen Branch erstellt hast, kannst du nun die Dokumentation bearbeiten und beispielsweise eine neue Seiten
einfügen.

<procedure title="Neue Seite anlegen" id="create-page">
<step>

Öffne das Writerside Tool Window (links am Rand) und klicke auf `+` und wähle `Empty MD Topic`.
</step>
<step>
Verwende für den Dateinamen Kleinschreibung, Englisch und Bindestriche (z. B. setup-guide.md).
Der Anzeigename ist frei wählbar.
</step>
<step>

Bestätige die Abfrage "Add file to Git" mit `Add`.
</step>
<step>
Ziehe die neue Datei im Projekt-Explorer in den entsprechenden Unterordner innerhalb Verzeichnisses.#
<img src="write-documentation-seventh.gif" alt="Move File" thumbnail="true"/>
</step>
<step>
Die neue Seite wurde erfolgreich erstellt und kann nun bearbeitet werden.
</step>
</procedure>

## 4. Mardown Grundlagen {collapsible="true"}

<deflist>

<def title="Fett" id="bold">
        Verwende <code>**Text**</code>, um wichtige Begriffe hervorzuheben. <br/>
        Beispiel: <b>Dieser Text ist fettgedruckt</b>
</def>
<def title="Kursiv" id="italic">
        Verwende <code>*Text*</code> für dezente Betonungen. <br/>
        Beispiel: <i>Dieser Text ist kursiv</i>
</def>
<def title="Durchgestrichen" id="strikethrough">
        Verwende <code>~~Text~~</code>, um veraltete Infos zu markieren. <br/>
        Beispiel: <strike>Dieser Text ist durchgestrichen</strike>
</def>
<def title="Links" id="links">
        Nutze <code>[Text](URL)</code> für Verweise. <br/>
        Beispiel: <a href="https://www.google.com">Google</a>
</def>
<def title="Code" id="code">
        Nutze einzelne Backticks (<code>`code`</code>) für Befehle oder Variablennamen im fließenden Text.
        Beispiel: Für jede aktive Spielstunde erhältst du <code>%paycheck% %main_currency%s</code>.
</def>
<def title="Codeblöcke" id="code-blocks">
        Für mehrzeiligen Code verwende dreifache Backticks (<code>``` code ```</code>) mit Angabe der Sprache: 
<code-block>
        java
        public void hello() {
            System.out.println("Hello World");
        }
</code-block>
</def>
<def title="Bilder" id="images">
        Nutze <code>![Alternativer Text](dateiname.png)</code> um Bilder einzufügen. <br/>
<note>Bilder müssen zwingend im Ordner <code>images</code> liegen, damit sie im Build korrekt angezeigt werden.</note>
</def>
</deflist>

> Es gibt noch viel mehr Formatierungen, die du verwenden kannst. Eine vollständige Dokumentation dazu findest du
> direkt auf der [WriterSide Dokumentation](https://www.jetbrains.com/help/writerside/markup-reference.html). \
> Dort wird unter anderem erklärt, wie du Tabellen, Listen, Überschriften und mehr erstellen kannst.
>
{style="note"}

Das waren einige grundlegende Markdown-Formatierungsanweisungen, die du in WriterSide verwenden kannst. Du kannst diese
Formatierungen kombinieren, um deinen Text nach deinen Vorstellungen zu gestalten.

## 5. Änderungen veröffentlichen {collapsible="true"}

Sobald deine Texte fertig sind, müssen sie über Git gespeichert und hochgeladen werden, damit sie für andere sichtbar werden.

<procedure title="Committen und Pushen" id="publish-changes">
    <step>
        <b>Commit-Fenster öffnen:</b> Klicke links am Rand auf das <code>Commit</code>-Icon oder drücke <code>Strg + K</code>.
        <img src="publish-changes-first.png" alt="Commit Fenster" style="block"/>
    </step>
    <step>
        <b>Dateien wählen:</b> Markiere alle Dateien, die du geändert oder neu erstellt hast.
    </step>
    <step>
        <b>Commit-Nachricht erstellen:</b> Klicke auf das Icon <code>Build Commit Message</code> (Conventional Commit Plugin), um den Dialog zu öffnen.
        <img src="publish-changes-third.png" alt="Build Commit Message" style="block" thumbnail="true"/>
    </step>
    <step>
        <b>Details ausfüllen:</b> Fülle die Felder im Pop-up wie folgt aus:
        <list style="bullet">
            <li><b>Type:</b> Art der Änderung (z. B. <code>feat</code> für neue Inhalte, <code>fix</code> für Korrekturen).</li>
            <li><b>Scope:</b> Der betroffene Bereich (z. B. <code>docs</code>).</li>
            <li><b>Subject:</b> Eine kurze, prägnante Zusammenfassung auf Englisch.</li>
            <li><b>Body:</b> (Optional) Eine detailliertere Beschreibung der Änderungen.</li>
        </list>
    </step>
    <step>
        <b>Absenden:</b> Klicke unten auf den Pfeil neben <code>Commit</code> und wähle <code>Commit and Push...</code>. Bestätige den anschließenden Dialog mit <code>Push</code>.
        <img src="publish-changes-fifth.png" alt="Commit and Push" style="block" thumbnail="true"/>
    </step>
</procedure>

<procedure title="Pull Request auf GitHub erstellen" id="create-pr">
    <step>
        Gehe auf GitHub zur Seite <b>deines</b> geforkten Repositories.
    </step>
    <step>
        Klicke auf den Button <code>Contribute</code> und wähle <code>Open pull request</code>.
        <note>Vergewissere dich, dass oben der richtige Branch ausgewählt ist, in dem du gearbeitet hast.</note>
        <img src="open-pull-request.png" alt="Pull Request öffnen" style="block" thumbnail="true"/>
    </step>
    <step>
        <b>Titel und Beschreibung:</b> Gib deinem PR einen aussagekräftigen Namen und beschreibe kurz, was geändert wurde. Klicke dann auf <code>Create pull request</code>.
    </step>
    <step>
        <b>Review abwarten:</b> Dein Beitrag wird nun vom Team geprüft. Falls es Anmerkungen gibt, kannst du diese einfach in deinem lokalen Projekt korrigieren und erneut pushen – der PR aktualisiert sich automatisch.
    </step>
</procedure>