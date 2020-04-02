---
title: Bots
description: Informationen über verschiedene Bot-Bibliotheken
published: true
date: 2020-01-31T21:59:43.910Z
tags: 
---

Discord erlaubt Benutzern Bots zu erstellen und diese in Server einzuladen. Discord erlaubt Benutzern Applikationen zu erstellen, welche mit der API interagieren können. Die API-Dokumentation kann [hier](https://discordapp.com/developers/docs/intro) gefunden werden.
Den Community-betriebene aber offizielle Discord API Server kann man [hier](https://discord.gg/discord-api) beitreten.

# Reguläre Bots
Reguläre Bots haben *dedizierte* Bot-Accounts, welche durch das Developer-Portal erstellt werden. Bot-Accounts haben andere Einschränkungen und Features als Benutzer-Accounts. Um einen Bot zu deinem Discord einzuladen, musst due die **Server verwalten** Berechtigung haben, als auch den Bot mittels eines Autorisierungslinks speziell für diesen Bot autorisieren. Um einen Bot einzuladen, klicke den Autorisierungslink, wähle einen Server, verbiete oder erlaube die gelisteten Rechte und klicke "Autorisieren". Um einen Bot von deinem Server zu entfernen, kicke oder banne es wie du es mit einem Benutzer tun würdest. Das erneute einladen eines gebannten Bots hebt den Ban automatisch auf. Bot-Accounts haben einen Bot tag neben ihrem namen um sie von normalen Benutzern zu unterscheiden. Wenn du einen Bot selber erstellen willst, musst du dies durch Discord's Applikationsseite tun. Die Applikationsseite ist [hier](https://discordapp.com/developers/applications/me) gelistet.

# Selbstbots
Selbstbots sind Benutzer, welche die Discord API verwenden um ihr Konto zu automatisieren. Ein Selbstbot läuft direkt auf deinem Konto durch das verwenden deines Benutzer-Tokens um sich selbst zu automatisieren. Selbstbots sind gegen die Discord [OAuth](https://discordapp.com/developers/docs/topics/oauth2#bot-vs-user-accounts) Richtlinien und können zur Terminierung deines Kontos führen. Im vergleich zu Userbots, antworten Selbstbots nur auf das Konto, auf welchem der Bot läuft. **Gib niemandem deinen Benutzer-Token. Wenn jemand deinen Benutzer-Token erhält, können diese deinem Konto erheblichen Schaden zufügen, inclusive lesen von Nachrichten, senden von Nachrichten sowie verändern aller Server für welche du Rechte hast.**

# Userbots
Userbots sind voll funktionsfähige Bots welche über ein normales Konto laufen. Dies ist gegen die Discord [Nutzungsbedingungen](https://discordapp.com/terms). Wie andere verletzungen der Nutzungsbedingungen können Userbots an das Discord Vertauen & Sicherheit Team unter support@discordapp.com gemeldet werden.

# Bibliotheken
Benutzer haben verschiedenste Bibliotheken erstellt, welche das verwenden der Discord API leichter machen.
* [Discord.io](https://github.com/izy521/discord.io)
* [Discord.js](https://github.com/hydrabolt/discord.js)
* [Discord.net](https://github.com/RogueException/Discord.Net)
* [Disco](https://github.com/b1naryth1ef/disco)
* [Discord.py](https://github.com/Rapptz/discord.py)
* [Discord-rs](https://github.com/SpaceManiac/discord-rs)
* [Discord4J](https://github.com/austinv11/Discord4J)
* [Discordcr](https://github.com/meew0/discordcr)
* [Discordia](https://github.com/SinisterRectus/Discordia) *Nicht zu verwechseln mit htttps://discordia.me*
* [Discordie](https://github.com/qeled/discordie)
* [DiscordGo](https://github.com/bwmarrin/discordgo)
* [Discordrb](https://github.com/meew0/discordrb)
* [DSharpPlus](https://github.com/NaamloosDT/DSharpPlus)
* [Eris](https://github.com/abalabahaha/eris)
* [Javacord](https://github.com/BtoBastian/Javacord)
* [JDA](https://github.com/DV8FromTheWorld/JDA)
* [Nostrum](https://github.com/Kraigie/nostrum)
* [Restcord](https://github.com/restcord/restcord)
* [Serenity](https://github.com/zeyla/serenity)
* [SwiftDiscord](https://github.com/nuclearace/SwiftDiscord)
* [Sword](https://github.com/Azoy/Sword)

### Discord-kuratierte Bibliotheken
Discord hat [eine Liste von kuratierten Bibliotheken](https://discordapp.com/developers/docs/topics/community-resources#libraries) "die den API-Standarts von Discord bezüglich Authentifizierung und Ratenbegrenzung entsprechen." (Übersetzt vom englischen)