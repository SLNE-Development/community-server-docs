# Clan-Management

## Mitgliederverwaltung {id="member-management"}

> Nur Offiziere, Anführer oder der Clanbesitzer können Mitglieder hinzufügen oder entfernen.

{type="medium"}
Mitglieder einladen {id="invite-member"}
: Verwende `/clan invite <player>`, um Spieler in den Clan einzuladen.

Mitglieder entfernen {id="remove-member"}
: Verwende `/clan kick <player>`, um Mitglieder aus dem Clan zu entfernen.

## Rollenverteilung {id="role-distribution"}

Clanmitgliedern können verschiedene Rollen zugewiesen werden – zum Beispiel Offizier oder Anführer.
Die Rechte der jeweiligen Rolle sind in der folgenden Tabelle dargestellt:


<table style="both">
<tr><td width="256"><strong>Funktion</strong></td><td><strong>Offizier</strong></td><td><strong>Anführer</strong></td><td><strong>Besitzer</strong></td></tr>
<tr><td>Spieler einladen</td><td>✅</td><td>✅</td><td>✅</td></tr>
<tr><td>Mitglieder entfernen</td><td>✅</td><td>✅</td><td>✅</td></tr>
<tr><td>Mitglieder befördern</td><td>❌</td><td>✅</td><td>✅</td></tr>
<tr><td>Mitglieder herabstufen</td><td>❌</td><td>✅</td><td>✅</td></tr>
<tr><td>Clan auflösen</td><td>❌</td><td>❌</td><td>✅</td></tr>
</table>

{type="medium"}
Mitglied befördern {id="promote-member"}
: Verwende `/clan promote <player>`, um ein Mitglied auf die nächsthöhere Rolle zu befördern.

Mitglied herabstufen {id="demote-member"}
: Verwende `/clan demote <player>`, um ein Mitglied auf die nächstniedrigere Rolle herabzustufen.

## Clanauflösung {id="clan-dissolution"}

Der Clanbesitzer kann den Clan mit dem Befehl `/clan disband` auflösen.

> Nach Eingabe des Befehls muss die Auflösung manuell im Chat bestätigt werden.
> Sobald die Bestätigung erfolgt, wird der Clan **unwiderruflich** gelöscht und alle
> Mitglieder entfernt.
>
{style="warning" title="Achtung"}