---
title: poem.txt
description: An interactive installation where visitors shoot words from their smartphone onto a large screen to create visual poems. Words can be styled with different typefaces, boldness, italics, and rotation—but no color, honoring Paul van Ostaijen's approach to visual poetry.
preview: /public/images/projects/poem-txt/poem-txt-1.png
pics:
    - /public/images/projects/poem-txt/poem-txt-1.png
links:
    -   name: view project on GitHub
        link: https://github.com/Jana-Elst/poem.txt.git
        
year: 2025
partners:
    - Devine I Creative Code 4
services:
    - Concept Development
    - Installation Design
    - Web Development
tools:
    - Javascript
    - GSAP
    - WebRTC
    - Canvas API

device:
    - desktop & smartphone
role: individual student work
tags:
    - Web Development
    - Creative Coding
    - Installation Art
featured: true
draft: false
permalink: /poem-txt/
---

## The Assignment

For Creative Code 4, I had to build a mobile + screen interaction. Rather than create something purely functional, I wanted to layer in something meaningful—connecting playfulness with art and exploring how digital tools can become creative instruments.

## Concept

What if you could shoot words from your phone onto a screen and create visual poetry in the process? **poem.txt** is an interactive installation that brings this idea to life.

Visitors type a word on their smartphone and style it—choosing typeface, weight (boldness), italics, and rotation angle. Then they "shoot" it onto the large screen by flicking their device. The harder you flick, the larger the word appears and the faster it travels. The final poem is a composition of layered text—a visual poem that shifts with each contribution.

Currently, visitors can save their creation as an image. I'm working on a new version that will allow them to plot their poem directly onto a postcard—bringing the digital creation back into the physical world.

## Design Philosophy

Notably, there's **no color**. This constraint is intentional, honoring Paul van Ostaijen's approach to visual poetry, where meaning comes from placement, scale, and typography—not color. There's also no animation on individual words. The movement comes from the gesture of shooting, not from the words themselves moving after they land.

This restraint forces visitors to think more carefully about composition, spacing, and how words interact spatially.

## Inspiration: Paul van Ostaijen

The project is rooted in **Paul van Ostaijen's visual poetry**, where the placement and typography of words on the page become integral to the meaning. Rather than just reading the words, you *see* the poem. By translating this into an interactive, three-dimensional space, the installation invites visitors to become poets themselves—exploring how language, movement, and space create meaning together.

## Technical Implementation

The core challenge was enabling real-time communication between mobile devices and the installation screen with minimal latency. I used **WebRTC** for direct peer-to-peer communication between browsers, creating an immediate, responsive experience where every gesture feels connected.