
# Geänderte Vanilla Mechaniken

## Spawn limits {collapsible="true" default-state="collapsed" id="spawn-limits"}

Spawn Limit
: Die Anzahl an Mobs, welche natürlich spawnen können.

<table style="both">
<tr>
    <td></td>
    <td>Vanilla</td>
    <td>Community Server</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="spawn-limits-ambient" summary="%click-more-info%">Ambient</a></td>
    <td>15</td>
    <td>4</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="spawn-limits-axolotl" summary="%click-more-info%">Axolotl</a></td>
    <td>5</td>
    <td>3</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="spawn-limits-monster" summary="%click-more-info%">Monster</a></td>
    <td>70</td>
    <td>25</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="spawn-limits-water-ambient" summary="%click-more-info%">Wasser Ambient</a></td>
    <td>20</td>
    <td>10</td>
</tr>
</table>


<deflist id="spawn-limits-def" collapsible="true" default-state="collapsed" type="medium">
<def title="Ambient" id="spawn-limits-ambient">
Die Konstante, die verwendet wird, um zu bestimmen, wie viele Umgebungsmobs pro Welt natürlich gespawnt werden sollen.
</def>
<def title="Axolotl" id="spawn-limits-axolotl">
Die Konstante, die verwendet wird, um zu bestimmen, wie viele Axolotl pro Welt natürlich gespawnt werden sollen.
</def>
<def title="Monster" id="spawn-limits-monster">
Die Konstante, die verwendet wird, um zu bestimmen, wie viele Monster pro Welt natürlich gespawnt werden sollen.
</def>
<def title="Wasser Ambient" id="spawn-limits-water-ambient">
Die Konstante, die verwendet wird, um zu bestimmen, wie viele Wasser Ambient Mobs pro Welt natürlich gespawnt werden sollen.
</def>
</deflist>

## Ticks-Per-Einstellungen {collapsible="true" default-state="collapsed" id="ticks-per-settings"}

Ticks-Per
: Bestimmt, wie oft bestimmte Ereignisse pro Spiel-Tick passieren.

<table style="both">
<tr>
    <td></td>
    <td>Vanilla</td>
    <td>Community Server</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-ambient-spawn" summary="%click-more-info%">Ambient Spawn</a></td>
    <td>1</td>
    <td>400</td>
</tr>
<tr>
<td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-animal-spawn" summary="%click-more-info%">Tiere Spawn</a></td>
    <td>400</td>
    <td>300</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-axolotl-spawn" summary="%click-more-info%">Axolotl Spawn</a></td>
    <td>1</td>
    <td>400</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-monster-spawn" summary="%click-more-info%">Monster Spawn</a></td>
    <td>1</td>
    <td>10</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-water-ambient-spawn" summary="%click-more-info%">Wasser Ambient Spawn</a></td>
    <td>1</td>
    <td>200</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-water-spawn" summary="%click-more-info%">Wasser Spawn</a></td>
    <td>1</td>
    <td>100</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-water-underground-spawn" summary="%click-more-info%">Wasser Untergrund Spawn</a></td>
    <td>1</td>
    <td>200</td>    
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-hopper-check" summary="%click-more-info%">Trichter Check</a></td>
    <td>1</td>
    <td>4</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-hopper-transfer" summary="%click-more-info%">Trichter Transfer</a></td>
    <td>1</td>
    <td>8</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-container-update" summary="%click-more-info%">Container Update</a></td>
    <td>1</td>
    <td>3</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-grass-spread" summary="%click-more-info%">Verbreitung von Gras</a></td>
    <td>1</td>
    <td>4</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="ticks-per-mob-spawner" summary="%click-more-info%">Mob Spawner</a></td>
    <td>1</td>
    <td>2</td>
</tr>
</table>

