# STAMP

A generative grid sandbox. Black/white binary cells with dithered "stamps" and a 4-color palette layer system, driven by a configurable BPM and a stack of procedural systems (chaos, tendrils, tracers, diggers, bombs, entities, pulses, band shifts, evolution, collapse).

Single-file HTML. WebGL2 fragment shader sampling a CPU-side cell grid. No build step, no dependencies.

**Live demo:** https://YOUR_USERNAME.github.io/REPO_NAME/

## Controls

- Slider panel for all parameters (BPM, grid size, behavior amounts, evolution, color palette).
- **SPACE** — tap tempo (averages the last 6 taps)
- **F** — toggle fullscreen
- **C** — clear grid
- **I** — reverse colors
- **H** — show/hide control panel

Mobile: panel scrolls vertically, slider drags work horizontally without conflict. Hotkey hints are hidden on small viewports.

## Running locally

Open `index.html` in any modern browser. That's it.

## Embedding

Designed to be embedded as an `<iframe>`. The canvas auto-fits as a square inside whatever box it's given, with black letterboxing if the container isn't square. Off-screen scroll and tab-hidden pause the simulation automatically.

```html
<iframe
  src="https://YOUR_USERNAME.github.io/REPO_NAME/"
  loading="lazy"
  allow="fullscreen"
  style="width: 100%; aspect-ratio: 1/1; border: 0;"
></iframe>
```

## License

[fill in if you want one]
