<primary-label ref="event-upcoming"/>
<secondary-label ref="ca14-event-mc-version"/>
<secondary-label ref="no-date"/>

# CraftAttack-Ölbohrinsel-Bau-Event

## Über das Event {id="general-info"}

Deine Kreativität ist wieder gefragt! Heikos Base in CraftAttack 14 ist eine Ölbohrinsel und dafür sucht er
wieder deine Ideen. Entwirf eigene Module und Details, die die Bohrinsel ergänzen. Vielleicht greift Heiko am Ende
genau deinen Entwurf auf und setzt ihn in CraftAttack 14 um.

Am Spawn kannst du dir die Ölbohrinsel aus nächster Nähe ansehen und Inspiration sammeln. Anschließend sicherst du
dir dein eigenes Grundstück und legst im Creative-Modus los. Du kannst allein bauen oder gemeinsam mit anderen
Spielern kreativ werden.

> Du warst schon beim [CraftAttack-Schiff-Bau-Event](ca13-event.md) dabei? Dann kennst du den Ablauf bereits.
> Neu ist diesmal:
>
> - Du kannst bis zu **zwei Grundstücke** beanspruchen und sie mit `/p merge` zusammenlegen, wenn sie direkt
>   nebeneinander liegen.
> - Der **Axiom Editor Mode** steht diesmal allen Spielern zur Verfügung, auch ohne Veteranen- oder Premium-Rang.
>
{style="tip" title="Was ist neu?"}

## Deine Ideen für Heikos Ölbohrinsel {id="oil-rig-ideas"}

Deine Idee soll keine vollständige Ölbohrinsel sein. Im Mittelpunkt stehen einzelne Module und Details, die zu
Heikos Bohrinsel passen und sie noch lebendiger machen.

## Sichere dir dein Grundstück {id="claim-and-build"}

Jetzt bist du dran! Mit `/p claim` beanspruchst du das Grundstück, auf dem du dich gerade befindest. Alternativ weist
dir `/p auto` automatisch ein freies Grundstück zu. Jeder Spieler kann bis zu zwei Grundstücke mit einer Größe von
jeweils `100 × 100 Blöcken` beanspruchen.

Liegen deine beiden Grundstücke direkt nebeneinander, kannst du sie mit `/p merge` zu einem großen Grundstück
zusammenlegen. Stelle dich dazu auf eines der beiden Grundstücke und schau in Richtung des anderen. So hast du mehr
Platz für größere Module.

Bei der Erstellung deines Grundstücks wird automatisch ein Home-Punkt gesetzt. Mit `/home` kannst du jederzeit
dorthin zurückkehren. Du möchtest nicht allein bauen? Dann erteile anderen Spielern mit `/trust <Spieler>` Baurechte
auf deinem Grundstück. So könnt ihr eure Ideen gemeinsam umsetzen.

Das genaue Datum und die Laufzeit des Events werden noch bekannt gegeben. Du kannst während der gesamten Laufzeit
jederzeit einsteigen und ein Grundstück beanspruchen.

## Entdecke die Ideen der Community {id="discover-and-like"}

Du möchtest einfach nur sehen, was die Community erschafft? Kein Problem: Fliege jederzeit frei durch die Eventwelt
und schau dir die Entwürfe auf anderen Grundstücken an. Wenn dich eine Idee begeistert, kannst du das Grundstück mit
`/like` bewerten.

Die Likes zeigen Heiko, welche Ideen der Community besonders gefallen. Die endgültige Auswahl trifft Heiko jedoch selbst.

## Verfügbare Blöcke und Items {id="available-content"}

Du trittst dem Event mit **Minecraft 26.3** bei. Beim Bauen stehen dir alle Blöcke und Items dieser Version zur
Verfügung.

## Regeln {id="rules"}

<include from="util.md" element-id="no-rules-changed" />

## Befehle {id="commands"}

Folgende Befehle kannst du während des Events verwenden:

### Grundstück beanspruchen und verwalten {collapsible="true" default-state="collapsed" id="commands-plot"}

`/p claim` {id="command-plot-claim"}
: Beansprucht das Grundstück, auf dem du dich gerade befindest.

`/p auto` {id="command-plot-auto"}
: Weist dir automatisch ein freies Grundstück zu.

`/p merge` {id="command-plot-merge"}
: Legt das Grundstück, auf dem du dich gerade befindest, mit deinem zweiten Grundstück zusammen. Schau dabei in
Richtung des anderen Grundstücks. Das funktioniert nur, wenn beide Grundstücke dir gehören und direkt nebeneinander
liegen.

`/p clear` {id="command-plot-clear"}
: Entfernt alle Bauwerke und Blöcke von deinem Grundstück, ohne das Grundstück aufzugeben.

`/p delete` {id="command-plot-delete"}
: Löscht dein Grundstück und gibt es wieder frei.

