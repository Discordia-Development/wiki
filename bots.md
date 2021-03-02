---
title: Bots
description: Information about various Discord Bot Libraries
published: true
date: 2021-03-02T16:05:05.008Z
tags: 
editor: markdown
dateCreated: 2020-01-09T04:55:32.662Z
---

Discord allows users to create Bots that can be invited to Servers and applications that can interact with the API. The API documentation is listed [here](https://discordapp.com/developers/docs/intro).

There also exists a [Discord API Server](https://discord.gg/discord-api) that is managed by the community. While it does have Discord Staff-members on and is also recommended by Discord for support with their API is it considered an unofficial server.

Additionally does also a official [Discord Developers](https://discord.gg/discord-developers) Server exist, which is the main place to ask questions regarding the API, Game SDK, Verification Process, etc.
It is however not the main place to ask questions related to specific libraries for the Discord API.

# Regular Bots
Regular Bots have a dedicated Bot-Account (indicated with a "BOT" label).

## Restrictions and Features
Bots have different restrictions and features compared to regular users.
For once do they not have a 100 Server limit, meaning they can join a virtually infinite number of Servers.
However, once a bot reaches 75 or more Servers are they required to get [verified](verified-developers) or they won't be able to get past 100 Servers.

Inviting a bot is also different compared to users. Instead of just sharing a invite link will you need to open a dedicated OAuth link to "authorize" the bot to join the server on your behalf.
You can only invite the bot to a server that you have **Manage Server** permissions on.

To remove a bot from your server can you just kick or ban it.
Note that you don't have to unban a bot, if you want to re-invite it, as the OAuth link will automatically do that for you.

## Creating a Bot
To create a Bot will you need to go to your [Applications Page](https://discord.com/developers/applications/me) and create a new Application. From there, click on the "Bot" tab on the left and create a bot in the new window.

All that is left to do now is choosing a library for the coding language of your choice, set up some code and start your bot with it. Don't forget to invite it to some servers first!

# Selfbots
> Selfbots violate the [Discord API OAuth policy](https://discord.com/developers/docs/topics/oauth2#bot-vs-user-accounts) and can lead to an account-termination.
{.is-warning}

Selfbots are when a user uses the Discord API to automate their account. A self bot runs directly on your account by using your user token to automate itself.

In contrast to userbots, selfbots only respond to the user account it is running on. **Do not give anyone your user token. If someone gets your user token, they can do serious damage to your account, including reading messages, sending messages and mess with any server you have permissions on.**

# Userbots
Userbots are fully functioning bots that run through a regular account. This is against the Discord [Terms of Service](https://discordapp.com/terms). Like other Terms of Service violations, userbots can be reported to Discord Trust & Safety at [support@discordapp.com.](mailto:support@discordapp.com).

# Libraries
The Discord Community offers a variety of Libraries to work with the Discord API.  
Discord themself has a [list of curated libraries](https://discord.com/developers/docs/topics/community-resources#libraries). Each listed library is confirmed to be maintained and *"conforms to our (Discord's) API standards around authentication and rate limiting"*.

This means that these libraries are guaranteed to follow the rules and especially the Developer ToS in terms of rate limits and general API usage.

# Verification
On April 7th, 2020, Bots Verification was introduced. Each bot that reaches over 75 simultanious guilds has a chance of getting verified. 

Since October 7th, 2020, unverified bots will not be able to join more than 100 servers (if it's already in more than 100 of them, you won't be able to invite it) and won't be able to access [Privileged Intents](https://discord.com/developers/docs/topics/gateway#privileged-intents).