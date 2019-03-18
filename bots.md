<!-- TITLE: Bots -->
<!-- SUBTITLE: Information about various Discord Bot Libraries -->
* *This article is about Discord bots. To see Discord Wiki's own bot, see [WikiBot](/wikibot).*

Discord allows users to create Bots and invite them to servers. Discord allows users to create applications that interact with the API. API documentation is listed [here](https://discordapp.com/developers/docs/intro).
The community-driven but official Discord API server can be accessed [here](http://discord.gg/discord-api).

# Server Bots
The most common type of bots are server bots. Server bots have dedicated bot accounts that are different from user accounts and function mainly on servers. There are hundreds of server bots on Discord that have different functions. To invite a server bot to your guild, you need to have the **Manage Server** permission, and you need to authorize it with an authorization link specific to that bot. To invite a bot, click the authorization link, select a server, deny or allow it to have the permissions listed on the page and click 'Authorize'. To remove a bot from your server, simply kick or ban it like you would any other user. Bot accounts have a bot tag next to their name. If you want to create your own server bot, you need to register it through Discord's application page. Click [here](https://discordapp.com/developers/applications/me) to access the applications page.

# Selfbots
Selfbots are when a user uses the Discord API to enhance their account and give them some automated abilities, such as a self ping and embeds. A self bot runs on your account (not through the applications page) and has the ability to post messages for you. Selfbots are against the Discord API [OAuth](https://discordapp.com/developers/docs/topics/oauth2#bot-vs-user-accounts) policy and can lead to an account termination if found. Selfbots *must* only respond to commands from you, otherwise it is deemed a userbot (see below). To use a selfbot, you need your user token which can be found on the console. **Do not give anyone your user token. If someone gets your user token, they can do serious damage to your account, including reading messages, sending messages and mess with any server you have permissions on.**
# Userbots
Userbots are fully functioning bots run through a regular account. This is against the Discord [Terms of Service](https://discordapp.com/terms). If you encounter a userbot, please report it to [support@discordapp.com.](mailto:support@discordapp.com) 

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