---
title: Bots
description: Information about Discord bots.
published: true
date: 2021-03-13T14:48:06.325Z
tags: 
editor: markdown
dateCreated: 2020-01-09T04:55:32.662Z
---

Discord allows users to create bots that can be invited to servers and applications that can interact with the API. The API documentation is listed [here](https://discordapp.com/developers/docs/intro).

There also exists a [Discord API Server](https://discord.gg/discord-api) that is managed by the community. While it does contain Discord staff and is also recommended by Discord for support with their API, is it considered an unofficial server.

Finally, an official [Discord Developers](https://discord.gg/discord-developers) server exists, which is the main place to ask questions regarding the API, the Game SDK, [Bot Verification](/en/verified-developers) and such.
It is however not the main place to ask questions related to specific libraries for the Discord API.

# Regular Bots
Regular Bots have a dedicated bot account (indicated with a "BOT" label).

## Restrictions and Features
Bots have different restrictions and features compared to regular users.
For example, a bot is not restricted to 100 servers (as long as it's verified). However, once a bot reaches 75 or more Servers they are required to be [verified](verified-developers) or they won't be able to get past 100 servers.

Inviting a bot is also different compared to users. Instead of just sharing a invite link will you need to open a dedicated OAuth link to "authorize" the bot to join the server on your behalf.
You can only invite the bot to a server that you have **Manage Server** permissions on.

To remove a bot from your server you can just kick or ban it.
Note that you don't have to unban a bot if you want to re-invite it, as the OAuth link will automatically do that for you.

## Creating a Bot
To create a bot will you need to go to your [applications page](https://discord.com/developers/applications/me) and create a new application. From there, click on the "Bot" tab on the left and create a bot in the new window.

All that is left to do now is choosing a library for the coding language of your choice, set up some code and start your bot with it. Don't forget to invite it to some servers too!

# Selfbots
> Selfbots violate the [Discord API OAuth policy](https://discord.com/developers/docs/topics/oauth2#bot-vs-user-accounts) and can lead to an account-termination.
{.is-warning}

Selfbots are when a user uses the Discord API to automate their account. A self bot runs directly on your account by using your user token to automate itself.

In contrast to userbots, selfbots only respond to the user account it is running on. **Do not give anyone your user token. If someone gets your user token, they can do serious damage to your account, including reading messages, sending messages and mess with any server you have permissions on.**

# Userbots
Userbots are fully functioning bots that run through a regular account. This is against the Discord [Terms of Service](https://discordapp.com/terms). Like other Terms of Service violations, userbots can be reported to Discord Trust & Safety at [support@discordapp.com.](mailto:support@discordapp.com).

# Libraries
The Discord community offers a variety of libraries to work with the Discord API.  
Discord themselves have a [list of curated libraries](https://discord.com/developers/docs/topics/community-resources#libraries). Each listed library is confirmed to be maintained and *"conforms to our (Discord's) API standards around authentication and rate limiting"*.

This means that these libraries are guaranteed to follow the rules and especially the Developer ToS in terms of rate limits and general API usage.

# Verification
On April 7th, 2020, bot verification was introduced. Any bot that is in 75 or more guilds can apply for veirification. 

Since October 7th, 2020, unverified bots will not be able to join more than 100 servers (if it's already in more than 100 of them, you won't be able to invite it) and won't be able to access [Privileged Intents](https://discord.com/developers/docs/topics/gateway#privileged-intents).