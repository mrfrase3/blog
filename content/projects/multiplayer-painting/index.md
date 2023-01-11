---
title: "[old] Multiplayer Painting"
date: 2018-06-10T00:18:58+08:00
draft: false
aliases: ["/project/multiplayer-painting/"]
tags: ["WebVR", "Networking", "SIGGRAPH Asia"]
summary: "A socket based multiplayer server example for a-painter, a WebVR painting application."
hiddenInHomeList: true

cover:
    image: "a-painter.png" # image path/url
    alt: "" # alt text
    caption: "" # display caption under cover
    relative: true # when using page bundles set this to true
    hidden: false # only hide on current single page

---

This server uses a-painter's main repo, except instead of using a cli webpack server, it hosts its own express server with webpack implemented and then runs a socket.io server on top. It also injects the multiplayer layer into the client application.

This serves as a basic example and the method can easily be modified to support different communication types, like mongo, firebase, webRTC, etc...

[The project code can be found here](https://github.com/mrfrase3/a-painter-socket-server)
