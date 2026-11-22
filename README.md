# ✦ Orbit

### A little universe for the thoughts you want to keep close.

Orbit is a calming, single-page notes app that turns your thoughts into glowing stars. Add a note, give it a place in one of the moon’s orbits, and watch it drift through a quiet night sky.

<p align="center">
  <strong>Write a thought&nbsp; · &nbsp;Set it in orbit&nbsp; · &nbsp;Come back to it when you need it</strong>
</p>

##  Features

- **A living night sky** — layered stars, glowing orbital paths, a detailed moon, and a gentle sense of motion.
- **Notes as orbiting stars** — create a thought and choose which orbit it belongs to.
- **Easy to revisit** — select any star to read or edit its note, or remove it when you’re ready.
- **Saved on your device** — notes persist in your browser using `localStorage`; there’s no account to create.
- **A live clock and date** — a small reminder of the moment you’re writing in.
- **Keyboard friendly** — use Tab to reach the orbits and stars, Enter or Space to open them, and Escape to close the note editor.
- **Responsive and self-contained** — built with plain HTML, CSS, SVG, and JavaScript, with no frameworks or dependencies.

## Get started

No install or build step is needed.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Select an orbit or choose **Add a thought** to create your first note.

You can also serve the folder with any static web server. The app runs entirely in the browser.

##  Your notes

Orbit stores notes in your browser’s local storage under `orbit-notes-v1`. They stay on that browser and device, and are not synced to an account or sent to a server. Clearing the browser’s site data will remove them.

##  Built with

- HTML, CSS, and vanilla JavaScript
- SVG for the orbital paths, moon, and animated stars
- `localStorage` for on-device note persistence
- `requestAnimationFrame` for smooth orbital motion

##  Make it yours

The colors, orbit geometry, and animation are defined in `index.html`, so you can customize the universe without a build tool. Change the palette in the CSS variables, or adjust the orbit sizes and speeds in the JavaScript.

---

<p align="center"><em>Some thoughts deserve their own little universe.</em></p>