<deflist id="ticks-per-settings-def" collapsible="false" default-state="collapsed" type="medium">
<def title="Ambient Spawn" id="ticks-per-ambient-spawn">
Anzahl der Ticks zwischen jedem Versuch, Umgebungsmobs zu spawnen
</def>
<def title="Tiere Spawn" id="ticks-per-animal-spawn">
Anzahl der Ticks zwischen jedem Versuch, Tiere zu spawnen
</def>
<def title="Axolotl" id="ticks-per-axolotl-spawn">
Anzahl der Ticks zwischen jedem Versuch, Axolotl zu spawnen
</def>
<def title="Monster" id="ticks-per-monster-spawn">
Anzahl der Ticks zwischen jedem Versuch, Monster zu spawnen
</def>
<def title="Wasser Ambient" id="ticks-per-water-ambient-spawn">
Anzahl der Ticks zwischen jedem Versuch, Wasser Ambient Mobs zu spawnen
</def>
<def title="Wasser Spawn" id="ticks-per-water-spawn">
Anzahl der Ticks zwischen jedem Versuch, Wasser Mobs zu spawnen
</def>
<def title="Wasser Untergrund Spawn" id="ticks-per-water-underground-spawn">
Anzahl der Ticks zwischen jedem Versuch, Wasser Untergrund Mobs zu spawnen
</def>
<def title="Trichter Check" id="ticks-per-hopper-check">
Die Anzahl der Ticks, die zwischen den Überprüfungen vergehen, um Gegenstände aus oder in einen Trichter zu ziehen.
</def>
<def title="Trichter Transfer" id="ticks-per-hopper-transfer">
Die Anzahl der Ticks, die zwischen den Bewegungen von Gegenständen in einem Trichter vergehen.
</def>
<def title="Container Update" id="ticks-per-container-update">
Die Anzahl der Ticks, die zwischen den Aktualisierungen von Containern und Inventaren vergehen.
</def>
<def title="Verbreitung von Gras" id="ticks-per-grass-spread">
Die Anzahl der Ticks, die zwischen den Versuchen vergehen, Gras zu verbreiten.
</def>
<def title="Mob Spawner" id="ticks-per-mob-spawner">
Die Anzahl der Ticks, die zwischen den Versuchen vergehen, Monster aus einem Mob Spawner zu spawnen.
</def>
</deflist>

## Welt-Einstellungen {collapsible="true" default-state="collapsed" id="world-settings"}

### Entity activation range {collapsible="true" default-state="collapsed" id="entity-activation-range"}

Entity Activation Range
: Bestimmt die Distanz (in Blöcken), in der Entitäten aktiv sind.

<table style="both">
<tr>
    <td></td>
    <td>Vanilla</td>
    <td>Community Server</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="entity-activation-range-animals" summary="%click-more-info%">Tiere</a></td>
    <td>32</td>
    <td>16</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="entity-activation-range-monsters" summary="%click-more-info%">Monster</a></td>
    <td>32</td>
    <td>24</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="entity-activation-range-misc" summary="%click-more-info%">Sonstige</a></td>
    <td>16</td>
    <td>8</td>
</tr>
</table>

<deflist id="entity-activation-range-def" collapsible="true" default-state="collapsed" type="medium">
<def title="Tiere" id="entity-activation-range-animals">
Die Entfernung, in der Tiere aktiv sind.
</def>
<def title="Monster" id="entity-activation-range-monsters">
Die Entfernung, in der Monster aktiv sind.
</def>
<def title="Sonstige" id="entity-activation-range-misc">
Die Entfernung, in der sonstige Entitäten aktiv sind.
</def>
</deflist>

### Verschmelzungsradius {collapsible="true" default-state="collapsed" id="merge-radius"}

Verschmelzungsradius
: Bestimmt die Distanz (in Blöcken), in der mehrere Entitäten zu einer verschmelzen.

<table style="both">
<tr>
    <td></td>
    <td>Vanilla</td>
    <td>Community Server</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="merge-radius-item" summary="%click-more-info%">Items</a></td>
    <td>2.5</td>
    <td>3.5</td>
