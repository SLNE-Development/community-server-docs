# Verbindungstest durchführen

## Warum ein MTR-Test?

Ein MTR-Test hilft uns dabei herauszufinden, ob das Problem an deiner Internetverbindung oder dem Server liegt. 
Du testest damit, ob deine Datenpakete problemlos durch das Netzwerk bis zu uns kommen oder irgendwo auf dem Weg hängen bleiben.

## Wie kann ich einen MTR durchführen?

Wie du einen MTR durchführen kannst, ist im folgenden Abschnitt genauer beschrieben.

> Bitte beachte, dass die Ergebnisse des Tests nur hilfreich sind, wenn er durchgeführt wird, während die Probleme tatsächlich auftreten!
>
{style="warning"}

<tabs>

<tab id="windows-install" title="Windows">

1. Lade **WinMTR** von [SourceForge](https://sourceforge.net/projects/winmtr/files/WinMTR-v092.zip/download) herunter und installiere es.
2. Starte WinMTR und gib in das Feld **„Host:“** die Server-IP ein:
   - **play.castcrafter.de** für allgemeine Verbindungsprobleme
   - **voice.castcrafter.de** für Voicechat-Probleme
3. Klicke auf **Start** und lasse mindestens **100 Pakete** senden.
4. Klicke auf **„Copy text to clipboard“**, um die Testergebnisse zu kopieren.
5. Lade die Daten auf eine Seite wie [Pastebin](https://pastebin.com/) hoch (Einstellung: **„Unlisted“**).

![mtr.png](mtr.png)

</tab>
<tab id="macos-install" title="macOS">

1. Falls du **Homebrew** nicht installiert hast, öffne das Terminal und gib ein:
   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
   ```
2. Installiere MTR mit:
   ```sh
   brew install mtr
   ```
3. Starte den MTR-Test mit:
   ```sh
   mtr -w -c 100 -z play.castcrafter.de
   ```
   Falls du den Voicechat testen willst, ersetze die IP durch **voice.castcrafter.de**.
4. Markiere das Ergebnis im Terminal, kopiere es mit **CMD + C** und lade es auf eine Seite wie [Pastebin](https://pastebin.com/) hoch (Einstellung: **„Unlisted“**).
</tab>
<tab id="linux-install" title="Linux">

1. Öffne das Terminal.
2. Installiere MTR abhängig von deiner Distribution:
    - **Ubuntu/Mint:** `sudo apt install mtr`
    - **Fedora:** `sudo yum install mtr`
    - Falls es nicht funktioniert, überprüfe die Paketverwaltung deiner Distribution.
3. Führe den Test aus:
   ```sh
   mtr -w -c 100 -z play.castcrafter.de
   ```
   Falls du den Voicechat testen willst, ersetze die IP durch **voice.castcrafter.de**.
4. Kopiere das Ergebnis mit **Strg + C** und lade es auf eine Seite wie [Pastebin](https://pastebin.com/) hoch (Einstellung: **„Unlisted“**).
</tab>
</tabs>

Anschließend kannst du uns den Link in einem Support Ticket zukommen lassen, damit wir uns das Problem genauer anschauen können.