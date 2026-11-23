# Persönliche Einstellungen

## So passt du Chestprotect an {id="chestprotect-settings"}

Gib `/chestprotect` ein und wähle **Settings**. Für manche Einstellungen benötigst du eine Berechtigung.

![chestprotect-settings](chestprotect-settings.png) {border-effect="rounded" thumbnail="false" width="480"}

| Item     | Einstellung                              | Beschreibung                                                                                              |
|----------|------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Schild   | **Persistent Lock/Unlock**               | Bleibt aktiv, bis du `/chestprotect exit` ausführst oder den Modus ausschaltest.                          |
| Kopf     | **Persistent Trust/Untrust/SetRole**     | Bleibt aktiv, bis du `/chestprotect exit` ausführst oder den Modus ausschaltest.                          |
| Beobachter | **Auto Lock**                          | Sichert sicherbare Blöcke automatisch beim Platzieren, wenn du unter deinem Limit liegst.                 |
| Papier   | **Notifications**                        | Zeigt Nachrichten, wenn du eine eigene Sicherung oder eine Sicherung, auf der du vertraut bist, öffnest. |

## Wann schlägt Auto-Lock fehl? {id="chestprotect-settings-autolock"}

- Du hast dein Sicherungslimit erreicht.
- Die Welt oder Region erlaubt keine Sicherungen.
- Der Objekttyp ist nicht sicherbar.

## Dauerhafte Modi {id="chestprotect-settings-persistent"}

Ist ein Modus nicht dauerhaft, endet er nach einer erfolgreichen Aktion. Ist er dauerhaft, führe
`/chestprotect exit` aus, wenn du fertig bist.
