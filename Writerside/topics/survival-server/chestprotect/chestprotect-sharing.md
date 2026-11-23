# Spieler vertrauen

## So teilst du Sicherungen mit anderen Spielern {id="chestprotect-sharing"}

Du kannst eine Sicherung mit bestimmten Spielern teilen. Vertraute Spieler erhalten eine Rolle, die festlegt, was sie
tun dürfen.

<tabs>
<tab title="Spieler vertrauen" id="chestprotect-trust">

Gib `/chestprotect trust <player>` ein und klicke auf die Sicherung.

Alternativ vertraust du Spielern über das Sicherungsmenü:

1. Halte <shortcut>Shift</shortcut> gedrückt und klicke mit der <shortcut>Linksklick</shortcut>-Taste auf die
   Sicherung.
2. Öffne **Members**.
3. Wähle **Trust Player**.
4. Gib den Spieler ein oder wähle ihn aus.
   ![chestprotect-trusted-players](chestprotect-trusted-players.png) {border-effect="rounded" thumbnail="false" width="480"}

> Eine Gruppe kann maximal 20 Mitglieder enthalten, siehe [Gruppen](chestprotect-groups.md).
>
{style="note"}

</tab>
<tab title="Vertrauen entziehen" id="chestprotect-untrust">

Gib `/chestprotect untrust <player>` ein und klicke auf die Sicherung.

Alternativ entfernst du Spieler im Menü **Members**.

> Ist ein Spieler über eine Gruppe vertraut, musst du ihn aus dieser Gruppe entfernen.
>
{style="note"}

</tab>
</tabs>

## Rollen {id="chestprotect-roles"}

Jedem vertrauten Spieler kannst du pro Sicherung eine von zwei Rollen geben:

| Rolle                | Rechte                                                                           |
|----------------------|----------------------------------------------------------------------------------|
| Member (Mitglied)    | Darf die Sicherung öffnen.                                                       |
| Admin (Verwalter)    | Darf die Sicherung öffnen, Spielern vertrauen, Vertrauen entziehen und Rollen ändern. |

Du kannst keine eigenen Rollen erstellen. Du selbst bist als Besitzer (Owner) der Sicherung berechtigt, alles an ihr zu tun.

> Hopper funktionieren an gesicherten Objekten nicht. Das Flag `HOPPER_TRANSFER` hat daher keine Wirkung.
>
{style="note"}

## Rollen-Flags {id="chestprotect-role-flags"}

Rollen-Flags legen fest, was vertraute Spieler tun dürfen.

| Flag              | Beschreibung                                         |
|-------------------|------------------------------------------------------|
| `OPEN`            | Die Sicherung öffnen oder nutzen.                    |
| `HOPPER_TRANSFER` | Hopper zum Übertragen von Items nutzen.              |
| `PLAYER_TRUST`    | Spielern auf der Sicherung vertrauen.                |
| `PLAYER_UNTRUST`  | Vertraute Spieler von der Sicherung entfernen.       |
| `PLAYER_SETROLE`  | Die Rolle eines anderen vertrauten Spielers ändern.  |
| `UNLOCK`          | Die Sicherung aufheben.                              |
| `EDIT_FLAGS`      | Die Flags der Sicherung ändern.                      |

> Du kannst Spieler in der Regel nicht bearbeiten, wenn ihre Rolle die gleiche oder eine höhere Priorität hat als deine.
>
{style="note"}

## Grundstücke und Regionen {id="chestprotect-regions"}

Chestprotect unterstützt auf dem Server Grundstücke (Regionen). Du kannst Objekte sowohl auf als auch außerhalb von
Grundstücken sichern. Mehr zu Grundstücken findest du unter [Grundstücke](plots-homepage.topic).

Die Mitglieder eines Grundstücks werden **nicht automatisch** auf Sicherungen vertraut, die dort liegen. Möchtest du
das, musst du es für jede Sicherung einzeln einstellen:

1. Halte <shortcut>Shift</shortcut> gedrückt und klicke mit der <shortcut>Linksklick</shortcut>-Taste auf die
   Sicherung.
2. Öffne **Members**.
3. Stelle **Allow Region Members** auf **Yes**.

Danach dürfen die Mitglieder des Grundstücks, auf dem die Sicherung liegt, auf sie zugreifen.
