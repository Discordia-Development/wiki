---
title: Chat Befehle
description: Beschreibt alle verfügbaren Chat Befehle, sogar die nicht offensichtlichen/nicht dokumentierten
published: true
date: 2020-03-16T17:59:35.144Z
tags: 
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

## Slash Befehle
Diese Befehle sind nur auf der Desktop und iOS App verfügbar. Unglücklicherweise haben Android-Nutzer kein solches Glück.

> **Hinweis**:  
> `<Text>` wird benötigt, während `[Text]` optional ist.

### `/tableflip [Nachricht]`
Gibt `(╯°□°）╯︵ ┻━┻` als Output in den Chat.  
Wenn du eine Nachricht an den Befehl anhängst (`/tableflip Ich mag diesen Tisch nicht.`), wird das Emoticon ans ende dieser Nachricht angehängt (`Ich mag diesen Tisch nicht. (╯°□°）╯︵ ┻━┻`).

### `/unflip [Nachricht]`
Gibt `┬─┬ ノ( ゜-゜ノ)` als Output in den Chat.  
Wenn du eine Nachricht an den Befehl anhängst (`/unflip Ich mag diesen Tisch aber.`), wird das Emoticon ans ende dieser Nachricht angehängt (`Ich mag diesen Tisch aber. ┬─┬ ノ( ゜-゜ノ)`).

### `/shrug [Nachricht]`
Gibt `¯\_(ツ)_/¯` als Output in den Chat.  
Wenn du eine Nachricht an den Befehl anhängst (`/shrug Ich mag Stühle mehr.`), wird das Emoticon ans ende dieser Nachricht angehängt (`Ich mag Stühle mehr. ¯\_(ツ)_/¯`).

### `/me <Nachricht>`
Sended deine Nachricht in *Kursiv* ähnlich dem Stil von IRC.  
Genau gleich wie wenn du die Nachricht mit `*` (Asterisk) umhülst (`*<Nachricht hier>*`)

### `/nick <Neuer Nickname>`
Ändert deinen Nicknamen auf dem Server zu dem, was du nach dem Befehl angegeben hast.  
Du benötigst "Nickname ändern" Berechtigung auf dem Server.

### `/tenor <Suchbegriff>` und `/giphy <Suchbegriff>`
Durchsucht Tenor oder Giphy (Abhängig davon, welchen Befehl du verwendet hast) nach gifs, welche deinem Suchbegriff entsprechen.

### `/spoiler <Nachricht>`
Setzt alles nach dem Befehl in Spoiler.  
Genau gleich wie wenn du die Nachricht mit `||` umhüllst (`||<Nachricht hier>||`)