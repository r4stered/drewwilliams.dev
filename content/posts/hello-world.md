---
title: "Hello World"
date: 2019-07-26T01:00:09-04:00
# weight: 1
# aliases: ["/first"]
tags: ["hello", "world", "blog"]
author: "Me"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Desc Text."
canonicalURL: "https://drewwilliams.dev/"
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
editPost:
    URL: "https://github.com/r4stered/drewwilliams.dev/content"
    Text: "Suggest Changes" # edit text
    appendFilePath: true # to append file path to Edit link
---

Welcome to my personal website! I just wanted to quickly run through the specs of the site:

- Namesilo for domain name
- Digital Ocean for hosting. I went with 3GB RAM, 1 CPU, and a 60 GB SSD. (I will explain why later).
- HUGO static site generator

I wanted to build a personal website while learning how the internals of setting up a website actually worked. So I decided to go the more manual route instead of squarespace or wordpress or anything like that, but I also wanted to quickly create content and not have to worry about coding HTML and CSS. So thats why I went with a static site generator. I went with HUGO mostly because it was the first thing that came up when I searched for a site generator.

This is all hosted on Digital Ocean, and because of the extremely low resources to run the site, I am also running a Minecraft server on the same droplet for my friends and I. It seems to be working really well so far!

I have the git repos on the VM to automatically run the HUGO when i push to the repo so it is pretty seamless.

Thanks for reading!

Drew