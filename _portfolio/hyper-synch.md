---
title: "hyperSynch"
excerpt: "Simple & cheap solution to synchronizing multiple EEG systems with each other AND video and audio while recording these data"
author_profile: true
header:
  teaser: assets/images/synch_teaser.jpg
---

One of the biggest challenges of doing multiple person EEG is a technical one: how can we synchronize multiple systems with each other and with other data streams we might have? (i.e. video, music...). I came up with a simple and efficient solution: using a simple Arduino circuit, I send three logical 1's to (1) parallel ports of EEG systems, (2) the audio recording, and (3) the audio channel of the camera. This ensures that all the systems are synchronized (using an oscilloscope, we tested the delays between the pulses, which ended up being of 4µs). You can see the basic circuit here:

![circuit](/assets/images/synch_diagram.png)

## Status
Finished; I use this for my masters thesis testing

## Skills developed
* Creating a very simple circuit using Arduino
* Arduino programming language
* Basic embedded programming

## Output
A detailed step by step procedure can be found [here](https://github.com/neurohazardous/hyperSynch)
