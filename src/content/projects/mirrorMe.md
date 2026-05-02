---
title: mirrorMe
description: A fully functional React Native app that transforms digital communication into a physical, embodied experience. When you unlock a message, you're not just reading text—you're replicating the sender's movement, stepping into their gesture, and understanding how they sent it.
preview: /public/images/projects/mirrorMe/mirrorMe-1.png
pics:
    - /public/images/projects/mirrorMe/mirrorMe-2.png
links:
    -   name: view project on GitHub
        link: https://github.com/Jana-Elst/mirrorMe.git
        
year: 2025
partners:
    - Devine I Expert Creative Development
services:
    - App Development
    - Concept Development
tools:
    - React Native
    - Supabase
    - Device Sensors (accelerometer, compass, gyroscope)

device:
    - mobile
role: individual student work
tags:
    - App Development
    - Concept Development
    - Machine Learning
featured: true
draft: false
permalink: /mirrorme/
---

## The Assignment

The challenge was to learn React Native by building a fully functional application. Rather than create a standard UI exercise, I wanted to explore something conceptually interesting—how technology could facilitate more meaningful human connection.

## Concept

Most messaging apps are purely digital—text on a screen. But what if you could add a physical layer? What if understanding a message meant experiencing how the sender moved?

**mirrorMe** embeds the sender's movement into every message. When someone sends you a message, they're not just typing words—they're encoding their physical gesture, the way they tilted and moved their phone. 

To read that message, you have to **move your phone the same way**. You're literally stepping into their shoes, replicating their gesture, experiencing the intention behind the message. It's intimate. It's playful. It makes something purely digital actually *physical*.

The message stays hidden—distorted, off-screen, unreadable—until your phone's movement matches theirs. Only then does it snap into place, fully legible. At that moment, you've literally embodied the sender's gesture. You understand not just *what* they said, but *how* they said it.

## How It Works

1. **Send** - You write a message and as you do, your phone's sensors capture your movement—how you tilted it, rotated it, held it
2. **Receive** - The message arrives, but it's distorted, off-screen, unreadable
3. **Move** - To understand what they sent, you move your phone—tilting, rotating, positioning it in space
4. **Understand** - When your movement matches theirs, the message snaps into place. You've just embodied their gesture. You understand their intention.

## Technical Implementation

When you send a message, mirrorMe captures real-time sensor data from your phone—accelerometer (motion), gyroscope (rotation), compass (direction). This "movement fingerprint" is encoded into the message.

When the receiver gets it, their device reads sensor data as they move their phone. The app compares their live sensor readings to the sender's captured movement. When the patterns match—when they've tilted, rotated, and positioned their phone the same way—the message unlocks.

**Supabase** stores the messages and movement data securely, creating a persistent link between sender and receiver through their shared gesture.

## Why This Matters

Most digital communication strips away the physical. You type a message and it appears on someone's screen—no trace of *how* you sent it, your mood, your gesture, your presence.

**mirrorMe** brings that back. It adds layers. It makes the receiver work a little—not as friction, but as *understanding*. When you move your phone to unlock a message, you're not just reading words. You're experiencing the sender's intention. You're in their body for a moment.

This was my first React Native app, and I wanted the technical challenge to serve the concept. Building a fully functional app meant solving real problems: capturing sensor data reliably, matching movement patterns, storing everything securely. The engineering had to be invisible—what matters is the experience of stepping into someone else's gesture.