> Mit `/p clear` und `/p delete` entfernst du deinen bisherigen Baufortschritt. Prüfe deshalb vor der Ausführung
> sorgfältig, welchen Befehl du verwenden möchtest.
>
{style="warning"}

### Gemeinsam bauen {collapsible="true" default-state="collapsed" id="commands-trust"}

`/trust <Spieler>` {id="command-trust"}
: Erteilt dem angegebenen Spieler Baurechte auf deinem Grundstück.

`/untrust <Spieler>` {id="command-untrust"}
: Entzieht dem angegebenen Spieler die zuvor erteilten Baurechte.

### Spieler verwalten {collapsible="true" default-state="collapsed" id="commands-visitors"}

`/p kick <Spieler>` {id="command-plot-kick"}
: Entfernt den angegebenen Spieler einmalig von deinem Grundstück.

`/p deny <Spieler>` {id="command-plot-deny"}
: Sperrt den angegebenen Spieler für dein Grundstück.

### Spawn & Homes {collapsible="true" default-state="collapsed" id="commands-home"}

`/spawn` {id="command-spawn"}
: Teleportiert dich zum Spawn der Eventwelt.

`/sethome` {id="command-sethome"}
: Setzt den bei der Grundstückserstellung automatisch angelegten Home-Punkt an deine aktuelle Position um. Du kannst
den Befehl nur auf deinem eigenen Grundstück verwenden.

`/home` {id="command-home"}
: Teleportiert dich zu deinem Home-Punkt auf dem Grundstück.

### Grundstück bewerten {collapsible="true" default-state="collapsed" id="commands-like"}

`/like` {id="command-like"}
: Bewertet das Grundstück, auf dem du dich gerade befindest.

## Tools und Plugins {id="tools"}

Um dir das Bauen zu erleichtern, stehen dir auf deinem Grundstück folgende Tools zur Verfügung:

- [**WorldEdit**](https://intellectualsites.gitbook.io/fastasyncworldedit)
- [**Axiom Builder Mode**](https://axiomdocs.moulberry.com/builder/intro.html)
- [**Axiom Editor Mode**](https://axiomdocs.moulberry.com/editor/intro.html)

> Da nun alle Spieler Axiom nutzen können, müssen wir jedoch einem Missbrauch vorbeugen. Deshalb sind, wie bei
> WorldEdit, diesmal auch bei Axiom einige Blöcke gesperrt. Für Spieler mit Veteranen- oder Premium-Rang fallen die
> Einschränkungen bei Axiom jedoch etwas geringer aus, da wir das Missbrauchsrisiko bei ihnen als geringer einschätzen.
> Wir behalten uns vor, diese Beschränkungen während des Events jederzeit nach Bedarf anzupassen.
>
{style="note"}

## Häufige Fragen {id="q-a"}

{collapsible="true" default-state="collapsed"}
Was soll ich bauen? {id="event-building-goal"}
: Entwirf eigene Module und Details für Heikos Ölbohrinsel in CraftAttack 14. Die Bohrinsel kannst du dir am Spawn
ansehen.

Wann findet das Event statt? {id="event-date"}
: Ein genaues Datum steht noch nicht fest. Es wird bekannt gegeben, sobald es feststeht.

Welche Minecraft-Version benötige ich? {id="event-mc-version"}
: Du musst dem Event mit **Minecraft 26.3** beitreten. Zum Bauen stehen dir alle Blöcke und Items dieser Version zur
Verfügung.

Wie viele Grundstücke kann ich beanspruchen? {id="event-plot-count"}
: Du kannst bis zu zwei Grundstücke beanspruchen. Liegen sie direkt nebeneinander, kannst du sie mit `/p merge` zu
einem großen Grundstück zusammenlegen.

Kann ich auch später einsteigen? {id="event-join-later"}
: Ja, du kannst während der gesamten Laufzeit jederzeit in das Event einsteigen und ein Grundstück beanspruchen.

Kann ich gemeinsam mit anderen Spielern bauen? {id="event-build-together"}
: Ja, du kannst anderen Spielern mit `/trust <Spieler>` Baurechte auf deinem Grundstück erteilen.

Brauche ich einen Rang, um Axiom zu nutzen? {id="event-axiom"}
: Nein, der Axiom Builder Mode und der Axiom Editor Mode stehen bei diesem Event allen Spielern zur Verfügung. Um
Missbrauch vorzubeugen, sind jedoch wie bei WorldEdit einige Blöcke für Axiom gesperrt.

Wie werden die Likes ausgewertet? {id="event-likes"}
: Die Likes zeigen Heiko die Favoriten der Community. Die endgültige Auswahl trifft Heiko selbst.

Was passiert, wenn ich gegen die Regeln verstoße? {id="event-rules"}
: Regelverstöße werden ernst genommen und können zum dauerhaften Ausschluss vom gesamten Server führen. Halte dich
bitte an die Regeln, um ein faires und spaßiges Event für alle zu gewährleisten.
