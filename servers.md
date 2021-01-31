---
title: Servers
description: 
published: true
date: 2021-01-31T14:52:07.663Z
tags: 
editor: markdown
dateCreated: 2020-01-09T05:51:32.376Z
---

A server (occasionally referred to as a *guild* in Discord documentation) is the main feature on Discord.


![A Discord Server](https://github.com/DiscordiaWiki/wiki/blob/master/uploads/servers/discordserver.png?raw=true "A Discord Server")

*A server with one text channel and two voice channels.*

# Joining a Server
Users can join servers by going to the invite link in their browser or by scrolling down to the bottom of their server list, clicking the + icon, and entering the invite code.

If however, the user is already on 100 servers can they no longer join any new one nor create any.

## Creating a Server
Users can create a server by scrolling to the bottom of their server list and clicking the + icon.


# Basic Features
By default can a Discord Server have [Text Channels](#text-channels), [Voice Channels](#voice-channels), [Roles](#roles) and [Custom Emojis](#custom-emoji).

## Text Channels
Text channels are how users communicate with each other on a server. Users with the "Manage Channels" permission may create and delete text and voice channels. These extra text channels may be edited so that only certain roles and/or users may read it.

As of a new update, the first channel created will not be the default text channel. The default channel now changes to the one with the lowest permissions.

## Voice Channels
Voice channels allow server members to talk to each other using their voices. There is no default voice channels and all permissions may be edited for any voice channel. Servers are not required to have voice channels, but they make the party a bit more fun!

Voice channels also allow members with Nitro to share their screen or game with others in the same channel. This requires the 'Go Live' permission.

## Roles
Servers contain [roles](/roles) which - when assigned - give users certain permissions, a custom name-color (if set) and can separate them from others in the member list on the right (if set).

Servers typically use roles to assign special permissions or signify a rank on an external website, but they can also be used for other things such as providing information about someone, quick punishments (e.g. muting) or for updates and news (tagable roles).

## Custom Emoji
Servers can have up to 50 static and 50 animated [emoji](/emoji) (Often refered to as "Emote" in Discord's documentation).
While anyone with sufficient permission may use static emoji can only users with Nitro Classic or higher use animated ones.

### Uploading Emojis
User with 'Manage Emojis' permission may be able to upload emoji to the server. In order to do that go to the Server Settings and then click on the 'Emoji' button. After that click the blurple button and select the Emojis you want to upload and use. When doing so keep the [limitations](#limitations) in mind.

### Usage on other Servers
User with at least Nitro Classic may use custom emoji in other servers, as long as they have 'Use External emojis' permission in the Text Channel.

### Limitations
- Uploaded emoji can only be deleted or have their name changed (Only allows A-Z, '-' and '\_')
- File size may not be higher than 265kB
- Only user with at least Nitro Classic and 'Manage Emojis' permission may upload animated emoji under the above requirements
- Amount of emoji is set to a total of 100 (50 static and 50 animated). This number can be increased through [Server Boosting](/server-boosting)

# Community Features
Server owners have the option to enable the Community Section in their Server's Settings to turn it into a Community Server.
Community Servers have the option to create [News Channels](#news-channel), enable [Member Screening](#member-screening) and a [Welcome Screen](#welcome-screen) and can also get access to Server Insights for useful statistics. The last option however requires a certain amount of members to be on the server to be actually available.

Finally can Community Servers also [apply for partnership](/partner), which has its own set of requirements and benefits.

## News Channel
This channel allows users to follow it, by clicking a "Follow" button at the bottom of the channel (Where usually the text field is) and then selecting a Guild followed by a Text Channel.
Only Servers you have Manage Server permissions on will appear in the drop-down menu.

Users with permissions to write in this channel (Disabled for `@everyone` by default) can publish their own messages they've send in that channel, while users with Manage Message permissions for this channel can also publish messages of other users.

When a message is published will it appear on any Server that follows it as a webhook message with the "SERVER" label and the Server's icon. The displayed name and icon can be altered if desired.

Editing a message has a higher rate limit than editing a normal message and deleting the original message will make the published message on the other Servers appear as "[Original Message deleted]" which is one if not the only dynamic webhook message that changes depending on your set language.

Published messages support all basic features of a normal message (Formatting, embeds, images and attachments).

## Member screening
Member screening is a feature which allows you to set a variety of rules that a newly joined member has to accept in order to gain full access to the Discord Server.
While the new Member hasn't accepted the rules will they be unable to send messages in any channels and also won't be able to send any direct messages to other members of the Server. They still have read access to the channels however.

The text for the displayed rules allow all markdown formatting such as **bold**, *italic* or <u>underline</u>, Channel mentions, user/role mentions and the usage of emojis and custom Emotes, including those of external servers.

## Welcome Screen
The welcome screen allows you to set a small Server description alongside a set of channels with a unicode Emoji (Custom ones won't be selectable) and a short description for those.
The newly joined Member will see that screen and can then select the channel they want to directly jump to, or close the window.

Only channels that `@everyone` has read permissions for can be selected.

# Verification Levels
Server administrators may toggle the verification level. When a verification level is set, members must meet the criteria before they can create a direct message with someone in the server or send messages in a text channel. If a member is assigned a role, they will bypass the verification.

| Level: | Restrictions:                                                   | Note:                                             |
| ------ | --------------------------------------------------------------- | ------------------------------------------------- |
| None   | Unrestricted                                                    | Default Setting. Not usable for Community Server. |
| Low    | User must have a verified email on their Discord account.       |                                                   |
| Medium | User must also be registered on Discord for at least 5 minutes. |                                                   |
| High   | User must be a member of the server for at least 5 minutes.     | Formerly known as `(╯°□°）╯︵ ┻━┻`                  |
| Highest | User must have a verified phone on their Discord account.      | Formerly known as `┻━┻ ﾐヽ(ಠ益ಠ)ノ彡┻━┻`              |

# Vanity Invites
Some servers have the ability to be able to set a custom invite link, instead of a randomly generated one. One example is https://discord.gg/discord-developers. Servers gain the ability to set vanity invites if they are a [Discord Partner](/partner), [Verified Server](/verified-servers), the server has reached Level 3 boost through [server boosting](/server-boosting) feature or is owned by a Discord Developer. Any member with Manage Server can customize the vanity invite.