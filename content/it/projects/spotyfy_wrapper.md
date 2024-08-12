---
title: "Spotify Wrapper App"
date: 2024-08-12T00:00:00+00:00
# weight: 1
tags: ["Spotify", "linux", "dart", "flutter", "api", "spotify api"]
author: ["Mark-74", "Lorii0"]
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Un'applicazione per linux creata con flutter in una settimana"
canonicalURL: "https://mark-74.github.io/it/projects"
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
    alt: "Spotify Wrapper App" # alt text
    caption: "Un'applicazione per linux creata con flutter in una settimana" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/Mark-74/Mark-74.github.io/tree/main/content/it/projects"
    Text: "Suggerisci modifiche" # edit text
    appendFilePath: true # to append file path to Edit link
---
# Spotify Wrapper App ▶︎ •၊၊||၊|။|||| |
Applicazione Linux finita in una sola settimana usando flutter e il package spotify.

## Development team 🤖
Questo progetto è stato sviluppato da:

- **Balducci** Marco
- **Shani** Lorenzo

## Github Repository
[qui](https://github.com/Mark-74/spotify_wrapper) puoi trovare il progetto finito. 


## App 🚀
Abbiamo deciso di sfidare noi stessi e creare una applicazione simile a spotify in una settimana.

**Come abbiamo fatto 🤔:** 
- I primi 3 giorni li abbiamo passati a studiare l'api di spotify e come adattarlo ad una applicazione in flutter, inoltre abbiamo fatto le prime scelte considerevoli per il design dell'app.
- Abbiamo poi iniziato a creare tutti i widget necessari, partendo dalla homepage per poi inserire tutti i componenti al suo interno.
- Una volta finita l'homepage e collegati all'api di spotify siamo passati alla parte di logica, a questo punto era il quinto giorno.
- Finita la logica abbiamo aggiunto qualche dettaglio e sistemato alcuni problemi, era l'ultimo giorno.

**Problemi 🚩:**
Il peggior problema riscontrato è sicuramente la durata dell'access token di spotify, infatti scade soltanto un'ora dopo la sua creazione.

**Soluzioni 💡:**
Abbiamo dovuto trovare un modo per usare l'api di spotify per più di un'ora senza aver bisogno di fare nuovamente il login, quindi la migliore soluzione che ci è venuta in mente è quella di fare il login ogni volta che l'app viene aperta e fare subito le richieste che richiedono un access token, mentre per le altre richieste che non ne necessitavano abbiamo usato un'api pubblica, così l'utente avrebbe potuto usare l'app per più di un'ora senza alcun problema.

**Packages usati 📦:**
- [spotify](https://pub.dev/packages/spotify)
- [flutter_dotenv](https://pub.dev/packages/flutter_dotenv)
- [youtube_explode_dart](https://pub.dev/packages/youtube_explode_dart)
<pre>


</pre>
# Conclusions ⚖️
Il progetto è stato un successo ed entrambi abbiamo imparato molto da questa esperienza, anche se non era la prima volta che usavamo flutter.
