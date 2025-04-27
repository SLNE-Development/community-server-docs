<primary-label ref="event-running"/>
<secondary-label ref="ca-cube-all-mc-version"/>
<secondary-label ref="ca-cube-all-date"/>

# CraftAttack Würfel Bau Event

## Über das Event {id="general-info"}

Das Streamer-Projekt **CraftAttack 12** neigt sich dem Ende. Das Problem ist: Das Bau-Projekt von CastCrafter, ein Würfel, ist noch nicht fertig.
In diesem Event habt ihr die Möglichkeit, einen Teil des Würfels zu bauen.

Das Ziel: Den CraftAttack Würfel mithilfe der Community fertigzustellen. **CastCrafter** wird am Ende des Events die besten Würfel auswählen und diese in CraftAttack nachbauen.
Jeder baut seinen eigenen Würfel. Deinen Plot kannst du mit `/plot auto` claimen und mit `/plot home` jederzeit betreten.
Wenn du mit einer Gruppe von Freunden bauen möchtest, kannst du andere Spieler mit `/plot trust <Spieler>` zu deinem Plot einladen.
>
> **Achtung:** Der Würfel muss die Maße `44x44x44` Blöcke haben. Das bedeutet, dass die Grundfläche 44x44 Blöcke groß ist und die Höhe 44 Blöcke beträgt.
> 
> {style="warning"}

![thumbnail](ca-building-event.png){border-effect="rounded"}


## Regeln {id="rules"}

> Neben den allgemeinen Serverregeln, welche ihr [hier](rules.md) einsehen k&ouml;nnt, gilt folgender Zusatz:
>
> In diesem Event ist die Nutzung von **Litematica und / oder anderen Schematic Mods nicht gestattet** und kann zu einem Ausschluss führen!
>
{style="warning" title="Es gibt geänderte Regeln speziell für dieses Event!"}

## Befehle {id="commands"}
Folgende Befehle können während des Events verwendet werden:

#### Plots beanspruchen {collapsible="true" default-state="collapsed" id="commands-claim"}

/plot claim {id="plot-claim-command"}
: Beansprucht das Plot, auf dem du dich aktuell befindest.

#### Teleportieren {collapsible="true" default-state="collapsed" id="commands-teleport"}

/plot home {id="plot-home"}
: Teleportiert dich zu deinem Plot.

/plot kick &lt;player | *&gt; {id="plot-kick-command"}
: Wirft einen Spieler von deinem Plot.

#### Plot-Einstellungen verändern {collapsible="true" default-state="collapsed" id="commands-settings"}

/plot trust &lt;player | *&gt; {id="plot-trust-command"} 
: Erteilt einem Spieler Baurechte, auch wenn du offline bist.

/plot add &lt;player | *&gt; {id="plot-add-command"} 
: Erlaubt einem Spieler, auf deinem Plot zu bauen, solange du online bist.

/plot remove &lt;player | *&gt; {id="plot-remove-command"}  
: Hebt die mit `/plot trust` oder `/plot add` vergebenen Baurechte auf.

#### Plot-Informationen abrufen {collapsible="true" default-state="collapsed" id="commands-info"}

/plot info &lt;id&gt; {id="command-plot-info"} 
: Zeigt Informationen zu einem Plot an.

## Geänderte Mechaniken {id="changed-mechanics"}
Um den Server stabil zu halten und den Supportaufwand zu minimieren, wurden für das Event einige Mechaniken geändert oder deaktiviert.

- Redstone ist deaktiviert
- Items können weder gedroppt noch aufgehoben werden
- Nether und End sind deaktiviert
- Es stehen nur reguläre Items zur Verfügung; modifizierte Items (z. B. aus dem Singleplayer) sind nicht nutzbar
- Mit Ausnahme von ArmorStands und ItemFrames gibt es keine Entities und es können auch keine gespawnt werden
- Einige Blöcke werden nicht getickt. Dies betrifft z. B. LeafDecay, CropGrowth und FarmlandMoisture

### VoiceChat {id="voicechat"}

In diesem Event steht euch ein Ingame-VoiceChat zur Verfügung, über welchen ihr mit anderen Spielern sprechen könnt.

Um den VoiceChat benutzen zu können, müsst ihr euch die SimpleVoiceChat Mod installieren.

Den Download der Mod findet ihr hier: [SimpleVoiceChat](https://modrinth.com/plugin/simple-voice-chat)


## Q&amp;A {id="q-a"}

{collapsible="true" default-state="collapsed"}
Welche Version von Minecraft wird benötigt? {id="event-mc-version"}
: Das Event wird in der Version **1.21.4/5** stattfinden.

Was passiert, wenn ich gegen die Regeln verstoße? {id="event-rules"}
: Regelverstöße werden ernst genommen und können zum dauerhaften Ausschluss vom gesamten Server führen. Haltet euch
bitte an die Regeln, um ein faires und spaßiges Event für alle zu gewährleisten und beachtet die Eventspezifischen Regeln für dieses Event!

Kann man auch später noch dem Event beitreten? {id="event-join-later"}
: Ja, auch wenn das Event bereits begonnen hat, kannst du jederzeit dem Event beitreten. Wenn allerdings die maximale
Spieleranzahl erreicht ist, kann es sein, dass du dich in die Warteschlange einreihen musst.