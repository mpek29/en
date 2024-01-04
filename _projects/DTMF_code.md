---
layout: page
title: Sound recognition
description: Mathematical tool in Python
img: assets/img/projects/DTMF_code/main.jpg
importance: 4
category: 2022
---
During my 4th semester at ENIB, as part of the subject dedicated to Euclidean space, my colleagues and I had the opportunity to work on a project based on the DTMF code. This code is made up of a combination of frequencies used in conventional telephony. These frequencies are emitted when a key is pressed on a telephone keypad, resulting in the production of an instinctive sound for each key.

The aim of the project was to distinguish the number of the key pressed by the user by recording only the sound emitted when the key is pressed. The second was to remove the DTMF code present in a sound recording in order to distinguish a voice masked by it.

To achieve this, we made use of mathematical concepts. Each frequency was represented by a vector, and the aim was to project the recording into our Euclidean base and determine which vectors of the base the recording best corresponded to.
