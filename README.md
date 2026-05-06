# 🎵 Zero-Drain Musical Gift Box
A battery-powered musical box circuit that plays a custom MP3 when opened. Doesn't drain battery when closed.

![DIY Arduino + DFPlayer Mini Music Box circuit diagram](assets/DIY%20Arduino%20+%20DFPlayer%20Music%20Box.jpeg)

## ✨ Features
*   **Absolute Zero Idle Drain:** The limit switch is wired directly into the main power circuit. When the box is closed, the circuit is physically broken—meaning 0.0mA of battery drain. 
*   **Clone-Proof Logic:** Built specifically to work with the notoriously stubborn **HW-247A V0.5.1** DFPlayer Mini clones that lack standalone ADKEY functionality.
*   **Safe Audio Output:** Programmed with a controlled startup delay and safe volume limits to protect smaller (0.5W) speakers from blowing out.

## 🧰 Hardware Requirements
*   **Microcontroller:** Arduino Uno or Nano
*   **Audio Module:** DFPlayer Mini (Tested with HW-247A V0.5.1)
*   **Storage:** MicroSD Card (formatted to FAT32)
*   **Trigger:** Micro Limit Switch (Normally Closed / NC)
*   **Speaker:** Up to 3W 4-Ohm Speaker (8-Ohm worked for me)
*   **(Optional but recommended) Protection:** 1x 1k Ohm Resistor
*   **Power:** 9V battery with 9V battery to DC jack
