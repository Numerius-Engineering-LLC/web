---
title: Speed Trap
description: A handheld two-beam optical speed trap with a 3D-printed gate and an ESP32 running no_std Rust firmware that times a pass and reports speed on an LCD.
permalink: /portfolio/speed-trap/
thumbnail: /assets/portfolio/speed-trap/cover.jpg
tags:
  - Embedded Rust
  - ESP32
  - 3D printing
  - Instrumentation
featured: true
---

<section class="page-header">
  <p class="eyebrow">Design Portfolio</p>
  <h1>Speed Trap</h1>
  <p class="lead">A compact optical speed trap that times an object passing between two light beams and shows its speed on an ESP32 board's built-in display.</p>
</section>

<section class="section-grid">
  <article class="content-block">
    <img class="gallery-image" src="{{ '/assets/portfolio/speed-trap/cover.jpg' | relative_url }}" alt="Speed Trap: a 3D-printed two-beam gate on a bracket, wired to an ESP32 board showing readings on its display">
  </article>
  <article class="content-block">
    <h2>Project focus</h2>
    <p>A 3D-printed gate holds two parallel beams 8 mm apart, each aimed at a phototransistor. Firmware written in <code>no_std</code> Rust timestamps the moment an object breaks each beam, divides the beam spacing by the elapsed time, and displays the result.</p>
    <p>The screen keeps the last three readings along with their mean and span, so repeatability is visible at a glance. Passing an object through in the reverse direction cycles the units between m/s, km/h, ft/s, and mph.</p>
    <p><a href="https://github.com/jwkunz/chronometer_esp32_rust">View the source and build notes on GitHub</a></p>
    <h2>What it demonstrates</h2>
    <p>This project spans the full chain from a physical instrument to its firmware: a printed enclosure and sensor gate, a polling state machine for microsecond timing, a custom ST7789 display driver with a software SPI master and scalable bitmap font, and a compact interface designed for use without a computer.</p>
  </article>
</section>
