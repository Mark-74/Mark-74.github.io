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
description: "A spotify linux application made with flutter in one week."
canonicalURL: "https://mark-74.github.io/en/projects"
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
    caption: "A spotify linux application made with flutter in one week." # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
editPost:
    URL: "https://github.com/Mark-74/Mark-74.github.io/tree/main/content/en/projects"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---
# Spotify Wrapper App ▶︎ •၊၊||၊|။|||| |
Linux application made as a one week project using flutter and the spotify package.

## Development team 🤖
This project has been developed by:

- **Balducci** Marco
- **Shani** Lorenzo

## Github Repository
[here](https://github.com/Mark-74/spotify_wrapper) you can find the finished project. 


## App 🚀
We decided to challenge ourselves to make a spotify app in just one week.

**How did we do it 🤔:** 
- The first 3 days were mostly used for studying the spotify api and how to use it for a flutter app, also we started making the first design choices.
- We then started making all the widgets we needed, starting from the homepage to insert all the features inside.
- Once we finished the homepage and were also able to connect to the spotify api we switched to making the logic part, it was the fifth day already.
- After finishing the logic we added some details and fixed some issues, it was the last day.

**Problems 🚩:**
The worst problem we encountered was the spotify Access Token duration, it lasts only an hour after it is created.

**Solutions 💡:**
We had to think of a way to be able to use the spotify api for longer than an hour without the need to login again, so the best solution that came to our minds was to access it every time you open the app, but the requests that needed the access token login to work were made as soon as possible, and we used the public api for the requests which didn't need an access token, so the user would be able to use the app for more than an hour without any problem.

**Used Packages 📦:**
- [spotify](https://pub.dev/packages/spotify)
- [flutter_dotenv](https://pub.dev/packages/flutter_dotenv)
- [youtube_explode_dart](https://pub.dev/packages/youtube_explode_dart)
<pre>


</pre>
# Conclusions ⚖️
The project was a success and both of us learned a lot from this experience, even though we already knew flutter.
