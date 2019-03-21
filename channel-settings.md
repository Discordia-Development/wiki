<!-- TITLE: Channel Settings -->
<!-- SUBTITLE: Description of channel settings -->

# Channel Settings
Channel settings are configurations specific to channels.

> Accessing Channel Settings

![Channel settings](/uploads/channel-settings/75-da-26-1.gif "Channel settings")

Channel settings can be accessed by hovering over the channel and pressing the gear <img src="/uploads/icons/settings.png" alt="settings" width="25" height="25"/> , or by right-clicking the channel and pressing **Edit Channel**. You must have the **Manage Channel**, **Manage Permissions**, or **Manage Webhooks** permission to be able to access the channel settings menu itself. Members with the **Manage Channel** permission can also delete the channel.

## Channel Types

* **Text Channels** <img src="/uploads/icons/channel.png" alt="channel" width="25" height="25"/> allow users to send messages and images (if permissions allow them to).
	* Locked Text Channels <img src="/uploads/icons/locked-channel.png" alt="locked-channel" width="25" height="25"/>
	* NSFW Text Channels <img src="/uploads/icons/nsfw-channel.png" alt="nsfw-channel" width="25" height="25"/> allow users to send NSFW content. NSFW content being sent in channels that are not marked NSFW violate Discord's [Community Guidelines](https://discordapp.com/guidelines).
* **Voice Channels** <img src="/uploads/icons/voice-channel.png" alt="voice-channel" width="25" height="25"/> allow users to talk with their microphone (if permissions allow them to)
	* Locked Voice Channel <img src="/uploads/icons/locked-voice-channel.png" alt="locked-voice-channel" width="25" height="25"/>
* A **Store Channel** <img src="/uploads/icons/store-channel.png" alt="store-channel" width="25" height="25"/> is a channel type only available on Verified Servers. You can only have one Store Channel ina server
* A **News Channel** <img src="/uploads/icons/news-channel.png" alt="news-channel" width="25" height="25"/> is a channel type only available on Verified Servers. These channels allow users to view news about your game, and news posted here will be put in the Activity Feeds of players.

# Tabs

## Overview

The Overview tab enables members with the **Manage Channel** permission to change the channel name, channel topic, slowmode interval, or the NSFW configuration.

### Slowmode

The slowmode configuration edits the interval in seconds that members that are not immune to slowmode must wait before sending another message. To be immune from slowmode, you must either have the **Manage Messages** or **Manage Channel** permissions. In the client, the interval can only be changed to the shown numbers, but via bots or by API requests, it can be changed to anything from 0 (off) to 120 (max) seconds. If the interval is set via bots or the API, it will round to the closest interval in the channel settings, but will still force members to wait the configured time.

![Slowmode settings](/uploads/channel-settings/88-e-103-1.gif "Slowmode Settings")

## Permissions

The Permissions tab enables members with the **Manage Permissions** permission to edit role and member permissions within the channel.

## Invites 

The Invites tab enables members with the **Manage Channel** permission to delete invites for that channel.

## Webhooks

The Webhooks tab enables members with the **Manage Webhooks** permission to manage invites for that channel.
