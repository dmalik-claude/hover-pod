# Hover Pod

An interactive 3D concept-vehicle hero page. Power it up and the pod lifts off and hovers; switch the headlights and brake lights on, honk, or flip between light and dark studio modes.

## Open it

Download the repository and double-click `index.html` — no install or server needed. Keep `car-assets.js` next to it (it holds an embedded copy of the 3D model).

## Controls

| Control | What it does |
| --- | --- |
| **Power** | Spools up, lifts off and hovers (with sound); press again to land |
| **Headlights** | Main and side lamps on, with a light beam and floor glow |
| **Brake lights** | Rear lamps glow red |
| **Honk** | Horn and a headlight flash |
| **Reset** | Lands the pod, switches everything off, returns to the starting view |
| **Sound on / off** | Mutes or unmutes all sounds |
| **Dark / Light mode** | Switches the studio backdrop and lighting |

Drag to turn the vehicle, scroll or pinch to zoom, double-click to reset the view.

## Built with

- [three.js](https://threejs.org/) r170, loaded from jsDelivr
- Sounds are synthesised live with the Web Audio API
- Model: `futuristic vehicle 3d model.glb`

The designer's Futura Cyrillic fonts are licensed and are not included; the page falls back to the Futura that ships with macOS, or Century Gothic / Avenir elsewhere.
