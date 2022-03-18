---
author: "Cooper Sullivan"
title: "Halara-Lobby"
date: "2021-08-11"
summary: "A spigot plugin that adds commands and mechanics for the Main Lobby on Halara Network."
tags: ["minecraft", "mods", "spigot-api", "java"]
Categories: ["personal"]
ShowToc: false
ShowBreadCrumbs: false
draft: false
---

![](/images/halara-plugins/orange.png#center)

### 📖 What is Halara-Lobby?
Halara-Lobby is a plugin (additive file) for Minecraft: Java Edition built with the [Spigot API](https://hub.spigotmc.org/stash/projects/SPIGOT).
Originally created for the [Halara Minecraft Network](https://mc.halara.net), Halara-Lobby moderates the "Main Lobby" server and adds various
automations & user-interfaces for a much quicker and easier server-navigation experience. This project depends on [Halara-Core](https://coopersully.me/projects/halara-core/).

### 🔎 Overview
#### Event Listeners
- User Connections: detects when a player connects to the server specified in the plugin's ``config.yml``.
	- Moves the player's character to the world's origin (X: 0, Y: 0, Z: 0)
	- Changes the player into Adventure Mode, preventing them from interacting with the surrounding environment.
	- Makes the player completely invisible and immobile.
	- Opens the "Server Selection" G.U.I. provided by **Halara-Core**.

#### Commands
- ``/fixspeeds`` resets the player's walking and flying speeds to their default values.

### 📚 Learn more about the project:
If you'd like to explore the project a bit more, view any of its code, or create a ticket,
you can visit its public GitHub repository.

🔗 [Click here to view this project on GitHub](https://github.com/coopersully/halara-lobby)
