# GTA Los Santos (PS2) - PNACH 
This repository contains custom PNACH patches developed as part of the **GTA Los Santos** project for PlayStation 2 (*GTA San Andreas*).

These patches focus on improving visual presentation, interface consistency, and rendering distance while maintaining compatibility with the original game engine on PCSX2.

---

## Features

### Interface & HUD Customization

* New Armor Bar color
* Custom radar disk color
* Updated menu selection highlight colors across:

  * Display
  * Gallery
  * Audio
  * Controller
  * Stats
  * Map
  * Brief
  * Game

Color scheme:

* Radar: RGB (255, 163, 196)
* Menu highlight: RGB (245, 188, 209)
* Armor Bar - Blue (value 0x03)

---

### Startup Optimization

* Disabled `open1.pss` intro video for faster boot time

---

### LOD (Level of Detail) Adjustments

- Objects: 0.9  
- Secondary LOD: 0.6  
- Vehicles: 0.9  
- Pedestrians: 0.9  

These adjustments slightly reduce LOD rendering distances to improve performance.  
The visual difference is minimal, but it still provides a noticeable optimization, especially on lower-end systems and real PS2 hardware.

---

## Installation

1. Rename the `.pnach` file to match your game CRC  
Example: C9F6EF9A.pnach

2. Place the file into:

PCSX2/cheats/

3. Enable cheats in PCSX2 settings

4. Launch the game

---

## Compatibility

* Target version: **SLUS_209.46 (USA)**
* Designed for use with the *GTA Los Santos* mod

---

## Credits 🙏

This work was developed with reference to existing PNACH patches created by:

* Daniel Santos
* Pedro PAP

Their contributions were essential for understanding patch structure, memory mapping, and rendering behavior on PS2.

All patches in this repository were independently adapted and customized for the **GTA Los Santos** project.

---

## Author

Henrique

---

## Disclaimer

This repository does not contain any original game files.
All content is intended for modding and educational purposes only.
