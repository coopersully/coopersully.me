---
author: "Cooper Sullivan"
title: "Guardian"
date: 2021-09-15
summary: "A friendly and feature-rich bot made to serve as an all-in-one solution for Discord servers."
tags: ["discord", "java", "json"]
Categories: ["personal"]
draft: false
---

![](/images/guardian-banner.png#center)

### 📖 What is Guardian?
Guardian is a friendly, feature-rich moderation tool for Discord servers with several features:
- A built-in file manager, allowing users to upload, edit, and access bot-hosted files.
- Connections to popular games such as VALORANT and Fortnite, allowing users to track their stats.
- Connections to social media sites such as Twitter and Instagram, allowing users to search the platforms via easy chat commands.
- An in-depth event and change log like no other, monitoring [almost every event](https://guardian.coopersully.me/docs/logs/) occurring in guilds.

### 🔎 Overview
#### Advanced Audit Logging
While Discord's native Audit Logs are a great way to keep a record of different happenings in your server,
they're pretty incomplete and lack detail. Each server's Audit Logs, however, are managed automatically by
Discord's basic moderation and cannot be modified, added to, or changed; this is why many popular bots such
as [MEE6](https://mee6.xyz/), [Dyno](https://dyno.gg/), and more create their own channels in which they log
events, etc. Guardian accomplishes this exact task, but better. 

Guardian's logs are unbelievably extensive, logging 20+ events by default with the possibility of so much more.
Each event is recorded in a neat and compact fashion, highlighting the issue and important details without cluttering
the text channel. At the end of every recorded event, Guardian attaches tags for the entry, noting the keywords
of the occurence so that they can be searched through later.

![](/images/guardian/stop-boosting.png#center)
![](/images/guardian/search-tags.png#center)

Users with the ``View Audit Logs`` permission may also manually add notes to the log if they so choose. These notes
are added in the same format as other events, with the tags being automatically determined by Guardian's artificial
intelligence.

#### Automatic Chat Moderation
Guardian will automaticall delete message containing explicit language, depending on the current chat-moderation setting of the guild. The possibilities are as follows:
    1. ``OFF`` disables chat moderation entirely; no language will be filtered.
    2. ``LOW`` enables light chat moderation, filtering out slurs.
    3. ``MEDIUM`` enables moderate chat moderation, filtering out intense swearingm, expletives, and slurs.
    4. ``HIGH`` enables intense chat moderation, filtering out profane language of any kind.
	
This setting can also be disabled per-channel if the guild owner so desires. You can read more about this option in Guardian's official documentation under the [channel tags](https://guardian.coopersully.me/docs/tags/) section.

Additionally, the bot will automatically delete messages containing harmful links and malicious websites and timeout the offending user for 1 hour.
This allows the staff to have time to respond to the situation appropriately. Of course, these events are all logged via Guardian's audit-logging system.

#### Commands
Perhaps one of Guardian's greatest features, the bot adds tons of commands for greater server moderation, feature control, 
web-searching, and of-course a few party-trick commands for members of the server to play around with. All of the bot's
commands and their explanations couldn't possibly fit in this overview, but you can view them all in Guardian's official
documentation under the [commands](https://guardian.coopersully.me/docs/commands/) section. A few highlighted commands are below.
- ``/user join-date [user]`` retrieves the timestamp at which a user joined the current guild.
- ``/lock [channel]`` and ``/unlock [channel]`` allows moderators to limit @everyone from sending messages and/or speaking in a specified channel.
- ``/embed <title> [description] [footer] [color] [channel]`` creates and sends an advanced embedded-message with customizable features, allowing moderators to send unique and eye-catching updates.
- ``/apex <origin ︱ xbox ︱ playstation> <username>`` retrieves a player's average Apex Legends statistics from any platform.
- ``/imgur <query>`` searches for an image around the internet using Imgur.
- ``/storage <view ︱ upload ︱ download> <path>`` allows administrators to view, download, and upload files stored in the bot's directory.
- ``/dadjoke`` replies with a witty dad-joke with 202,426 possibilities.

### 📚 Learn more about the project:
> This is just a sprinkle of the features that Guardian can add to a Discord server. 
If you're interested in seeing all of Guardian's additions, would like to view its documentation, 
or have any questions, visit it's official website below.

If you'd like to explore the project a bit more, you can see its public website and documentation below.

🔗 [Click here to view this project on it's website](https://guardian.coopersully.me/)