</tr>
<tr>
    <td><a href="changed-vanilla-mechanics.md" anchor="merge-radius-xp" summary="%click-more-info%">XP</a></td>
    <td>3</td>
    <td>5</td>
</tr>
</table>

<deflist id="merge-radius-def" collapsible="true" default-state="collapsed" type="medium">
<def title="Items" id="merge-radius-item">
Der Radius, in dem mehrere kleinere stacks von Items zu einem größeren verschmelzen.
</def>
<def title="XP" id="merge-radius-xp">
Der Radius, in dem mehrere kleinere stacks von XP zu einem größeren verschmelzen.
</def>
</deflist>

## DAB (Distance Activation Brain) {collapsible="true" default-state="collapsed" id="dab"}

DAB
: DAB (Distance Activation Brain) ist eine fortschrittliche Serveroptimierung, die speziell dafür entwickelt wurde, die
Leistung von Minecraft-Servern zu verbessern. Diese Funktion beeinflusst, wie häufig die "Gehirn-Ticks" von bestimmten
Entitäten ausgeführt werden. Gehirn-Ticks sind für die Ausführung der KI und für Verhaltensmuster von Entitäten wie
zum Beispiel das Bewegen, Angreifen, Essen, etc. verantwortlich. Diese Ticks sind jedoch sehr
ressourcenintensiv und werden daher durch DAB effizienter gestaltet.


<table style="both">
<tr>
    <td></td>
    <td>Wert</td>
    <td>Beschreibung</td>
</tr>
<tr>
    <td>Start Distanz</td>
    <td>12 Blöcke</td>
    <td>Definiert die Mindestdistanz in Blöcken, in denen DAB <b>nicht</b> aktiv ist. Das bedeutet, dass Entitäten, 
    die sich näher als 12 Blöcke an einem Spieler befinden, normal agieren und ihre Gehirn-Ticks nicht durch 
    DAB beeinflusst werden.</td>
</tr>
<tr>
    <td>Maximale Tick-Frequenz</td>
    <td>20 Ticks</td>
    <td>Legt die maximale Tick-Frequenz fest. Egal wie die Berechnung ausfällt, eine Entität wird nicht seltener als
    einmal alle 20 Ticks (entspricht etwa einer Sekunde im Spiel) aktualisiert. Dies stellt sicher, dass Entitäten 
    auch in weiterer Entfernung eine grundlegende Aktivität beibehalten.</td>
</tr>
<tr>
    <td>Aktivierungs-Distanz Modifikator</td>
    <td>8.0</td>
    <td>Dieser Wert steuert, wie die Entfernung zum Spieler die Tick-Frequenz der Entität beeinflusst. Je höher der Wert,
    desto schneller werden die Gehirn-Ticks ausgeführt. </td>
</tr>
</table>

## Despawn-Regeln {collapsible="true" default-state="collapsed" id="despawn-rules"}

### Despawn-Regeln für Items {collapsible="true" default-state="collapsed" id="item-despawn-rules"}

Item Despawn Rules
: Bestimmt, wann Items despawnen.

<table style="both">
<tr>
    <td></td>
    <td>Vanilla</td>
    <td>Community Server</td>
</tr>
<!-- Arrow -->
<tr>
    <td>Pfeil</td>
    <td>1.200 (1m)</td>
    <td>600 (30s)</td>
</tr>
<!-- acacia_leaves, birch_leaves, dark_oak_leaves, jungle_leaves, oak_leaves -->
<tr>
    <td>Blätter</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Andesite -->
<tr>
    <td>Andesit</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Bamboo -->
<tr>
    <td>Bambus</td>
    <td>6.000 (5m)</td>
    <td>800 (40s)</td>
</tr>
<!-- Cactus -->
<tr>
    <td>Kaktus</td>
    <td>6.000 (5m)</td>
    <td>800 (40s)</td>
