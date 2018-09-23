---
title: "hyperSynch"
excerpt: "Simple & cheap solution to synchronizing the recording of multiple EEG systems with each other and video/audio data"
author_profile: true
header:
  teaser: assets/images/synch_teaser.jpg
classes: wide
---

Synchronizing multiple EEG systems is one of the biggest challenges of doing hyperscanning (multiple person imaging/electrophysiology). I came up with a simple and efficient solution: a simple Arduino circuit that sends three logical 1's to (1) the parallel ports of multiple EEG systems, (2) the audio recording, and (3) the audio channel of the camera. This ensures that all the systems are synchronized. The delays between the pulses are of 4µs (negligible). You can see the basic circuit here:

![circuit](/assets/images/synch_diagram.png)

## GitHub Repository
You can find it [here](https://github.com/neurohazardous/hyperSynch)

## Status
Finished; I use this for my masters project testing

## Skills developed
* Creating a very simple circuit using Arduino
* Arduino programming language
* Basic embedded programming
