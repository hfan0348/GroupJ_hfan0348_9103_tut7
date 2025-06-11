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
My visual design is inspired by:

Retro arcade signs and LED dot-matrix displays

Piet Mondrian’s Broadway Boogie Woogie (1942–43), which influenced the structured grid and rhythm of the text animation
