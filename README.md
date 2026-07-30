# Baja Blast: Desert Truck Racer

A modern indie "retro-revival" racing game designed to pay homage to the golden era of arcade racers.

## Game Type & Genre
This game is a **Pseudo-3D Arcade Racer** (often called a "Chase-View" Racing Game). Before true 3D polygon graphics were possible, developers used clever 2D programming tricks to create the illusion of depth. This specific visual technique relies on:

- **Raster Scrolling (Line Scrolling):** The road is drawn using flat 2D horizontal lines that shift left and right row-by-row to simulate curves.
- **Sprite Scaling:** Roadside objects (like cacti and signs) start as tiny 2D sprites in the center of the screen and rapidly scale up in size as they move toward the edges to simulate the camera moving past them.

## Era Replicated
The aesthetic heavily replicates the late 1980s to early 1990s (specifically the 8-bit and 16-bit generations of arcades and home consoles):
- **Late 80s (8-bit):** Games like *Rad Racer* (1987) on the NES and Sega's *OutRun* (1986) in arcades pioneered and popularized this exact visual format.
- **Early 90s (16-bit):** The era peaked on platforms like the SNES and Sega Genesis with titles like *Top Gear* (1992) and *Lotus Esprit Turbo Challenge* (1990).

While capturing that classic 8-bit/16-bit era flawlessly, the crisp widescreen aspect ratio, full-viewport layout, and modern user interface elements (like the high-resolution font and nitro bar) elevate it with modern design sensibilities.

## Features
- **Dynamic Day/Night Cycle:** The sky naturally transitions from dusk, through night (complete with a moon and stars), back to daytime over the course of a race.
- **Responsive Layout:** The game scales dynamically to fill any screen size (`100vw`/`100vh`) using smart `object-fit` scaling to preserve the classic layout without cropping.
- **Audio Integration:** Synthesized engine noises paired with background tracks powered by the YouTube IFrame API.
- **Mobile Friendly:** Fully playable on mobile devices with an integrated touch control pad.

## Controls
- **↑ / W:** Gas
- **↓ / S:** Brake
- **← → / A D:** Steer
- **SHIFT / SPACE:** Nitro
- **P:** Pause
- **M:** Mute Sound
- **ENTER:** Start / Restart

## Technical Details
Built from scratch with zero dependencies using:
- **HTML5 Canvas 2D API** for high-performance procedural rendering.
- **Vanilla JavaScript** for game logic and physics.
- **Modern CSS (Flexbox)** for responsive UI overlays.
