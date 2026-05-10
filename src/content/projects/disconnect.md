---
title: "[dis]connect"
description: A spatial installation dispersed across two rooms that creates serendipitous conversations between strangers using vintage rotary phones. The project explores how obsolete technologies can break the "smartphone bubble" and facilitate meaningful micro-interactions.
preview: /public/images/projects/dis-connect/dis-connect-1.png
pics:
    - /public/images/projects/dis-connect/dis-connect-1.png
video:
    src: https://player.vimeo.com/video/1163033255?loop=1&autopause=0
links:
    -   name: Read my full process & research
        link: https://www.janaelst.be/passionProject/
    -   name: Watch the video
        link: https://vimeo.com/1163033255?share=copy&fl=sv&fe=ci
    -   name: Final presentation 
        link: https://www.figma.com/deck/XeDYmtkyNNSEPznhQHZP54
        
year: 2026
month: 1
partners:
    - Devine I Passion Project
services:
    - Concept Development
    - Creative Coding
    - Installation Design
    - Physical Computing
tools:
    - Arduino
    - Raspberry Pi
    - Telephony APIs
    - Physical Design

device: []
role: Creative coder & Designer
tags:
    - Creative Coding
    - Concept Development
featured: true
draft: false
permalink: /disconnect/
---

## The Research Question

**How might we use obsolete technologies to break the smartphone bubble and facilitate meaningful micro-interactions between strangers?**

This was my five-week passion project—my final school project where I could explore something I genuinely cared about. The question came from a very personal place.

## The Problem: The Smartphone Bubble

I started Devine with a Nokia 3310. It sounds crazy, but I loved it. Without Google Maps, I actually had to talk to strangers to find my way around. I had tiny, wonderful interactions every day—real human moments.

Now, I'm graduating with an iPhone 16 in my pocket. And while it was supposed to "improve" my life, something feels lost.

We're more "connected" than ever, but way more lonely. We're collectively addicted to anti-social media. We've stopped talking. And I realized: humans aren't built for endless scrolling—we're built for small, real interactions. We even have a hormone called oxytocin, basically an "emotional high-five" your brain releases during these micro-interactions.

## The Concept

**[dis]connect** is an installation spanning two separate rooms. In each room, a vintage rotary phone sits waiting.

Here's how it works: The first visitor picks up the phone and uses the rotary dial to choose from a set of conversation themes or opening questions. Once they've selected their theme, a second phone in the adjacent room starts ringing. When the next visitor picks it up, a warm voice-over greets them both, introduces the chosen theme, and then they can have a genuine conversation.

If no one picks up that second phone, the first visitor can leave a voicemail—a message for whoever might call later. This design prevents awkward silences and gives both callers something to respond to, breaking the ice and setting the tone for real conversation.

When they hang up, the connection ends, and they never know who they spoke to. The anonymity creates space for unexpected honesty and connection.

## Why Obsolete Tech?

I've always collected "obsolete" objects—record players, typewriters, vintage bikes, mechanical calculators. There's something beautiful and robust about them. A rotary phone forces you to slow down. You can't multitask while on it. You can't scroll. You have to be *present*.

By using this ancient technology, I'm deliberately rejecting the smartphone's design for distraction and isolation.

## Technical Implementation

The installation is built on a **Raspberry Pi and Arduino**, programmed in Python and C++. Two authentic vintage fixed phones are connected via a custom-built network that preserves the analog experience.

The system handles:
- Detecting when a handset is picked up (Arduino)
- Managing the rotary dial input to select conversation themes
- Routing the phone connection between the two rooms
- Playing the voice-over introduction
- Recording voicemail if the second visitor doesn't pick up

The focus is on keeping the technical setup invisible—visitors experience vintage phones and voice, not screens or digital complexity.

## The Bigger Picture

I don't want to fix the whole world, but I'd love to make a small difference in someone's day. This installation is my attempt to create a moment where strangers become briefly connected—not through screens, but through voice, vulnerability, and chance.

The project was selected for **div.fuse**, an exhibition celebrating this kind of experimental, conceptually-driven work.