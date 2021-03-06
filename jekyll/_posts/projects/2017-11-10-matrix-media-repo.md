---
layout: project
title: matrix-media-repo
categories: projects other
description: A replacement media repository for your homeserver
author: Travis Ralston
maturity: Late Beta
language: Go
license: MIT
repo: https://github.com/turt2live/matrix-media-repo
---

# {{ page.title }}
Intended for multi-homeserver environments (ie: homeserver hosting providers), matrix-media-repo deduplicates media from all servers, saving disk space when someone uploads the same cat picture to every room they can find. Multiple homeservers are handled by telling the media repo that it is the authority for media for a list of domains.

People running single homeservers can still reap the benefits of matrix-media-repo thanks to it's deduplication approach. It deduplicates local media as well as any remote media that happens to get downloaded, saving you even more disk space if you happen to re-upload a file you downloaded from another homeserver.

The source, and more information, can be found on [GitHub](https://github.com/turt2live/matrix-media-repo).

Repository: <{{page.repo}}>
