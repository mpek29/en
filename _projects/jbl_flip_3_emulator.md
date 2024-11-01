---
layout: page
title: JBL Flip 3 Emulator
description: Open-source JBL Flip 3 emulator
img: assets/img/projects/jbl_flip_3_emulator/main.jpg
git: https://github.com/mpek29/JBL-Flip-3-Emulator
importance: 1
category: 2024
---

# Introduction
Welcome to my portfolio page dedicated to my JBL Flip 3 emulator project. The aim of this project is to reproduce the tactile and sonic experience of this iconic portable speaker using both hardware and software developed by myself.

Technical aspects:
* **Hardware**: battery charge management and voltage conversion to power an ESP32, which handles Bluetooth functionality as well as the various buttons and LEDs.

* **Software**: I use the Espressif audio development framework to develop a complete firmware. This controls volume, emits sounds for various actions and generates an audio stream via I2S communication between the ESP32 and a MAX98357 amplifier.

The system is modularly designed for ease of repair and maximum durability. I also took care to reuse components I already had in stock.
I'd like to thank Adafruit, my main source of inspiration, notably through their “Aluminum Mounting Grid”, of which I printed a 3D copy with my Ender3, as well as for their excellent modules whose standard format I used.

# Preparation phase
During this first phase of preparation, I made an inventory of all my components with a view to reusing them and not ordering new ones. I also took the time to extract the sound effects from the jbl flip 3. Here they are: found_bt.wav, maximum_volume_limit.wav, search_bt.wav, switching_off.wav and switching_on.wav.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/jbl_flip_3_emulator/sound_extraction.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>