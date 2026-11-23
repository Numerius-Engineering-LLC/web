---
title: Spritely Bullfrog
description: A four-person wired buzzer game with a custom board, 3D-printed enclosures, and Arduino firmware, designed to teach teenagers soldering, 3D printing, and C++. Full build instructions are on Instructables.
permalink: /portfolio/spritely-bullfrog/
thumbnail: /assets/portfolio/spritely-bullfrog/cover.jpg
external_url: https://www.instructables.com/4-Person-Wired-Buzzer-Game-From-Scratch/
external_label: Build it yourself on Instructables
tags:
  - Electronics
  - 3D printing
  - PCB design
  - Education
featured: true
---

<section class="page-header">
  <p class="eyebrow">Hardware Projects</p>
  <h1>Spritely Bullfrog</h1>
  <p class="lead">A four-person wired buzzer game, built from scratch with a custom circuit board, 3D-printed enclosures, and Arduino firmware, and designed to teach teenagers how to solder, 3D print, and program in C++.</p>
</section>

<section class="section-grid">
  <article class="content-block">
    <img class="gallery-image" src="{{ '/assets/portfolio/spritely-bullfrog/cover.jpg' | relative_url }}" alt="The Spritely Bullfrog buzzer game: a motherboard in a printed case connected by phone cables to four colored handles, each with a large red button and two LEDs">
  </article>
  <article class="content-block">
    <h2>Project focus</h2>
    <p>A motherboard connects to four player handles over RJ12 phone cables. Each handle has a large button and two LEDs. After a question is asked, the motherboard button opens the round, and the first player to press and hold a handle button wins it, signalled by a light and a sound. If two players press at the same moment, the motherboard picks the winner with a random tiebreaker. A slide switch mutes the sound, and the game opens with a startup song.</p>
    <p>The whole system was designed as a teaching project. The circuit board layout was done in KiCad, the motherboard case and the handles were designed in FreeCAD for 3D printing, and the firmware is an Arduino project built on FreeRTOS, with short diagnostic sketches that make good first exercises in buttons and LEDs.</p>
    <p><a href="https://www.instructables.com/4-Person-Wired-Buzzer-Game-From-Scratch/">Build it yourself: step-by-step directions on Instructables</a><br><a href="https://github.com/jwkunz/Spritely_Bullfrog">Design files and source code on GitHub</a></p>
    <h2>What it demonstrates</h2>
    <p>This project covers a complete hardware product: schematic and board design, enclosure design, firmware, and clear documentation that lets others build it. It also shows an ability to make electronics approachable for beginners.</p>
  </article>
</section>
