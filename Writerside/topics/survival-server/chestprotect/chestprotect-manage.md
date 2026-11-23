# Sicherungen verwalten

## So verwaltest du deine Sicherungen {id="chestprotect-manage"}

### Sicherungsmenü öffnen {id="chestprotect-manage-menu"}

Halte <shortcut>Shift</shortcut> gedrückt und klicke mit der <shortcut>Linksklick</shortcut>-Taste auf die
Sicherung. Dafür benötigst du Bearbeitungsrechte. Das Menü bietet folgende Möglichkeiten:

- **Members:** Spieler vertrauen, entfernen und Rollen ändern.
- **Edit Flags:** Das Verhalten dieser Sicherung ändern.
- **Name:** Einen Anzeigenamen festlegen.
- **Edit Group:** Die Sicherung einer deiner Gruppen zuweisen.
- **Unlock:** Die Sicherung aufheben.

![chestprotect-protection-menu](chestprotect-protection-menu.png) {border-effect="rounded" thumbnail="false" width="480"}

### Alle Sicherungen anzeigen {id="chestprotect-manage-list"}

Gib `/chestprotect` ein und wähle **Protections**. Deine Sicherungen sind nach Typ gruppiert, z. B. Truhen, Fässer,
Öfen, Shulkerkisten und weitere. Unter **Other** findest du z. B. Amboss, Zaubertisch oder Trichter. Du kannst ein Menü öffnen oder
die Sicherung löschen. Im Hauptmenü siehst du außerdem, wie viele Container- und Entity-Sicherungen du im Vergleich zu
deinem Limit besitzt.

![chestprotect-protection-types](chestprotect-protection-types.png) {border-effect="rounded" thumbnail="false" width="480"}

### Flags {id="chestprotect-manage-flags"}

Flags ändern das Verhalten einer einzelnen Sicherung. Welche Flags du einstellen kannst, hängt vom Objekttyp ab:

| Flag            | Beschreibung                                                          |
|-----------------|-----------------------------------------------------------------------|
| `PUBLIC_TAKE`   | Jeder darf Items entnehmen, ohne vertraut zu sein.                    |
| `PUBLIC_INSERT` | Jeder darf Items einlagern, ohne vertraut zu sein.                    |
| `HOLOGRAM`      | Zeigt ein Hologramm mit dem Namen und dem Lagerplatz an.              |

| Objekttyp                   | Verfügbare Flags                                |
|-----------------------------|-------------------------------------------------|
| Truhe, Trichter             | `PUBLIC_TAKE`, `PUBLIC_INSERT`                  |
| Ofen, Shulkerkiste, Fass    | `PUBLIC_TAKE`, `PUBLIC_INSERT`, `HOLOGRAM`      |
| Amboss, Zaubertisch         | keine                                           |

![chestprotect-flags](chestprotect-flags.png) {border-effect="rounded" thumbnail="false" width="480"}

> Flags ersetzen keine Rollen. Die Rollen-Flags bestimmen weiterhin, wer die Sicherung öffnen oder verwalten darf.
>
{style="note"}

### Sicherung aufheben {id="chestprotect-manage-unlock"}

Gib `/chestprotect unlock` ein und klicke auf die Sicherung. Alternativ wählst du **Unlock** im Menü der Sicherung.
Da das Sichern nichts kostet, gibt es beim Aufheben keine Rückerstattung, siehe
[Limits und Einschränkungen](chestprotect-limits.md).

### Sicherungen in der Nähe anzeigen {id="chestprotect-manage-view"}

Mit `/chestprotect view` lässt du dir Sicherungen in deiner Nähe anzeigen. Führst du den Befehl erneut aus, schaltest
du die Anzeige wieder aus.

![chestprotect-view](chestprotect-view.png) {border-effect="rounded" thumbnail="false" width="480"}
