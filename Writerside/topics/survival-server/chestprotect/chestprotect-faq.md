# Häufige Fragen

## Häufige Fragen zu Chestprotect {id="chestprotect-faq"}

<deflist collapsible="true">
<def title="Warum kann ich dieses Objekt nicht sichern?" id="chestprotect-faq-cannot-lock">

Mögliche Gründe:

1. Der Block- oder Entity-Typ ist auf dem Server nicht sicherbar.
2. Chestprotect ist in dieser Welt deaktiviert.
3. Ein Plugin für Claims, Regionen, Inseln oder Grundstücke verhindert die Sicherung an dieser Stelle.
4. Du hast dein Limit von 250 Containern oder 100 Entities erreicht.

</def>
<def title="Wie öffne ich das Menü einer Sicherung?" id="chestprotect-faq-menu">

Halte <shortcut>Shift</shortcut> gedrückt und klicke mit der <shortcut>Linksklick</shortcut>-Taste auf die Sicherung.
Dafür benötigst du Bearbeitungsrechte.

</def>
<def title="Wie beende ich den Modus zum Sichern oder Vertrauen?" id="chestprotect-faq-exit">

Gib `/chestprotect exit` ein.

</def>
<def title="Warum können andere Items einlagern oder entnehmen, ohne vertraut zu sein?" id="chestprotect-faq-public">

Bei der Sicherung ist eventuell das Flag `PUBLIC_INSERT` oder `PUBLIC_TAKE` aktiviert. Prüfe die Flags im Menü der
Sicherung.

</def>
<def title="Warum funktionieren Hopper nicht mit meiner Sicherung?" id="chestprotect-faq-hopper">

An gesicherten Objekten funktionieren auf dem Server keine Hopper. Es können weder Items hinein noch heraus
transportiert werden.

</def>
<def title="Warum kann ich einem Spieler das Vertrauen nicht entziehen?" id="chestprotect-faq-untrust">

Der Spieler ist möglicherweise über eine Gruppe vertraut, oder seine Rolle hat die gleiche oder eine höhere Priorität
als deine. Entferne ihn im Gruppenmenü aus der Gruppe oder bitte den Besitzer, seine Rolle zu ändern.

</def>
<def title="Wie finde ich meine Sicherungen?" id="chestprotect-faq-find">

Gib `/chestprotect` ein und wähle **Protections**. Mit `/chestprotect view` lässt du dir außerdem Sicherungen in deiner
Nähe anzeigen.

</def>
<def title="Was passiert, wenn ich eine Sicherung aufhebe?" id="chestprotect-faq-unlock">

Sie wird entfernt. Eine Rückerstattung gibt es nicht, da das Sichern nichts kostet.

</def>
</deflist>
