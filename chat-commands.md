---
title: Chat Commands
description: Lists all the chat commands available, even the non-obvious/non-documented ones.
published: true
date: 2020-10-25T16:22:40.042Z
tags: 
editor: markdown
dateCreated: 2020-01-09T05:19:49.964Z
---

# Discord Chat Commands
While some of Discord's "slash" commands are fairly obvious to access, there are some things that can be done in the Message box that are somewhat undocumented (or hard to find information about). To avoid having to dig through changelogs and support articles, here are the things you can do in the Message box:

## Chat functions
There are some chat functionalities, which aren't that obvious, but make using the chat a bit easier.

### React to the previous message
Available on Desktop and iOS.  
When you type `+:emojiname:` in chat and send it, will the last message receive the mentioned emoji as a reaction.  
This also works with Emotes (custom Emojis) but requires you to be on the same Server or have Nitro for it.

### Edit your previous message with up arrow
Available for Desktop.  
If you want to edit your previously send message, do you not need to right-click it and then select "Edit Message".  
Instead can you just press the *up arrow* key on your keyboard to edit it.

### Fix a quick typo
*Available for Desktop and iOS.* 
Typed "Teh" instead of "The" and want to correct it real quick? Just type `s/Teh/The` in the chat to automatically edit your last message. It only changes a single instance (the first one), but is quite useful to quickly correct some typos!

### Get the ID of a mentionable item
Anything that can be mentioned in chat (Emotes, User, Roles, Channels, etc.) can be used to get the ID of that specific item.  
For example will `\@User` show the ID of the mentioned User, `\@Role` the ID of the mentioned role, `\#Channel` the ID of the mentioned channel and so on.

**Keep in mind that the user/role will still be mentioned!**

### Get a unicode emoji
You sadly can't use `:poop:` in your name to display the poop Emoji.  
But you can get the unicode emoji of `:poop:` by prefixing it with a `\`. That way `\:poop:` will become 💩, which you can use in your name.

### Text formatting
Discord added multiple keyboard combinations, which allow you to format your message, similar to a Text-Editor.  
Here is a list of all keyboard combinations and what they do:
- <kbd>Ctrl</kbd> + <kbd>B</kbd>: **Bold**
- <kbd>Ctrl</kbd> + <kbd>I</kbd>: *Italic*
- <kbd>Ctrl</kbd> + <kbd>U</kbd>: <u>Underlined</u>

> **Important!**  
> You need to highlight text in order to use the above keyboard combinations.
{.is-warning}

## Slash Commands

A large majority of these slash commands are only available for the Desktop and iOS clients. Android users only have access to `/tableflip`, `/unflip` and `/shrug`.

> **Note**:
> `<text>` is required and `[text]` is optional.
{.is-info}

### `/tableflip [message]`
Outputs `(╯°□°）╯︵ ┻━┻` in chat.

Appending a message after the command will add the Emoticon at the end of it.
For example will `/tableflip I don't like this table.` turn into `I don't like this table. (╯°□°）╯︵ ┻━┻`

### `/unflip [message]`
Outputs `┬─┬ ノ( ゜-゜ノ)` in chat.  

Appending a message after the command will add the Emoticon at the end of it.
For example will `/unflip I do like this table tho.` turn into `I do like this table tho. ┬─┬ ノ( ゜-゜ノ)`

### `/shrug [message]`
Outputs `¯\_(ツ)_/¯` in chat.  

Appending a message after the command will add the Emoticon at the end of it.
For example will `/shrug I prefer chairs.` turn into `I prefer chairs. ¯\_(ツ)_/¯`

### `/me <message>`
Outputs your message in *italics*, in the style of IRC. Identical to surrounding your message with asterisks (`*`, `*<message here>*`)

### `/nick <new nickname>`
Changes your nickname on the server to the provided one.  
You need "Change Nickname" permission on the Server in order to use this.

### `/tenor <search query>` and `/giphy <search query>`
Searches through Tenor or Giphy (Depending on which command you used) for gifs matching the provided search query.

### `/tts <message>`
Uses text-to-speech to read the message to all members, which can view the channel and have the "Text-to-speech" setting active.
You need the "Send TTS Messages" permission on the server/channel and also need to have the "Text-to-speech" option in your settings enabled in order to use this command.

> **Note**
> At the moment, text-to-speech doesn't work on mobile.
{.is-info}

### `/spoiler <message>`
Puts the provided message in spoilers. This is identical to surrounding your message with `||`s (`||<message here>||`)