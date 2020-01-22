---
title: Server Settings
description: 
published: true
date: 2020-01-22T09:18:03.933Z
tags: 
---

The settings below are specific to servers.

> Accessing Server Settings

<p style="text-align: left;"><img src="https://cats.needs-to-s.top/e5d137.gif" alt="Access Server Settings" align="middle"></p>

# Tabs

## Overview
Within the Overview tab, users with the **Manage Server** permission can change the icon, name, and server region of the server.

Users can select the AFK voice channel, and the default timeout before entering it.

Users can also set the [new member messages channel](https://discordia.me/new-member-messages) here.

The Default Notification settings are also in this tab, and include **All messages** or **Only @mentions.** **Only @Mentions** being enabled is recommended for public Discord servers.

## Moderation
Inside of the Moderation tab, the **Verification Level** and **Explicit Content Filter** can be changed. A server owner can also enable **[Server Two-Factor Authentication](/2fa)** from here.

### Verification levels include:
* **None** - Unrestricted
* **Low** - A user must have a verified email on their Discord account.
* **Medium** - In addition to Low, must be registered for more than 5 minutes. 
* **(╯°□°）╯︵ ┻━┻** - In addition to Low and Medium, must be in the server for 10 minutes.
* **┻━┻ ﾐヽ(ಠ益ಠ)ノ彡┻━┻** - In addition to Low, Medium and Tableflip, must have a verified phone number on their Discord account.

### Explicit Content Filter settings include:

* Don't scan any messages.
* Scan messages from users without a role.
* Scan messages sent by all members.

Server Two-Factor Authentication requires users to have Two-Factor Authentication enabled to have administrative abilities, such as banning members and accessing server settings. User accounts that own bot accounts must also have Two-Factor Authentication enabled to have the bot be able to use administrative permissions.

## Audit Logs

This tab allows users with the **View [Audit Logs](/audit-logs)** permission to view all the actions taken in the server, for example bans, and creating instant invites. It is possible to filter the results by users involved, and the actions taken.

## Roles

In this tab, users with **Manage Roles** can edit settings on roles below their top role. Managing roles means that users can delete the role, rename the role, change the role's color, and manage permissions on the role. Adding permissions you don't have to roles is not possible, and removing permissions that are only given to you by that role is also not possible.

## Integrations

Users with the **Manage Server** permission can add their *partnered* Twitch or Youtube Gaming accounts to the server. This allows you to sync your Subscribers (Twitch) or your Sponsors (Youtube Gaming) to a role on your Discord Server. Twitch *affiliates* can also make use of this functionality.

## Emoji

In this tab, users with **Manage Emoji** can rename emojis, upload new ones, view who uploaded them, and delete emojis. There is a 50 emoji limit per server, and users may only use emojis in that server, unless they have [Discord Nitro](/nitro). Animated Emojis have their own 50 emoji limit. More info about emojis can be found [here](/emoji). 

## Webhooks

This tab allows users with the **Manage Webhooks** permission to create, edit, delete, and view who made a webhook. More info about Webhooks can be found [here](https://support.discordapp.com/hc/en-us/articles/228383668-Intro-to-Webhook).

## Widget

The Widget tab has options for users who have **Manage Server** to edit the widget for the server. Users can enable the widget, and pick a channel for the widget to link to. If no channel is selected, only the online count and voice channels will be shown. A iframe widget is available to embed directly onto your website. A JSON API widget is also available.

## Vanity URL

This tab is only available to users with **Manage Server**, and only to servers that are partnered. More information about partners can be found [here](/partner), or [here](https://discordapp.com/partners).


-----


## Members

In this tab, users with **Manage Server** can view Members. Users with **Manage Nicknames** can change nicknames, server owners can Transfer Ownership, users with **Kick Members** can kick and prune, users with **Ban Members** can ban, and users with **Manage Roles** can add or remove roles from users, if that user is below them in the hierarchy. 

### Member Pruning

Users with **Kick Members** can access the Prune Members menu. The choices for pruning includes:
* kicking users last seen online or invisible one day ago
* kicking users last seen online or invisible 7 days ago
* kicking users last seen online or invisible 30 days ago

Users with roles will not be kicked.

## Invites
In this tab, users with the **Manage Server** permission can see instant invites created on the server. It shows the duration of an invite, the creator, the channel, and the number of uses on it. Users can also delete these invites by pressing the Revoke button on the right of the invite.

## Bans

This tab allows you to search the banned members and unban, if you have the **Ban Members** permission. 


-----


## Delete Server
If you are the server owner, the Delete Server option appears at the bottom of the list. This will prompt you to confirm the decision, by typing in the server name, and if you have [2FA](/2fa) enabled, you will be required to input a code before deletion.