<!-- TITLE: Roles -->


# Roles 

## Overview
A role is a part of a server, and when applied to a user, will give the user permissions and a color, if colors are set. 

# Permissions
A role may have any combination of permissions, from Administrator to just Use External Emojis.

Permissions are divided between General Permissions, Text Permissions, and Voice Permissions.

## Role Settings

* **Display role members seperately from online members** will show members of a role in a seperate group above default users, which is determined by role order. This is sometimes known as *hoisting* a role.

* **Allow anyone to @mention this role** allows any user to mention every member of a role at once, similar to how an @everyone ping functions. This is typically applied to moderation roles.

## General Permissions

* Most permissions in this section are server-management related permissions. Many of these permissions can be dangerous, and should only be given to users you can trust.

* The **Administrator** permission gives a user every single permission, and also ignores channel-specific settings. **This permission is not recommended to be given out to someone you do not trust**.

* The **View Audit Log** permission allows a user to view the server's audit logs.

* **Manage Server** allows a user to edit the server name, server icon, voice region, and the verification level. 

* **Manage Roles** allows a user to access the roles menu, and edit roles below their highest role. Users cannot take or give permissions they do not have.

* **Manage Channels** allows a user to delete and create new text and voice channels. This also applies to [channel categories](/channel-categories)

* The **Kick Members** permission allows a user to kick anyone who is below them in the heirarchy. 

* The **Ban Members** permission allows a user to ban anyone who is below them in the heirarchy. This also allows a user to access the ban list, and unban members from it.

* **Create Instant Invites** allows a user to create a instant invite for the server. Instant Invites can be revoked in the Instant Invites channel by anyone with Manage Server.

* The **Change Nickname** permission allows a user to change their own nickname. This nickname can still be changed by anyone above them with the Manage Nicknames permission.

* The **Manage Nicknames** permission allows users to rename a user with a nickname. Users can only apply or edit nicknames of users below them in the role heirarchy.

* The **Manage Emojis** permission allows users to access the Emojis tab in Server Settings. This allows them to upload, delete, and rename emojis. 

* The  **Manage Webhooks** permission allows a user to view, create, delete, and edit webhooks on any channel. Webhooks can be used to speak in the channel it is created in, even with the user not being on the server.

* The **Read Text Channels & See Voice Channels** permission allows a user to see all the text and voice channels that are available as default to users on the server. Without this or an appropriate role, a user will see no channels on a server.

## Text Permissions

* **Send Messages** allows a user to send messages in any channel unless denied by that channel's permissions.

* **Send TTS Messages** allows a user to use /tts in any channel unless denied by that channel's permissions. This feature is disabled on many servers, and can be disabled client-side in [User Settings](/user-settings).

* **Manage Messages** allows a user to delete, pin, and unpin messages, unless denied by that channel's permissions.

* **Embed Links** allows users to post links and have them embed. This can be denied per channel permissions.

* **Attach Files** allows users to upload files. This cna be denied per channel permissions.

* **Read Channel History** allows users to read the channel's history. If denied, they can only view history as far as they have seen the channel, and is reset after they reload the client.

* **Mention Everyone** allows users to mention @everyone or @here, unless denied by that channel's permissions.

* **Use External Emojis** allows users to use External Emojis, such as BTTV/Twitch global emojis, and emojis from other servers, if they have [Discord Nitro](/nitro). This can be denied by a channel's permissions.

* **Add Reactions** allows users to add reactions to any message, unless denied by that channel's permissions. 

## Voice Permissions

* **Connect** allows users to connect to a Voice Channel, unless denied by that channel's permission.

* **Speak** allows users to speak in a channel, unless denied by that channel's permission, or has been Server Muted.

* **Mute Members** allows a user to Server Mute other members, which makes the muted user unable to be heard by anyone in the channel. 

* **Defean Members** allows a user to Server Deafen other members, which makes the deafened user unable to hear anyone in the channel.

* **Move Members** allows a user to move any member from any channel to another. 

* **Use Voice Activity** allows a user to not have to use Push-to-Speak, unless denied by that channel's permissions.

# Other Info

A role can have a color from the 22 default colors, have a HEX color, or have no color at all. Users take the color of the highest role in their list, as long as it has a color.

When adding a bot to a server, it can ask for permissions. If given, this will make an undeletable role that can also not be given to any user manually. If no permissions are given, no role will be created.

The @everyone role cannot be deleted, renamed, given a color, or hoisted.