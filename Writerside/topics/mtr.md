# Verbindungstest durchführen

## Warum ein MTR-Test?

Ein MTR-Test hilft uns zu erkennen, ob Verbindungsprobleme an deiner Internetverbindung oder unserem Server liegen. Er zeigt, ob deine Datenpakete das Netzwerk problemlos durchlaufen oder unterwegs verloren gehen.

## Wie führe ich einen MTR-Test durch?

Die folgende Anleitung zeigt dir, wie du den Test unter deinem Betriebssystem durchführst.

> Führe den Test bitte **nur während der Probleme** durch – nur dann sind die Ergebnisse aussagekräftig!
>
{style="warning"}

<tabs>

<tab id="windows-install" title="Windows">

1. Lade **WinMTR** von [SourceForge](https://sourceforge.net/projects/winmtr/files/WinMTR-v092.zip/download) herunter und installiere es.
2. Starte WinMTR und gib im Feld **„Host:“** die passende Server-Adresse ein:
   - **play.castcrafter.de** bei allgemeinen Verbindungsproblemen
   - **voice.castcrafter.de** bei Voicechat-Problemen
3. Klicke auf **Start** und lasse mindestens **100 Pakete** senden.
4. Klicke auf **„Copy text to clipboard“**, um das Ergebnis zu kopieren.
5. Lade den Text auf eine Seite wie [Pastebin](https://pastebin.com/) hoch (Einstellung: **„Unlisted“**).

![mtr.png](mtr.png)

</tab>

<tab id="macos-install" title="macOS">

1. Öffne das Terminal. Falls **Homebrew** nicht installiert ist, führe diesen Befehl aus:
   ```sh
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
   ```
2. Installiere MTR mit:
   ```sh
   brew install mtr
   ```
3. Starte den Test mit:
   ```sh
   mtr -w -c 100 -z play.castcrafter.de
   ```
   Für Voicechat-Probleme verwende stattdessen **voice.castcrafter.de**.
4. Markiere das Ergebnis im Terminal, kopiere es mit **CMD + C**, und lade es auf [Pastebin](https://pastebin.com/) hoch (**„Unlisted“**).

</tab>

<tab id="linux-install" title="Linux">

1. Öffne das Terminal.
2. Installiere MTR abhängig von deiner Distribution:
   - **Ubuntu/Mint:** `sudo apt install mtr`
   - **Fedora:** `sudo yum install mtr`
   - Bei Problemen prüfe die Dokumentation deiner Distribution.
3. Starte den Test mit:
   ```sh
   mtr -w -c 100 -z play.castcrafter.de
   ```
   Für Voicechat-Probleme verwende **voice.castcrafter.de**.
4. Kopiere das Ergebnis mit **Strg + C** und lade es auf [Pastebin](https://pastebin.com/) hoch (**„Unlisted“**).

</tab>

</tabs>

Schick uns anschließend den Link per Support-Ticket, damit wir das Problem analysieren können.
