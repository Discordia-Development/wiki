---
title: Chat Commands
description: Describes all chat commands available, even the non-obvious/non-documented ones
published: true
date: 2019-11-24T20:16:06.381Z
tags: 
---

# Discord Chat Commands
While some of Discord's "slash" commands are fairly obvious to access, there are some things that can be done in the Message box that are somewhat undocumented (or hard to find information about). To avoid having to dig through changelogs and support articles, here are the things you can do in the Message box:

* **React to the previous message** (Desktop and iOS): To add a reaction to the previous message in chat, simply write `+:emojiname:` in your message box, and send it. For instance, reacting `+:smile:` adds the smile reaction. This even works with custom emojis, assuming you're on the right server or you have nitro!
* **Edit your previous message with up arrow** (Desktop only): Instead of having to right-click on a message, select "Edit Message" and clicking inside the edit box, you can simply hit the *Up* arrow on your keyboard to edit your last message in that channel!
* **Fix a quick typo with s/text/replace** (Desktop and iOS): Typed "teh" instead of "the" and want to quickly fix it? Use `s/teh/the` ! Using any variation of `s/one word/another word` will edit your previous message. It only changes a single instance (the first one), but to fix a quick typo it's great!
* **Get the ID of a mentionable item**: Anything that can be mentioned in chat (emoji, user, channel, role, etc) can be used to get the ID of that item. For instance, type in `\@user` to get a user's ID. `\@role` to get a role ID, `\#channel` to get a channel ID. Regular unicode emojis will give you the real unicode character (instead of the image) which can then be used in your username, so `\:poop:` to your heart's content! 
* **Get a unicode emoji**: If you escape an emoji with a `\` you will get its unicode form. So, `\:smiley:` doesn't return the discord version of `:smiley:` but returns the unicode one (😃). Note: This only works with standard emoji, not with custom ones.

## Slash Commands

These slash commands are only available on the Desktop and iOS apps. Unfortunately, Android users don't have that luck.

* `/tableflip [message]` : Outputs `(╯°□°）╯︵ ┻━┻` in chat. Adding text after it will add the tableflip emoticon after it
* `/unflip [message]` : Outputs `┬─┬﻿ ノ( ゜-゜ノ)` in chat. Adding text after it will add the unflip emoticon after it
* `/shrug` : Outputs `¯\_(ツ)_/¯` in chat. Adding text after it will add the shrug emoticon after it
* `/me <a message here>` : Outputs your message in italics, in the style of IRC. Identical to just surrounding your message with `*<a message here>*` (`*` for italics)
* `/nick <new nickname>` : Changes your nickname on the server to what you place after the command. Requires "Change Nickname" permissions on the server.
* `/tenor <search query>` and `/giphy <search query>` : Searches animated gifs on the web, using those 2 websites.
* `/spoiler <message to be spoiled>`: Puts anything after the slash command in a spoiler. If nothing is put after the command it will send `||||`.

> `<something>` indicates a "placeholder", meaning you can replace it with any text you like.
> `[something]` indicates a optional "placeholder", meaning you can replace it with any text you like, but it's optional.