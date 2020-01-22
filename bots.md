---
title: Bots
description: Information about various Discord Bot Libraries
published: true
date: 2020-01-22T09:17:07.153Z
tags: 
---

Discord allows users to create Bots and invite them to servers. Discord allows users to create applications that interact with the API. API documentation is listed [here](https://discordapp.com/developers/docs/intro).
The community-driven but official Discord API server can be accessed [here](http://discord.gg/discord-api).

# Regular Bots
Regular bots have *dedicated* bot accounts created through the developer portal. Bot accounts have different restrictions and features than user accounts. To invite a server bot to your guild, you need to have the **Manage Server** permission, and you need to authorize it with an authorization link specific to that bot. To invite a bot; click the authorization link, select a server, deny or allow it to have the permissions listed on the page, and click 'Authorize'. To remove a bot from your server, simply kick or ban it like you would any other user. Reinviting a bot account that was already banned from the server will unban it. Bot accounts have a bot tag next to their name to distinguish it from regular users. If you want to create your own bot, you need to create it through Discord's application page. The applications page is listed [here](https://discordapp.com/developers/applications/me).

# Selfbots
Selfbots are when a user uses the Discord API to automate their account. A self bot runs directly on your account by using your user token to automate itself. Selfbots are against the Discord API [OAuth](https://discordapp.com/developers/docs/topics/oauth2#bot-vs-user-accounts) policy and can lead to an account termination. In contrast to userbots, selfbots only respond to the user account it is running on. **Do not give anyone your user token. If someone gets your user token, they can do serious damage to your account, including reading messages, sending messages and mess with any server you have permissions on.**

# Userbots
Userbots are fully functioning bots that run through a regular account. This is against the Discord [Terms of Service](https://discordapp.com/terms). Like other Terms of Service violations, userbots can be reported to Discord Trust & Safety at [support@discordapp.com.](mailto:support@discordapp.com).

# Libraries
Users have created many different libraries that make using the Discord API easier.
* [Discord.io](https://github.com/izy521/discord.io)
* [Discord.js](https://github.com/hydrabolt/discord.js)
* [Discord.net](https://github.com/RogueException/Discord.Net)
* [Disco](https://github.com/b1naryth1ef/disco)
* [Discord.py](https://github.com/Rapptz/discord.py)
* [Discord-rs](https://github.com/SpaceManiac/discord-rs)
* [Discord4J](https://github.com/austinv11/Discord4J)
* [Discordcr](https://github.com/meew0/discordcr)
* [Discordia](https://github.com/SinisterRectus/Discordia) *Not to be confused with https://discordia.me*
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

### Discord-Curated Libraries

Discord has [a list of curated libraries](https://discordapp.com/developers/docs/topics/community-resources#libraries) "that conform to [Discord's] APIs standards around authentication and rate limiting."