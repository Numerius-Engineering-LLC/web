---
title: Curriculum
description: Educational resources and course material by Numerius Engineering LLC, organized by subject.
---

<section class="page-header">
  <p class="eyebrow">Curriculum</p>
  <h1>Learning resources.</h1>
  <p class="lead">Books, courses, and teaching material, organized by subject. Each entry links to the full resource.</p>
</section>

<!--
  HOW TO ADD CONTENT
  New resource in an existing subject: copy an <article class="gallery-item"> block
  into that subject's <div class="gallery-grid"> and edit the tags, title, text, and links.
  New subject: copy a whole <section class="section-block" id="..."> block, give it a new id,
  and add a matching link to the "Subjects" list below.
-->

<section class="section-block">
  <div class="section-heading">
    <p class="eyebrow">Subjects</p>
    <h2>Browse by topic.</h2>
  </div>
  <div class="gallery-meta">
    <a class="tag" href="#scientific-computing">Scientific computing</a>
    <a class="tag" href="#computing-programming">Computing and programming</a>
    <a class="tag" href="#fpga-embedded">FPGA and embedded systems</a>
    <a class="tag" href="#radio-signals">Radio and signals</a>
  </div>
</section>

<section class="section-block" id="scientific-computing">
  <div class="section-heading">
    <p class="eyebrow">Scientific Computing</p>
    <h2>Numerical methods and algorithms for engineers, physicists, and applied mathematicians.</h2>
  </div>
  <div class="gallery-grid">
    <article class="gallery-item">
      <div class="gallery-meta">
        <span class="tag">Book</span>
        <span class="tag">Rust</span>
        <span class="tag">Algorithms</span>
        <span class="tag">Self-paced</span>
      </div>
      <h2><a href="https://jwkunz.github.io/lib_jsl/book/">The lib_jsl Book</a></h2>
      <p>An encyclopedia-style technical book with 188 entries covering the subjects in the lib_jsl scientific computing library. Each entry presents the idea, the algorithm, measured results, and exercises.</p>
      <p><a href="https://jwkunz.github.io/lib_jsl/book/">Read the book</a> &middot; <a href="https://github.com/jwkunz/lib_jsl">View the library on GitHub</a></p>
    </article>
  </div>
</section>

<section class="section-block" id="computing-programming">
  <div class="section-heading">
    <p class="eyebrow">Computing and Programming</p>
    <h2>How computers, operating systems, and networks work, and how to write simple programs.</h2>
  </div>
  <div class="gallery-grid">
    <article class="gallery-item">
      <div class="gallery-meta">
        <span class="tag">Course</span>
        <span class="tag">Grades 7&ndash;12</span>
        <span class="tag">Python</span>
        <span class="tag">Networking</span>
      </div>
      <h2><a href="https://github.com/jwkunz/Radiant_Pupils">Radiant Pupils</a></h2>
      <p>A structured class for students in grades 7&ndash;12 covering how computers work, the role of operating systems, how computers are networked, simple Python applications, and scientific computing with Jupyter notebooks. Each numbered lesson pairs theory with a laboratory exercise, with starting-point problems and worked solutions.</p>
      <p><a href="https://github.com/jwkunz/Radiant_Pupils">View the course on GitHub</a></p>
    </article>
  </div>
</section>

<section class="section-block" id="fpga-embedded">
  <div class="section-heading">
    <p class="eyebrow">FPGA and Embedded Systems</p>
    <h2>Programming FPGA SoC designs from Rust, on Linux, bare metal, and an RTOS.</h2>
  </div>
  <div class="gallery-grid">
    <article class="gallery-item">
      <div class="gallery-meta">
        <span class="tag">Book</span>
        <span class="tag">Rust</span>
        <span class="tag">FPGA SoC</span>
        <span class="tag">Tutorials</span>
      </div>
      <h2><a href="https://jwkunz.github.io/Hardroxide/book/index.html">The Hardroxide Book</a></h2>
      <p>The guide to Hardroxide, a tool that turns a Vivado hardware export into a typed Rust crate for an FPGA SoC design, as a Rust counterpart to the PYNQ overlay framework. It covers installing and using the tool, choosing between Linux, bare-metal, and RTOS programs, and a series of hands-on tutorials from blinking LEDs to DMA, with reference pages for the generated drivers.</p>
      <p><a href="https://jwkunz.github.io/Hardroxide/book/index.html">Read the book</a> &middot; <a href="https://github.com/jwkunz/Hardroxide">View Hardroxide on GitHub</a></p>
    </article>
  </div>
</section>

<section class="section-block" id="radio-signals">
  <div class="section-heading">
    <p class="eyebrow">Radio and Signals</p>
    <h2>Software-defined radio: how signals work, and how to receive and program them.</h2>
  </div>
  <div class="gallery-grid">
    <article class="gallery-item">
      <div class="gallery-meta">
        <span class="tag">Book</span>
        <span class="tag">SDR</span>
        <span class="tag">Radio primer</span>
        <span class="tag">Python</span>
      </div>
      <h2><a href="https://jwkunz.github.io/LANline/">The LANline Book</a></h2>
      <p>The guide to LANline, with no engineering background assumed. It covers installing the server and Android app, receiving a first signal, and writing short Python programs against the radio's API, then suggests projects to build. A radio primer explains waves, antennas, modulation, software-defined radio, networking, and the voice, data, and picture signals involved. A demo build lets you start without a radio.</p>
      <p><a href="https://jwkunz.github.io/LANline/">Read the book</a> &middot; <a href="https://github.com/jwkunz/LANline">View LANline on GitHub</a></p>
    </article>
  </div>
</section>
