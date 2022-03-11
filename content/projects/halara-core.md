---
author: "Cooper Sullivan"
title: "Halara-Core"
date: "2021-08-11"
summary: "A spigot plugin that adds commands and mechanics for all servers on Halara Network."
tags: ["minecraft", "mods", "spigot-api"]
ShowToc: false
ShowBreadCrumbs: false
draft: false
---

![](/images/halara-plugins/red.png#center)

### 📖 What is Halara-Core?
Halara-Core is a plugin (additive file) for Minecraft: Java Edition built with the [Spigot API](https://hub.spigotmc.org/stash/projects/SPIGOT).
Originally created for the [Halara Minecraft Network](https://mc.halara.net), Halara-Core serves as a library of custom GUIS, commands,
and more for use all throughout the network.

### 🔎 Overview
#### Commands
- ``/help`` greets the user with an interactive chat-menu of F.A.Q.'s and useful topics for server-related issues. 
	- Each topic contains a hyperlink to the server's website for a more detailed description of the corresponding issue and possible solutions.
- ``/fakejoin [user]`` sends a pseudo-"join event" packet to the server, displaying a false user join message.
	- This command can only be used by users with the ``group.moderator`` permission node.
- ``/fakeleave [user]`` sends a pseudo-"join event" packet to the server, displaying a false user join message.
	- This command can only be used by users with the ``group.moderator`` permission node.
- ``/go`` opens an interactive server-selection G.U.I. in which users can select a server in the network to connect to.
	- Each possible server is represented with an icon in the menu, clicking the icon connects to the server.
	- When hovered, each icon displays the server name, a brief description, and the current status of the server (pictured below).

![](/images/halara-core/menu.png#center)
	
### 📚 Learn more about the project:
If you'd like to explore the project a bit more, view any of its code, or create a ticket,
you can visit its public GitHub repository.

🔗 [Click here to view this project on GitHub](https://github.com/coopersully/halara-core)