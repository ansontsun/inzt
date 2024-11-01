---
title: "FPGA Clarinet Simulator"
date: 2024-04-30
draft: false
ShowToc: true
cover:
  image: "/assets/FPGA_Clarinet_Simulator/FPGA_Clarinet_Simulator_Main.png"
  # can also paste direct link from external site
  # ex. https://i.ibb.co/K0HVPBd/paper-mod-profilemode.png
  alt: "FPGA Clarinet Simulator"
  caption: ""
  relative: false # To use relative path for cover image, used in hugo Page-bundles
---

# Introduction
The FPGA Clarinet Simulator is an application developed in C that simulates the notes produced by a B♭ clarinet. The simulator runs natively on Terasic's DE1-SoC FPGA and is compiled using Quartus.

# Key Features
## Instructions Screen
The instructions screen containing all possible ways the user can interact with the simulator. The characters are transcribed into a collection of pixel in order to be displayed on the VGA display.

{{< figure src="/assets/FPGA_Clarinet_Simulator/FPGA_Clarinet_Simulator_Instructions.png" caption="Figure 1. Instructions screen.">}}

## Keyboard Input
The main interactions (playing notes, recording operations, etc.) with the simulator are accomplished through the PS/2 keyboard. With consistent polling implemented, the simulator is responsive to each key press or hold. The key presses and holds are dynamically indicated on the VGA screen.

{{< figure src="/assets/FPGA_Clarinet_Simulator/FPGA_Clarinet_Simulator_Key_Press.png" caption="Figure 2. Key press visualization.">}}

## Recording & Playback
The simulator is capable to "record" the notes played by storing the audio snippets into on-board memory, for playback or deletion later on. To assist with more challenging music pieces, an animated metronome is built-in. The user is informed of each process ongoing through the dynamically-rendered GUI displayed on the VGA screen.

{{< figure src="/assets/FPGA_Clarinet_Simulator/FPGA_Clarinet_Simulator_Recording_Playback.png" caption="Figure 3. Playback and metronome in action.">}}

# Wrapping Up
There are more technical details than what have been introduced above. The FPGA Clarinet Simulator is a challenging project that built my skills in FPGA programming and UI design.

I would like to thank my team member Raida Fardous for her dedication and effort put into this application.

# Source Code
Due to university policy, the source code of the FPGA Clarinet Simulator generally needs to remain private. However, if source code is required for purposes such as employment screening, please [contact me](/).