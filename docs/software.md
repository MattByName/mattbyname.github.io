---
title: Software
layout: default
sort_order: 2
show-nav: true
---
Here is a little bit about each of the free software projects I maintain. 

## Color Overlays for Linux
As a sufferer of [visual stress](http://www.learningwithdyslexia.co.uk/visual-stress-and-dyslexia/) related to dyspraxia and dyslexia, I find tinted glasses and colour overlays extremely helpful for reading. Software overlays, which tint the whole desktop with a colour, are also helpful, and mean I don't have to wear my very dark and expensive [Irlen](https://irlen.com) lenses, which I can't always afford to renew with my prescription anyway. 

On Windows, I use [WindowShades](https://www.softpedia.com/get/Desktop-Enhancements/Other-Desktop-Enhancements/WindowShades.shtml). On Mac, I used a similar app that I can't remember the name of. When I started using Linux, however, there was only one option, [Gnome Tint](https://github.com/apenugon/gnome-tint), a GNOME Shell extension. Luckily, I was using GNOME at the time. However, when the project fell out of maintenance without a FOSS licence, I set to re-implementing it as [ColorTint](https://github.com/MattByName/color-tint) in early 2019.

I'm now also working on a new implementation for KDE Plasma, [KolorTint](https://github.com/MattByName/kolor-tint), as I've recently switched to that for my sins. As my desktop development skills increase, I will try to make a desktop-environment-independent solution, as I want this feature to be as widely available as possible, aiming towards a more accessible GNU/Linux. 

### ColorTint
<a href="https://github.com/mattbyname/color-tint">GitHub</a>
 | 
<a href="https://extensions.gnome.org/extension/1789/colortint/">GNOME Extensions Site</a>

ColorTint is a Gnome extension that draws a translucent coloured overlay over your desktop. This is to help people with dyslexia, visual stress, scopic sensitivity, and related conditions. ColorTint was forked as [AlphaTint](https://github.com/saifulbkhan/alpha-tint) for users who only wanted the ability to dim their displays.
### KolorTint

<a href="https://github.com/mattbyname/kolor-tint">GitHub</a>

KolorTint is a KDE widget that draws a translucent coloured overlay over your desktop. This is to help people with dyslexia, scopic sensitivity, and related conditions. It is the companion to [ColorTint](https://github.com/MattByName/color-tint), a GNOME extension with the same function.

## Pico RSS Maker
<a href="https://github.com/mattbyname/Pico-RssMaker">GitHub</a>

[Pico CMS](https://picocms.org) is a flat-file CMS based on twig and markdown. It's great and I'd be using it now instead of [Jekyll](https://jekyllrb.com) if it didn't require PHP. [Pico RSS Maker](https://github.com/MattByName/Pico-RssMaker) is a plugin I wrote so that I could have an RSS feed for a news blog for a client, mainly so I could tie it into Zapier routines. I no longer use Pico, but current users have improved the extension, in the FOSS way. 