</tr>
<!-- Cobblestone -->
<tr>
    <td>Cobblestone</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Diorite -->
<tr>
    <td>Diorit</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Dirt -->
<tr>
    <td>Dreck</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Golden Sword -->
<tr>
    <td>Goldenes Schwert</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Granite -->
<tr>
    <td>Granit</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Grass -->
<tr>
    <td>Gras</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Gravel -->
<tr>
    <td>Kies</td>
    <td>6.000 (5m)</td>
    <td>2.400 (2m)</td>
</tr>
<!-- Kelp -->
<tr>
    <td>Seetang</td>
    <td>6.000 (5m)</td>
    <td>800 (40s)</td>
</tr>
<!-- Melon Slice -->
<tr>
    <td>Wassermelone</td>
    <td>6.000 (5m)</td>
    <td>800 (40s)</td>
</tr>
<!-- Netherrack -->
<tr>
    <td>Netherrack</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Pumpkin -->
<tr>
    <td>Kürbis</td>
    <td>6.000 (5m)</td>
    <td>800 (40s)</td>
</tr>
<!-- Red Sand -->
<tr>
    <td>Roter Sand</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Sand -->
<tr>
    <td>Sand</td>
    <td>6.000 (5m)</td>
    <td>2.400 (2m)</td>
</tr>
<!-- Scaffolding -->
<tr>
    <td>Gerüst</td>
    <td>6.000 (5m)</td>
    <td>900 (45s)</td>
</tr>
<!-- Sugar Cane -->
<tr>
    <td>Zuckerrohr</td>
    <td>6.000 (5m)</td>
    <td>800 (40s)</td>
</tr>
<!-- Twisting Vines -->
<tr>
    <td>Verdrehte Ranken</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
<!-- Weeping Vines -->
<tr>
    <td>Weinende Ranken</td>
    <td>6.000 (5m)</td>
    <td>600 (30s)</td>
</tr>
</table>

### Despawn-Regeln für Entitäten {collapsible="true" default-state="collapsed" id="entity-despawn-rules"}


Entity Despawn Rules
: Bestimmt, wann Entitäten despawnen.

<table style="both">
<tr>
    <td></td>
    <td>Vanilla Soft</td>
    <td>Vanilla Hard</td>
    <td>Community Server Soft</td>
    <td>Community Server Hard</td>
</tr>
<tr>
    <td>Ambient</td>
    <td>32</td>
    <td>128</td>
    <td>28</td>
    <td>72</td>
</tr>
<tr>
    <td>Axolotl</td>
    <td>32</td>
    <td>128</td>
    <td>28</td>
    <td>72</td>
</tr>
<tr>
    <td>Monster</td>
    <td>32</td>
    <td>128</td>
    <td>28</td>
    <td>72</td>
</tr>
<tr>
    <td>Wasser Kreatur</td>
    <td>32</td>
    <td>128</td>
    <td>28</td>
    <td>72</td>
</tr>
<tr>
    <td>Kreatur</td>
    <td>N/A</td>
    <td>128</td>
    <td>N/A</td>
    <td>72</td>
</tr>
<tr>
    <td>Untergrund Wasser Kreatur</td>
    <td>N/A</td>
    <td>128</td>
    <td>N/A</td>
    <td>72</td>
</tr>
<tr>
    <td>Wasser Ambient</td>
    <td>32</td>
    <td>N/A</td>
    <td>28</td>
    <td>N/A</td>
</tr>
<tr>
    <td>Sonstige</td>
    <td>N/A</td>
    <td>128</td>
    <td>N/A</td>
    <td>72</td>
</tr>
</table>

<deflist collapsible="true" default-state="collapsed">
<def title="Soft Despawn Range" id="soft-despawn-range">
Die "Soft Despawn Range" bezeichnet die Distanz in Blöcken um einen Spieler herum, außerhalb derer verschiedene
Entitätentypen (für jeden Typ individuell festgelegt) zufällig zum Verschwinden ausgewählt werden können. 
Diese Regel gilt nur horizontal.

