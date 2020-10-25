---
title: Chat Befehle
description: Beschreibt alle verfügbaren Chat Befehle, sogar die nicht offensichtlichen/nicht dokumentierten
published: true
date: 2020-10-25T16:30:28.793Z
tags: 
editor: markdown
dateCreated: 2020-03-09T19:35:21.065Z
---

# Discord Chat Befehle
Während einige von Discord's "Slash" Befehlen ziemlich eindeutig anwendbar sind, gibt es einige dinge, welche man in der Chatbox tun kann und die nicht dokumentiert sind (oder schwer zu finden sind). Um zu verhindern, dass du dich durch Changelogs und Support-Artikel durchwühlen musst, sind hier einige dinge, welche du in der Chatbox tun kannst:

## Chat funktionen
Es gibt einige Chat-funktionen, welche nicht so offensichtlich sind, aber dafür das verwenden des Chats oftmals leichter machen.

### Reaktion per Chat hinzufügen
Verfügbar für Desktop und iOS.  
Wenn du `+:emojiname:` im Chat schreibst und dies dann sendest, wird der angegebene Emoji als Reaktion zur vorherigen Nachricht eingefügt.  
Dies funktioniert auch mit Emotes (Benutzerdefinierten Emojis), aber du musst dafür auf dem Server dieses Emotes sein, oder Nitro besitzen.

### Letzte Nachricht editieren
Verfügbar für Desktop.  
Wenn du deine zuletzt gesendete Nachricht editieren willst, musst du nicht extra auf diese Rechtsklick machen um dann "Nachricht bearbeiten" auszuwählen.  
Drücke einfach die *Pfeil auf* Taste und schon kannst du deine letzte Nachricht bearbeiten.

### Einen Schreibfehler schnell korrigieren
Verfügbar für Desktop und iOS.  
Hast du "Dsa" statt "Das" geschrieben und möchtest es schnell korrigieren? Schreibe einfach `s/Dsa/Das` in den Chat um deine letzte Nachricht automatisch zu bearbeiten. Es kann nur eine Instanz (Die erste) editieren, ist aber praktisch zum schennel korrigieren von Schreibfehlern!

### Erhalte die ID eines erwähnbaren Items
Alles was du erwähnen kannst (Emotes, Benutzer, Rollen, Kanäle, etc.) kann verwendet werden, um die ID dieses Items zu erhalten.  
Zum Beispiel wird `\@Benutzer` die id vom erwähnten Benutzer zeigen, `\@Rolle` die id von der erwähnten Rolle, `\#Kanal` die id vom erwähnten Kanal usw.

**Beachte jedoch, dass der Benutzer, die Rolle, ... weiterhin erwähnt wird!**

### Erhalte das unicode Emoji
Traurigerweise kannst du nicht einfach `:poop:` in deinem Namen verwenden um das Poop Emoji zu zeigen.  
Du kannst aber das Unicode Emoji von `:poop` erhalten, indem du es mit einem `\` beginnst. So wird aus `\:poop:` 💩, welches du dann in deinem Namen verwenden kannst.

### Text formattierung
Discord hat mehrere Tasten-Kombinationen eingefügt, mit welcher du deine Nachricht formatieren kannst, ähnlich wie in Text-Editoren.  
Hier ist eine Liste der Tasten-Kombinationen und was sie tun:
- `Ctrl + B`: **Fett**
- `Ctrl + I`: *Kursiv*
- `Ctrl + U`: <u>Unterstrichen</u>

> **Wichtig!**  
> Du musst Text markiert haben, um diese Tasten-Kombinationen zu verwenden.
{.is-warning}

## Slash Befehle
Ein grossteil dieser Befehle können nur auf Desktop und iOS Klients verwendet werden. Android Benutzer haben nur zugang zu `/tableflip`, `/unflip` und `/shrug`.

> **Hinweis**:  
> `<Text>` wird benötigt, während `[Text]` optional ist.
{.is-info}

### `/tableflip [Nachricht]`
Gibt `(╯°□°）╯︵ ┻━┻` als Output in den Chat.

Das hinzufügen einer Nachricht nach dem Befehl hängt das Emoticon an die Nachricht an.
Zum Beispiel wird `/tableflip Ich mag diesen Tisch nicht.` zu `Ich mag diesen Tisch nicht. (╯°□°）╯︵ ┻━┻`

### `/unflip [Nachricht]`
Gibt `┬─┬ ノ( ゜-゜ノ)` als Output in den Chat.

Das hinzufügen einer Nachricht nach dem Befehl hängt das Emoticon an die Nachricht an.
Zum Beispiel wird `/unflip Ich mag diesen Tisch aber.` zu `Ich mag diesen Tisch aber. ┬─┬ ノ( ゜-゜ノ)`

### `/shrug [Nachricht]`
Gibt `¯\_(ツ)_/¯` als Output in den Chat.

Das hinzufügen einer Nachricht nach dem Befehl hängt das Emoticon an die Nachricht an.
Zum Beispiel wird `/shrug Ich mag Stühle mehr.` zu `Ich mag Stühle mehr. ¯\_(ツ)_/¯`

### `/me <Nachricht>`
Sended deine Nachricht in *Kursiv* ähnlich dem Stil von IRC.
Genau gleich wie wenn du die Nachricht mit `*` (Asterisk) umhülst (`*<Nachricht hier>*`)

### `/nick <Neuer Nickname>`
Ändert deinen Nicknamen auf dem Server zu dem, was du nach dem Befehl angegeben hast.
Du benötigst "Nickname ändern" Berechtigung auf dem Server.

### `/tenor <Suchbegriff>` und `/giphy <Suchbegriff>`
Durchsucht Tenor oder Giphy (Abhängig davon, welchen Befehl du verwendet hast) nach gifs, welche deinem Suchbegriff entsprechen.

### `/tts <Nachricht>`
Verwendet Text-zu-Sprache um die Nachricht für alle, welche den Textkanal sehen und die "Text-zu-Sprache" Einstellung aktiv haben, vorzulesen.
Du benötigst die "TTS-Nachrichten senden" Berechtigung im Server/Textkanal und musst die "Text-zu-Sprache" Option in deinen Einstellungen aktiviert haben, um diesen Befehl verwenden zu können.

> **Hinweis**:
> Im moment funktioniert Text-zu-Sprache auf Mobilen Geräten nicht.
{.is-info}

### `/spoiler <Nachricht>`
Setzt alles nach dem Befehl in Spoiler.  
Genau gleich wie wenn du die Nachricht mit `||` umhüllst (`||<Nachricht hier>||`)