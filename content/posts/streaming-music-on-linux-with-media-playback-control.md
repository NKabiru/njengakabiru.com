+++
title = "How I stream music on Linux" 
date = 2020-07-10T05:00:00Z
author = ""
subtitle = "GNU/Linux alternatives for music streaming apps"
lastmod = 2020-07-10T05:00:00Z
tags= ["linux", "music", "apps"]
+++
Unfortunately, most music streaming services do not provide a native app on Linux. Though it's possible
to use the browser versions, you still miss out on native features such as keyboard media playback control.
(Useful for quick muting, skipping songs you don't like or keeping your favourite song on repeat without having to switch windows). 
Here are some of the solutions that have worked for me so far:

## [Deezer (AUR)](http://aur.archlinux.org/packages/deezer) 
This package works just like the Windows version. You can even upload your personal music through it. Keep in mind
that it's an Electron app, so its a bit large and eats up RAM.

## [MellowPlayer](https://colinduquesnoy.gitlab.io/MellowPlayer/)
This app acts as a wrapper around your cloud streaming services, providing you with media playback controls. Think of
it as a one-stop shop for most of your services (Youtube included). I personally had some issues with songs not playing in
background, but YMMV.

## [Nuvola Apps Runtime](https://nuvola.tiliado.eu/)
This is a runtime that provides a richer desktop integration for streaming web apps. They support a wide selection of 
streaming services. Keep in mind that it's a freemium product - after a 31 day trial you have to pay to access the premium features (MPRIS2 is one of them).

