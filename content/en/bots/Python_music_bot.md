---
title: "Youtube music bot - Python"
date: 2024-08-14T00:00:00+00:00
# weight: 1
tags: ["Youtube", "Discord", "python", "music", "api", "bot", "discord bot", "yt_dlp"]
author: ["Mark-74"]
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Python music bot which uses yt_dlp's API"
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
    alt: "Python music bot" # alt text
    caption: "Python music bot which uses yt_dlp's API" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/Mark-74/Mark-74.github.io/tree/main/content/en/bots"
    Text: "Suggest changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
# Youtube music bot - Python ♫

## Developer 🤖
the bot was developed by:

- **Balducci** Marco

## Github Repository </>
[here](https://github.com/Mark-74/Python_discord_youtube_bot) you can find the finished project. 

## Features ✨
- Multi-Server

the bot can play music in multiple servers at the same time.
- Button interface

buttons are present to manage the current song.
- Downloaded files cleaning

there is a cleaning queue for the downloaded files that keeps saved only 2 files per server at any moment.
- Youtube research

thanks to yt_dlp's api it's possible to research for songs directly from youtube.

## API 🔗
The bot depends on yt_dlp's api for researching songs and downloading them.

## Class management 📜
- MusicInstance

manages every instance of the bot in each servers in which it's added, it contains the logic responsible for the music playing and for the queue management, furthermore it uses the next class to clean the downloaded files.
- YoutubeDL

not a class, but but a group of useful functions to manage the downloaded files.