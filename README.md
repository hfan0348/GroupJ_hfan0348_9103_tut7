# Pacman x PIET Neon-style Game Display

This p5.js project displays neon-style text inspired by arcade aesthetics.

## 1. INTERACTION, ANIMATION APPROACH, AND DRIVER
- _**How to Interact with the Work**_
    - This project features _**two interaction methods:**_
        1. **Mouse Click:** 
        triggers background music
        ```
        "Click the screen to start the music"
        ```
        2. **Sound Input:** 
        animates text in response to audio amplitude
    - Clicking anywhere on the canvas starts the background track. Once the music is playing, the title texts _"Pacman" and "* PIET"_ begin to **flicker and glow**. Their brightness is driven by the **live sound input**, creating a reactive neon light effect that synchronizes with the music.

- _**My Individual Animation Approach**_
    - My contribution focuses on the text animation, designed to resemble a retro arcade neon sign. I use a **dot-matrix typography style** rendered with circles instead of `text()` to gain fine-grained control over visual rhythm. The layout is inspired by **arcade aesthetics** and **Piet Mondrian’s grid compositions.**
    - This animation is visually distinct from the rest of the project by:
        1. Animating text
        2. Using brightness and flicker changes rather than motion or color
        3. Responding to audio input instead of mouse movement or time

- _**What Drives My Animation**_
1. **Driver:** Audio input (via `p5.FFT`)
2. **Effect:** Maps amplitude values to brightness of each text dot
3. **Result:** Text pulses in sync with music beats, simulating real-time audio-reactive neon signage

## 2. VISUAL INSPIRATIONS
The visual language of my individual contribution draws heavily from **retro arcade aesthetics,** with a particular focus on **dot-matrix text,** **vintage gaming consoles,** and **neon signage.** These elements work together to evoke the feeling of an old-school game cabinet brought to life with modern browser technology.
1. Dot-Matrix Text
Inspired by pixel-based displays used in vintage game systems, my text design uses a grid of circular dots to form letters. 
- 
![An image of Dot-Matrix LED Text](example1_dot_font.jpg)
[Example of Dot-Matrix LED Text](https://www.instructables.com/Arduino-LED-Display/)
2. Neon Signboard Effect
3. Arcade Console Interface
