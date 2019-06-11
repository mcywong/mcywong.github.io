---
layout: post
title: Project Start!
subtitle: Background and Problem Statement
image: /img/dfoLogoCropped.jpg
gh-repo: mcywong/DFO-Tools-site
tags: [Hell Logger, Engineering Design Process]
---


### Background
This project is designed to be a convenient tool for players of the MMORPG by Neople&copy; [Dungeon Fighter Online](https://www.dfoneople.com/) or DFO for short.
As with most RPG style games, players fight in dungeons to level up and get stronger equipment.
One type of dungeon in DFO is called Hell mode where the strongest tier of equipment called Epics can be found at a low drop rate.
Players will complete many runs of Hell mode hoping to get lucky and find one of their desired Epic gear.

I saw some guild members using Excel Spreadsheets to log their hell runs and how many lucky drops they got.
I found this method to be simple to understand but tedious to manage.
To calculate an accurate drop rate, data from multiple players should be collected together. 
However that is not easy with spreadsheets from different people with different formats.

### Problem Statement
Logging Hell runs using spreadsheets is tedious and difficult to compile data from multiple sources.

#### Potential Solutions:
1. Desktop app that hooks to the game client to log runs
2. A webapp that parses spreadsheets to compile data
3. A website with a visual UI that makes logging simpler

Solution 1 is difficult because there is no publicly avaliable APIs for the game and risky because it has to avoid triggering anti-cheat software. 
Solution 2 would solve collecting data from multiple sources and allows each player to log how they have been
Solution 3 would need be designed well for users to actively want to log runs on the website instead of their current methods

Overall solution 3 makes it easy to collect data since runs will be directly logged into a singular database. 
Now I want to build a website users can access to collect Hell run data and display statistics.
