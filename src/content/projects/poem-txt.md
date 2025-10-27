---
title: poem.txt
description: This is tool lets you create playfull poems with your phone by using the computer as a canvas. The project is inspirated by the visual poetry Paul van Ostaijen.
preview: /public/images/projects/poem-txt/poem-txt-1.png
pics:
    - /public/images/projects/la-cuisine-du-sang/la-cuisine-du-sang-2.png
    - /public/images/projects/la-cuisine-du-sang/la-cuisine-du-sang-1.png
links:
    -   name: view project on GitHub
        link: https://github.com/Jana-Elst/poem.txt.git
        
year: 2025
partners:
    - Devine I Creative Code 4
services:
    - Concept Development
    - Web Development
tools:
    - Javascript
    - GSAP
    - WebRTC

device:
    - desktop & smartphone
role: individual student work
tags:
    - Web Development
    - Creative Development
featured: false
draft: true
permalink: projects/poem-txt/
---
What if you could create a playful, visual poem by literally shooting words from your phone onto your computer screen? This project brings that idea to life. You simply type a word, style it, and 'shoot' it from your device. The harder you flick your phone, the bigger the word appears on the canvas. Once your masterpiece is ready, you can save the final poem directly to your phone's photo gallery.

## Technical Implementation
The core technical challenge was creating a seamless, real-time communication channel between the phone and the computer. To solve this, I used the WebRTC API, which enables direct peer-to-peer communication between browsers with extremely low latency, perfect for an interactive experience