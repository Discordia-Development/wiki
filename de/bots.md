---
title: Bots
description: Informationen über verschiedenste Bot-APIs
published: true
date: 2019-12-29 3:36:00 UTC
tags:
---

* *Dieser Artikel ist über Discord Bots. Um den eigenen Bot des Discord Wikis zu sehen, siehe [WikiBot](https://github.com/DiscordiaWiki/wiki/blob/master/wikibot).*

Discord erlaubt Benutzersn, Bots zu erstellen und diese in Server einzuladen. Discord erlaubt Benutzern Applikationen zu erstellen, welche mir der API interagieren. Die Dokumentation ist [hier](https://discordapp.com/developers/docs/intro) gelistet. Dem Community-geführten, aber offizielle Discord API-Server kann man [hier](http://discord.gg/discord-api) beitreten.

# Reguläre Bots
Reguläre Bots haben *dedizierte* Bot-Konten, erstellt durch das Entwickler-Portal. Bot-Konten haben andere Einschränkungen und Features als Benutzerkonten. Um einen Serverbot auf deine Gilde einzuladen musst du die **Server verwalten** Berechtigung auf der Gilde, sowie einen Autorisierungslink (Auch OAuth-Link genannt) speziell für diesen Bot haben. Um einen Bot einzuladen, klicke auf den Link, wähle einen Server, verbiete oder erlaube es die gelisteten Berechtigungen auf der Seite und klicke 'Autorisieren'. Um einen Bot von deinem Server zu entfernen, kicke oder banne es wie einen normalen Benutzer. Erneutes einladen des Bot-Kontos, während dieser gebannt ist, entbannt diesen. Bot-Konten haben einen Bot Tag neben ihren Namen um sie von normalen Benutzern zu unterscheiden. Wenn du deinen eigenen Bot erstellen willst, musst du diesen durch Discord's Applikations-Seite erstellen. Die Applikations-Seite ist [hier](https://discordapp.com/developers/applications/me) gelistet.

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
