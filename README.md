
# 3D Geodetic Satellite Orbit Simulation

An interactive 3D space simulation built using **Three.js (WebGL)** to visualize different satellite orbits around the Earth.

##  Demo Video

[![Watch the demo](https://img.shields.io/badge/🎬-Watch_Demo_Video-red?style=for-the-badge)](https://github.com/Mobinravan/Geodetic-Satellite-Simulation/raw/refs/heads/main/assets/demo.mp4)

##  Developer
- **Mobin Ravan**

##  Main Features
- **3D Earth:** A beautiful 3D model of Earth with an independent moving cloud layer.
- **Interactive Orbit Paths:** Visualizes various real-world satellite orbits (like ISS, GPS, GEO, and the Moon).
- **Smooth Mouse Interaction:** Easily hover over any satellite node to instantly view its details without lag.
- **Dynamic Laser Line:** Draws a laser beam from the selected satellite to the center of the Earth.
- **Offline Map Support:** Automatically generates a backup world map if the internet texture fails to load.

##  Satellites Modeled
1. Near Earth Surface
2. ISS (International Space Station)
3. Remote Sensing (EO)
4. TOPEX/POSEIDON
5. PAGEOS Balloon
6. LAGEOS Geodetic Satellite
7. GPS Constellation
8. GEO (Geostationary Orbit)
9. Luna (The Moon)

##  Orbital Data Reference

The orbital parameters used in this simulation are based on **Table 3.6** from the book:

> **Seeber, G. (2003).** *Satellite Geodesy: Foundations, Methods, and Applications* (2nd ed.). Walter de Gruyter.

| r (km) | h (km) | v_c (km/s) | U (min/h/d) | Example |
|--------|--------|------------|--------------|---------|
| 6,378 | 7 | 7.91 | 84.49 min | Near Earth's surface |
| 6,770 | 400 | 7.67 | 92.57 min | Space Station / Gravity field missions |
| 7,400 | 1,000 | 7.34 | 105.6 min | Earth observation satellites |
| 7,730 | 1,360 | 7.18 | 112.9 min | TOPEX/POSEIDON |
| 10,000 | 3,600 | 6.31 | 165.6 min | PAGEOS |
| 12,300 | 5,900 | 5.69 | 226.2 min | LAGEOS |
| 26,600 | 20,200 | 3.87 | 12 h | GPS |
| 42,160 | 35,790 | 3.07 | 23 h 56 min | Geostationary satellite |
| 384,400 | — | 1.02 | 27 d 8 h | Moon |

##  How to Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/Mobinravan/Geodetic-Satellite-Simulation.git](https://github.com/Mobinravan/Geodetic-Satellite-Simulation.git)
