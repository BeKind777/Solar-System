# Solar System Orrery

An interactive, rotatable 3D model of the solar system that runs entirely in your browser. It is a single HTML file with no server, no accounts and no tracking.

**Live demo:** bekind777.github.io/Solar-System/

> This project was written entirely by [Claude Code](https://claude.com/claude-code), Anthropic's AI coding assistant, through a conversation with its author.

## Features

- **Accurate positions.** The Sun, eight planets, dwarf planets (Ceres, Pluto, Eris, Haumea, Makemake), major moons and Halley's Comet are placed from published orbital elements for any date. Drag to rotate, scroll or pinch to zoom, tap a body to select it and tap again to focus on it.
- **Moons, asteroids and meteoroids.** Moon orbits, the asteroid belt, Jupiter Trojans, the Kuiper belt and the Halley meteoroid stream.
- **Real-time start.** It opens at the current time, running at real speed. Speed can be raised up to 5 years per second, reversed, or jumped to any date.
- **Textured planets.** Zoom in far enough and planets and the Moon become textured spheres, with the correct rotation phase and day/night shading.
- **Telescope observability.** Pick a telescope from a long list of common models (or add your own) and see which bodies are visible from your city, with sky charts, rise and set times and the Moon's path.
- **City picker.** US, Chinese and Australian cities, with UTC and local time shown side by side and daylight saving handled automatically.
- **Lagrange points.** Choose any two bodies and see their five Lagrange points in 3D, with stability and example missions.
- **Two-point transfer.** Straight-line distance and light travel time, a Hohmann transfer with launch window, flight time and Δv, a rocket-equation mass estimate with rocket presets, and the formulas used.
- **Ecliptic projection lines** to see how far each body sits above or below the ecliptic plane.
- **English and Chinese**, switchable in the page.
- **Works on phones**, with touch-friendly controls.

## Run it

Open in any modern browser, or enable GitHub Pages for this repository and open the published link. Nothing needs to be installed.

## Accuracy

Planet positions use JPL's approximate Keplerian elements (valid for 1800 to 2050), typically accurate to a few arcminutes. Dwarf planets and Halley's Comet use published elements. The asteroid belt, Trojans, Kuiper belt and meteoroid stream are statistical samples, not real catalogs. Transfer calculations are first-order estimates (circular, coplanar orbits, no gravity losses), good for comparing options but not for real flight planning.

## Privacy

The page does not send any data anywhere. Your selected city is only used inside the page to compute sky positions.

## Credits

- Planet positions: JPL approximate Keplerian elements; Moon model after Paul Schlyter.
- Textures: planet and Moon maps from [Planet Pixel Emporium](http://planetpixelemporium.com/planets.html), obtained through [threex.planets](https://github.com/jeromeetienne/threex.planets) and downscaled. threex.planets is MIT licensed, but that covers its code; the textures remain under Planet Pixel Emporium's own terms.
- Built with Claude Code.
