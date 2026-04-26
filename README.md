# Interactive 3D Solar System — JavaScript & Three.js
Ever wondered what it looks like to fly through the Solar System in real time? This is a browser-based 3D simulation of all 8 planets orbiting the Sun, built entirely from scratch using JavaScript and Three.js — no game engines, no templates.

Each planet has its own real texture map, accurate relative size, and orbital speed. Click any planet and the camera smoothly flies to it and locks on, following it through its orbit while you freely rotate the view. Press Escape to pull back out.

A few details I'm particularly proud of:

•	Earth has a real day/night shader — the side facing the Sun shows the daymap, the dark side shows city lights at night, and the boundary shifts naturally as Earth orbits
•	Saturn has a semi-transparent ring with an alpha texture
•	Jupiter's four Galilean moons orbit independently
•	An adjustable speed slider lets you slow down or speed up the entire system

# Solar System Orbital View
A real-time 3D simulation of all 8 planets orbiting the Sun, built in the browser using JavaScript and Three.js. Each planet features high-resolution texture maps and independent orbital speeds.

# Interactive Planet Details
Clicking any planet triggers a smooth camera fly-in that locks onto and follows the planet through its orbit. A detailed info panel displays real astronomical data for each body in the Solar System.
