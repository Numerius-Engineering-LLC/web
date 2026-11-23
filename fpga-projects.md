---
title: FPGA Projects
description: FPGA and SoC design work by Numerius Engineering LLC, including tooling for AMD FPGA SoCs and video-processing designs, with links to each GitHub repository.
---

<section class="page-header">
  <p class="eyebrow">FPGA Projects</p>
  <h1>FPGA projects.</h1>
  <p class="lead">Designs and tooling for FPGAs and FPGA SoCs, from hardware description and high-level synthesis to the software that controls them. Each entry links to its GitHub repository.</p>
</section>

<section class="section-block">
  <div class="section-heading">
    <p class="eyebrow">AMD Zynq</p>
    <h2>Hardware designs and the software stacks that drive them.</h2>
  </div>
  <div class="gallery-grid">
    <article class="gallery-item">
      <div class="gallery-meta">
        <span class="tag">Verilog</span>
        <span class="tag">HLS C++</span>
        <span class="tag">PYNQ-Z2</span>
      </div>
      <h2><a href="https://github.com/jwkunz/vidcap_pynqz2">vidcap_pynqz2</a></h2>
      <p>HDMI video capture, live filtering, and display for the PYNQ-Z2 (Zynq-7020), controlled from Jupyter. The pipeline captures a frame into DDR and applies switchable filters (grayscale, threshold, Sobel edges, blur, sharpen, and retro grain), 3D look-up-table color grading with support for <code>.cube</code> files, and temporal averaging. A hardware clock draws a timestamp, and a test pattern keeps the display live without an input. It is built from hand-written RTL, Vitis HLS cores, and a Python driver, with one bitstream per video mode from 240p to 1080p30. The repository also includes a textbook-style technical guide to video hardware.</p>
      <p><a href="https://github.com/jwkunz/vidcap_pynqz2">View on GitHub</a></p>
    </article>
    <article class="gallery-item">
      <div class="gallery-meta">
        <span class="tag">Rust</span>
        <span class="tag">FPGA</span>
        <span class="tag">SoC</span>
      </div>
      <h2><a href="https://github.com/jwkunz/Hardroxide">Hardroxide</a></h2>
      <p>A Rust HAL generator for AMD FPGA SoC designs, comparable to the Pynq framework.</p>
      <p><a href="https://github.com/jwkunz/Hardroxide">View on GitHub</a></p>
    </article>
    <article class="gallery-item">
      <div class="gallery-meta">
        <span class="tag">C</span>
        <span class="tag">Linux kernel</span>
        <span class="tag">FPGA SoC</span>
      </div>
      <h2><a href="https://github.com/jwkunz/pynq-panther">PYNQ Panther</a></h2>
      <p>A Raspberry Pi-style graphical desktop for the stock PYNQ-Z2: DRM/KMS and ALSA kernel modules, a Rust session, a one-command offline installer, USB input, and a pink-and-black fluxbox theme. No custom bitstream.</p>
      <p><a href="https://github.com/jwkunz/pynq-panther">View on GitHub</a></p>
    </article>
  </div>
</section>
