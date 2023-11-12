---
title: "Java Game Engine Project 1: Configurable Pacman"
excerpt: "A version of the retro game Pacman made to be configurable.<br/><img src='/images/Pacman.png'>"
collection: portfolio
---

Java Game Engine
------
Java Game Engine has been my personal project with the Husky Coding Project (HCP) since Summer of 2022 with our initial kickoff in January 2023. Pacman was the very first game we developed to learn game development and at the HCP 2023 Project Showcase, we demonstrated our configurable version of Pacman.

Java Game Engine's original goal was to construct a lightweight low or no code engine to address the steep learning curve of introductory game development. Specifically our target audience is individuals aiming to get into game development, but they have little to no programming experience.

Pacman
------
Since our team did not have any game development knowledge or GUI knowledge prior to working on the project we chose to develop Pacman first given the games simplistic implementation. In all actuality however, it was not. We met a significant amount of problems along the way given our lack of experience in game development and JavaFX which ended up cutting hard into our development progress. However, after a few meetings and literature review, we ended up getting back on track. Initially we had a verbose back end composing of up to 3000 lines of code ready to go. But since our front-end was not able to mesh well with it we had to refactor it almost completely. We ended up completing our simplified implementation of Pacman over the Summer quarter (June - August), and soon after that we finished the configuration and map writing menus in the month of September.

The Game
------
Our application consists of two stages. The configuration stage, where users can select or change attributes of the game's characters or map tiles, and the playing stage, where users can interact with their configured Pacman implementation.

Where To Play?
------
Our game can be downloaded from Github via this [repository](https://github.com/hcp-uw/java-game-engine-pacman), there is not an executable version at the current moment, however using intellij you can import the project then run with Maven via the Mapwriter Main class's main method 