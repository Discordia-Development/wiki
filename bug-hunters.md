---
title: Bug Hunters
description: Helping Discord Developers manage Bug Reports and fix Bugs
published: true
date: 2020-09-23T21:43:56.554Z
tags: 
editor: markdown
dateCreated: 2020-01-09T04:56:27.542Z
---

# Bug Hunters
Bug Hunters are an elite group of Discord users, who have successfully found bugs with Discord on any client that could also be reproduced by other users. They help the Discord developers to learn about bugs and fix them.

Every day, they get on Discord and continue to search and verify other bugs that other users have reported. They use [Discord Canary](/canary), and work hard every day to help new users find bugs, check if they're a duplicate of already reported bugs, and sometimes help others format their report.

## How to become a Bug Hunter
Becoming a Bug Hunter isn't that easy as it contains several steps before you can actually submit a bug.

### Prerequisite
Before reporting any bug should you make sure that it isn't caused by any 3rd party application, that it isn't already fixed on a Canary Build and that you use the official Discord Client and not a 3rd party one such as BetterDiscord or Powercord.

### Join the Discord Testers Server
Now, to become a Bug Hunter, you first have to join the [Discord Testers Server](https://discord.gg/discord-testers).
At the beginning will you only have access to a few selected channels. You'll then get a Direct Message from a Bot called DBug. It will provide you with a few links such as an article on how to download and install either the Discord Canary or Discord PTB Client.

### Solve the Quiz
You will need to make a quiz in order to access more of the Server. Just run the command `!quiz` inside your DMs with DBug and it will provide you with a Link to a google form and also a 1-time Code for it.
Fill out the required fields with what you think is the right answer. After submiting the Form will DBug inform you about whether you managed to pass the quiz or not. If you failed the quiz will you be able to try it again after a certain time.
When you managed to pass the quiz will you receive access to more channels such as the `#bughunter-general-chat.`

### Assign roles
In order now to report the Bug for your platform (i.e. Windows) will you need to assign yourself some roles first. Go back to your DMs with DBug and use `!role add <platform>` (Replace `<platform>` with whatever platform you have. For example would Windows, Linux and Mac be `desktop`).
You should now receive the right roles. Note that you can execute `!role list` to see all roles you can assign to yourself.

### Report the bug!
Now to the most important part: Reporting the Bug!
In order to report a bug will you need to use the `!submit` command in the right `#<platform>-cug-reports` channel.
The command uses specific *flags* for different parts of the Bug report.

Here's a full example of such a command:
`!submit -t Title of bug -r First Step ~ Second Step ~ Third Step -e What actually should happen -a What actually happens -c The Discord Client you use -s Your OS info`

A complete and more in-depth explanation about the commands of DBug can be found in [this article](https://support.discord.com/hc/en-us/articles/360045884472).

### Can/Can't reproduce
If your bug was already reported and you can reproduce the actual issue, can you use the `!canrepro <id> <info>` command in the right channel to note that you can reproduce this bug.
The same goes for when you **can't** reproduce a bug but this time is the command `!cantrepro <id> <info>`

> **Pro-Tip:**
> You can save your System information using the `!info store` command to then use the right info in the above command (i.e. `!canrepo 0 -w` for Windows System info)
{.is-info}

## What do I get?
The Discord Testers Server has multiple "tiers". You can unlock a tier when meeting the right reqiuirements for it.

> Note that any mention of `X*` means that the actual amount of approved Bug Reports for this tier is undisclosed.
{.is-info}

## Tabs {.tabset}
### Tier 1: @everyone
Everyone joining Discord Testers has this tier.
It doesn't have any benefits but actual limits such as only having access to specific channels.

### Tier 2: Bug Hunter
**Requirements:**
- Pass the Bug Hunter Quiz

You gain access to the `#announcements` channel and to the different bug hunter channels. You're also able to submit bugs to the different channels.

### Tier 3: Bug Squasher
**Requirements:**
- X* approved Bug Reports
- Bug Hunter Rank

This tier unlocks access to the approval queue meaning you can approve or deny Bug reports. Additionally do you also get access to the Bug Squasher chat.

### Tier 4: Bug Tracker
**Requirements:**
- Demonstration of proper usage of the Approval queue
- X* approved Bug Reports
- Bug Squasher Rank

You get access to Discord Focus Tests and also the [Bug Hunter Badge](/badges#discord-bug-hunter).

### Tier 5: Bug Terminator
**Requirements:**
- Maintained activity over a 6 month period
- X* approved Bug Reports OR successfully helped on Discord Focus Tests
- Bug Tracker Rank

You receive the [Golden Bug Hunter Badge](/badges) and a possible chance of becoming a Junior Moderator.