---
title: GPS Clock
description: A GPS-disciplined eight-digit clock with alarm, built on a custom PCB from an earlier outreach project, with its firmware rewritten in Rust.
permalink: /portfolio/gps-clock/
thumbnail: /assets/portfolio/gps-clock/cover.jpg
tags:
  - Embedded Rust
  - GPS timing
  - PCB design
  - 3D printing
featured: true
---

<section class="page-header">
  <p class="eyebrow">Design Portfolio</p>
  <h1>GPS Clock</h1>
  <p class="lead">An eight-digit seven-segment clock that takes its time from GPS satellites, built on a custom board that started life as a university outreach project.</p>
</section>

<section class="section-grid">
  <article class="content-block">
    <img class="gallery-image" src="{{ '/assets/portfolio/gps-clock/cover.jpg' | relative_url }}" alt="GPS Clock: a green faceplate with a GPS module, an Arduino Nano, a row of push buttons, and an eight-digit display showing the time down to hundredths of a second">
  </article>
  <article class="content-block">
    <h2>Project focus</h2>
    <p>The GPS Clock is disciplined by the satellites' one-pulse-per-second signal, which marks each second boundary in hardware, and by a GPS time sentence read at power-up and once a minute. Between pulses, a hardware timer fills in the hundredths of a second, so the display reads <code>HH.MM.SS.CC</code>.</p>
    <p>It also has a buzzer alarm, a date view, and a worldwide UTC offset that can be set from the front panel. The firmware is written in Rust for the ATmega328P (Arduino Nano), with a bit-banged software UART for the GPS, a custom MAX7221 display driver, debounced buttons, and a separate module for each feature. The case was designed in FreeCAD for 3D printing.</p>
    <p><a href="https://github.com/jwkunz/gps_clock_purple">GPS clock source code and documentation on GitHub</a></p>
    <h2>What it demonstrates</h2>
    <p>The project shows precision timing from a GPS source, embedded Rust on a small 8-bit microcontroller, and a complete hardware, firmware, and enclosure workflow: board design, driver development, and a printed case that brings it together.</p>
  </article>
</section>

<section class="section-block">
  <div class="section-heading">
    <p class="eyebrow">Origins</p>
    <h2>Built on the BYU 7-Segment Board.</h2>
  </div>
  <div class="gallery-grid">
    <article class="gallery-item">
      <img class="gallery-image" src="{{ '/assets/portfolio/gps-clock/byu-7seg-board.png' | relative_url }}" alt="3D render of the BYU 7-Segment Board printed circuit board">
      <div class="gallery-meta">
        <span class="tag">PCB design</span>
        <span class="tag">Arduino</span>
        <span class="tag">Outreach</span>
      </div>
      <h2><a href="https://github.com/jwkunz/BYU7SegBoard">BYU 7-Segment Board</a></h2>
      <p>The GPS Clock is a sequel to an educational outreach project for Brigham Young University's Smart Antenna Systems Group. That project was a custom Altium-designed board combining an Arduino Nano, a MAX7221 driving eight seven-segment digits, six buttons, a switch, and a buzzer, with firmware for a tuned free-running alarm clock.</p>
      <p>The same board came back with a GPS module on its spare header pins, replacing a tuned timer with satellite timing, and with the firmware rewritten in Rust.</p>
      <p><a href="https://github.com/jwkunz/BYU7SegBoard">View the original board and firmware on GitHub</a></p>
    </article>
  </div>
</section>
