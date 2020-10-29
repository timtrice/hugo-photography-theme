---
title: "Introducing NINA: An astrophotography sequencing suite"
date: 2020-10-24T10:00:49-05:00
draft: true
layout: article
tags: ["N.I.N.A."]
summary: >
  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed tincidunt erat lorem, vestibulum scelerisque mauris rhoncus vitae. Donec elementum fermentum tortor at suscipit.
image: 
  src: nina.png
  caption:  "Nighttime Imaging 'N' Astronomy"
---

 have been involved in a new opensource project over the past several months called Nighttime Imaging ‘N’ Astronomy (“NINA”). NINA is ground-breaking both in the hobby of amateur astrophotography and personally. An artifact of several historical reasons, the world of computer-controlled astrophotography is dominated by Windows applications. As such, astrophotography apps tend to follow a closed-source, shareware or freemium/commercial-only model. The idea of well-featured apps being opensource or freeware is a relatively recent development in this niche world, as the list of such apps is abysmally small relative to the large variety of payware apps that are available. NINA stands out in this regard in that it is fully-featured, opensource (GNU GPLv3) and, hence, freely available.

On a personal note, this was my very first introduction to programming on Windows and GUI apps in general. Learning Visual Studio, C#, WPF, and the particulars of Windows programming environments was fun and easier than I had expected. My personal interest on this project is implementing and touching-up direct (“native”) camera control integration and UI tweaks where needed.

### Core Concept

NINA’s core concept is straight-forward. In the basic sense, NINA is a program where one sets up a session that contains sequences of hardware control actions and exposures. It operates a to-do list done in sequential order: Point the telescope to this part of the sky. Select the luminance filter in the filter wheel. Perform a focus routine. Take N exposures at X gain (or ISO) and Y shutter speed. Tell the filter wheel to rotate to the red filter and take another N exposures, perform a dither… and so-on.

The idea with such a sequencing app is to compose an astrophotography session and have the app drive it from start to finish. This means one may press “Start” on the sequence and go do other things: watch TV, enjoy visual astronomy through another telescope, or even just go to bed knowing that the application will take care of all the hardware manipulation and data collection and collation itself.

NINA is designed to be accommodating to the new astrophotographer as well as seasoned ones. Full observatory automation is not on the roadmap right now as the team wants to focus on developing the basics first. For the vast majority of amateur astrophotographers, however, NINA’s feature set is both powerful and, most importantly, accessible.

It is worth noting what NINA is not. NINA is not an image processing application. The sole purpose of NINA is to operate your astrophotography gear, get you the exposures you desire, and organize that collected data so that you can then import it into image processing software of your choice (such as PixInsight). Image processing is a world unto itself with a plethora of options, methods, and of course opinions.

