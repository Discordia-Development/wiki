---
title: Chat Commands
description: Describes all chat commands available, even the non-obvious/non-documented ones
published: true
date: 2020-03-16T18:02:31.456Z
tags: 
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
Available for Desktop and iOS.  
Typed "Teh" instead of "The" and want to correct it real quick? Just type `s/Teh/The` in the chat to automatically edit your last message. It only changes a single instance (the first one), but is quite useful to quickly correct some typos!

### Get the ID of a mentionable item
Anything that can be mentioned in chat (Emotes, User, Roles, Channels, etc.) can be used to get the ID of that specific item.  
For example will `\@User` show the ID of the mentioned User, `\@Role` the ID of the mentioned role, `\#Channel` the ID of the mentioned channel and so on.

**Keep in mind that the User, Role, ... is still getting mentioned!**

### Get a unicode Emoji
You sadly can't use `:poop:` in your Name to display the Poop Emoji.  
But you can get the unicode Emoji of `:poop:` by prefixing it with a `\`. That way will `\:poop:` become 💩, which you can use in your name.

### Text formatting
Discord added multiple keyboard combinations, which allow you to format your message, similar to a Text-Editor.  
Here is a list of all keyboard combinations and what they do:
- `Ctrl + B`: **Bold**
- `Ctrl + I`: *Italic*
- `Ctrl + U`: <u>Underlined</u>

> **Important!**  
> You need to highlight text in order to use the above keyboard combinations.

## Slash Commands

These slash commands are only available on the Desktop and iOS apps. Unfortunately, Android users don't have that luck.

> **Note**:
> `<Text>` is required and `[Text]` is optional.

### `/tableflip [Message]`
Outputs `(╯°□°）╯︵ ┻━┻` in chat.  
When you attach a message to the command (`/tableflip I don't like this table.`) will the emoticon be attached to the end of the message (`I don't like this table. (╯°□°）╯︵ ┻━┻`).

### `/unflip [Message]`
Outputs `┬─┬ ノ( ゜-゜ノ)` in chat.  
When you attach a message to the command (`/unflip I do like this table tho.`) will the emoticon be attached to the end of the message (`I do like this table tho. ┬─┬ ノ( ゜-゜ノ)`).

### `/shrug [Message]`
Outputs `¯\_(ツ)_/¯` in chat.  
When you attach a message to the command (`/shrug I prefer chairs.`) will the emoticon be attached to the end of the message (`I prefer chairs. ¯\_(ツ)_/¯`).

### `/me <Message>`
Outputs your message in *italics*, in the style of IRC.  
Identical to surrounding your message with `*` (asterisks. `*<Message here>*`)

### `/nick <New Nickname>`
Changes your nickname on the server to the provided one.  
You need "Change Nickname" permission on the Server.

### `/tenor <Search Querry>` and `/giphy <Search Querry>`
Searches through Tenor or Giphy (Depending on which command you used) for gifs matching the provided search querry.

### `/spoiler <Message>`
Puts the provided message in spoilers.  
Identical to surrounding your message with `||` (`||<Message here>||`)