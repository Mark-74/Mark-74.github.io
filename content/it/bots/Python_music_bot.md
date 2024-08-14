---
title: "Youtube music bot - Python"
date: 2024-08-14T00:00:00+00:00
# weight: 1
tags: ["Youtube", "Discord", "python", "music", "api", "bot", "discord bot"]
author: ["Mark-74"]
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Bot della musica in python che usa le api di youtube e yt_dlp"
canonicalURL: "https://mark-74.github.io/it/bots"
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
    caption: "Bot della musica in python che usa le api di youtube e yt_dlp" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/Mark-74/Mark-74.github.io/tree/main/content/it/bots"
    Text: "suggerisci modifiche" # edit text
    appendFilePath: true # to append file path to Edit link
---
# Youtube music bot - Python ♫

## Developer 🤖
Il bot è stato sviluppato da:

- **Balducci** Marco

## Github Repository
[qui](https://github.com/Mark-74/Python_discord_youtube_bot) puoi trovare il progetto finito. 

## Features ✨
- Multi-Server
può riprodurre musica su più server contemporaneamente.
- Interfaccia a bottoni
sono presenti bottoni per la gestione della canzone corrente.
- Pulizia dei file scaricati
è stata implementata una coda di pulizia per i file scaricati che ne mantiene solo 2 per server in ogni momento.
- Ricerca su Youtube
grazie all'api di youtube è possibile ricercare direttamente da youtube

## API 🔗
Il bot dipende dalle api di youtube per la ricerca delle canzoni e da quello di yt_dlp per scaricarle.

## Gestione classi 📜
- MusicInstance
gestisce l'istanza del bot per ogni server discord in cui viene aggiunto e usato, al suo interno troviamo la logica per la riproduzione delle canzoni e per la gestione della queue, inoltre si interfaccia alla classe successiva per la pulizia dei file.
- YoutubeDL
non è una classe, ma un'insieme di funzioni utili per la gestione dei file scaricati.