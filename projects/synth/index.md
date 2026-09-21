---
layout: default
title: Poly-Synth
description: A 3-voice polyphonic synthesizer ASIC, taped out on Tiny Tapeout SKY26c.
---

# Poly-Synth

<p class="status">Taped out on Tiny Tapeout SKY26c, silicon pending</p>
<p><a href="https://github.com/Colbywonn/tt-poly-synth">Repository on GitHub</a></p>

Poly-Synth is a 3-voice polyphonic synthesizer ASIC, taped out on Tiny Tapeout SKY26c. It takes an input as a tuning word over SPI, passes it through one of 3 DDS cores, which consist of a phase accumulator and a shaper. Finally, the 3 voices are mixed arithmetically and are output via oversampling with a 1st-order Sigma-Delta module.

## Hear it

<!-- TODO: your OBS recording. Label it as the FPGA prototype. -->
<audio controls src="/assets/audio/fpga-demo.mp3"></audio>

## System

![Poly-Synth block diagram](/assets/img/block-diagram.svg)

![Poly-Synth die render](/assets/img/die-render.png)

## Verification

<!-- TODO: your words. Golden models per module, mutation testing to confirm the testbenches catch bugs, FPGA MIDI playback. Add the scope frequency check if you do it. -->

## Status and next steps

<!-- TODO: taped out on SKY26c, silicon expected in about a year. What you'll do at bring-up. -->
