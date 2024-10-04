---
title: "Clip Editor bot"
date: 2024-10-4T00:00:00+00:00
# weight: 1
tags: ["Discord", "python", "music", "api", "bot", "discord bot", "assemblyai", "TikTok", "Reels", "Shorts", "editor", "simple"]
author: ["Mark-74, AlBovo"]
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Python discord bot that creates engaging videos in smartphone format 9:16"
canonicalURL: "https://mark-74.github.io/en/bots"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "" # TODO: add image path/url
    alt: "Clip Editor bot" # alt text
    caption: "Python discord bot that creates engaging videos in smartphone format 9:16" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/Mark-74/Mark-74.github.io/tree/main/content/en/bots"
    Text: "Suggest changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
# Clip Editor Bot 🎥

## Developers 🤖
the bot was developed by:

- **Balducci** Marco
- **Bovo** Alan Davide

## Github Repository </>
[here](https://github.com/Mark-74/Editing-Bot.git) you can find the finished project. 

## Features ✨
- Multi-Server

The bot can handle multiple requests at the same time and therefore be used in multiple servers at once.
- Video editor

The bot edits the video sent by the user using the resources which already has (for more information read the README of the project in the repo).
- Video size optimization

The bot uses FFmpeg to reduce video size.
- Results directly to the users

The edited videos are sent to the users who requested them via Discord direct messages.
- Docker-Ready

The docker files are complete and the bot is ready to be deployed.


## API and libraries 🔗
The bot depends on AssemblyAi's api for subtitles.

``` requirements.txt
discord>=2.3.2
python-dotenv>=1.0.1
moviepy>=1.0.3
assemblyai>=0.26.0
pysrt>=1.1.2
imageio>=2.34.1
nest-asyncio>=1.6.0
```