<tip>
In einfacheren Worten: Wenn eine Entität – wie ein Monster, Tier oder eine andere Kreatur – sich außerhalb dieser festgelegten Distanz zum Spieler befindet, kann sie zufällig despawnen.
</tip>
</def>
<def title="Hard Despawn Range" id="hard-despawn-range">
Die "Hard Despawn Range" bezeichnet die Distanz in Blöcken um einen Spieler herum, außerhalb derer verschiedene
Entitätentypen (für jeden Typ individuell festgelegt) auf jeden Fall despawnen. 
Diese Regel gilt nur horizontal.

<tip>
In einfacheren Worten: Wenn eine Entität – wie ein Monster, Tier oder eine andere Kreatur – sich außerhalb dieser festgelegten Distanz zum Spieler befindet, wird sie auf jeden Fall despawnen.
</tip>
</def>
</deflist>

## Angelbare Gegenstände {collapsible="true" default-state="collapsed" id="additionally-fishing-loot"}

<include from="util.md" element-id="additionally-fishing-loot"></include>

## Kompostierbare Items {collapsible="true" default-state="collapsed" id="compostable-items"}

<include from="util.md" element-id="compostable-items"></include>

## Vermehrung der Hilfsgeister {collapsible="true" default-state="collapsed" id="allay-breeding"}

[Hilfsgeister](https://de.minecraft.wiki/w/Hilfsgeist) sind auf dem Survival Server nicht durch [Amethystscherben](https://de.minecraft.wiki/w/Amethystscherbe) vermehrbar.
Du kannst sie dennoch in [Plünderer-Außenposten](https://de.minecraft.wiki/w/Plünderer-Außenposten) finden.

## Alternate Current Redstone-Implementierung {collapsible="true" default-state="collapsed" id="alternate-current"}

Der Server verwendet
die [Alternate Current Redstone-Implementierung
![logo](https://i.imgur.com/Xn4Ya2P.png) {border-effect="rounded"}](https://github.com/SpaceWalkerRS/alternate-current/blob/main/README.md "Alternate Current Redstone-Implementierung")
um die Leistung von Redstone-Systemen zu verbessern.

Alternate Current
: "Alternate Current" ist eine effiziente, nicht-lokationsabhängige Redstone-Staub-Implementierung. Der Hauptfokus liegt
darauf, die durch Redstone-Staub verursachte Verzögerung zu verringern, indem Leistungsberechnungen optimiert und die
Anzahl an Form- und Block-Updates reduziert werden. Diese Implementierung macht die Update-Reihenfolge von
Redstone-Staubnetzwerken vorhersehbar und intuitiv, anstatt positionsabhängig und chaotisch zu sein.

Leistungsverbesserung
: Die Leistungsbeiträge (MSPT) von Redstone-Staub sind mit "Alternate Current" bis zu 20 Mal niedriger als in Vanilla,
bei gleichzeitiger Beibehaltung hoher Vanilla-Parität. Durch die geringe Anzahl an Code-Modifikationen ist es eine
einfach einzubindende Alternative zum Vanilla-Redstone-Staub.

Funktionsweise
: "Alternate Current" verwendet einen Algorithmus, der folgende Ziele verfolgt: \
\
Minimierung der Häufigkeit, mit der eine Leitung ihre Umgebung überprüft, um ihren Leistungspegel zu bestimmen.
Minimierung der Anzahl von Block- und Form-Updates.
Ausgabe von Block- und Form-Updates in einer deterministischen, nicht-lokationsabhängigen Reihenfolge.
Im Gegensatz zu Vanilla, wo eine Redstone-Leitung ihre Leistungsstufe isoliert berechnet, baut "Alternate Current" ein
Netzwerk verbundener Leitungen auf und verbreitet von dort aus die Energie. Dadurch werden weniger häufige und weniger
redundante Updates erzeugt.
