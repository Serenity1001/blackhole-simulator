# Black Hole Simulator

Interstellar-inspired black hole simulator built as a single HTML file with HTML5 Canvas 2D. Throw celestial bodies into Gargantua and watch accretion-disk physics, gravitational lensing approximations, tidal disruption, event-horizon absorption, and impact-point rewind convergence in real time.

## Live Demo

> After enabling GitHub Pages, replace this with your URL:
> `https://<username>.github.io/<repo>/`

## Features

- **3 black hole masses**: Cygnus X-1 (stellar), IMBH (intermediate), TON 618 (supermassive)
- **5 throwable bodies**: Moon, Earth, Saturn, Jupiter, Sun
- **Interstellar-style visuals**: photon ring, top-arc gravitational lensing, equatorial beam, red low-luminosity accretion palette
- **Interactive controls**: brightness (color-scaled, not just alpha), zoom, viewing tilt (edge-on ↔ face-on), time speed (1×–100×)
- **Rigid-body cluster physics**: thrown objects maintain a spherical shape until tidal forces near the horizon progressively shred them
- **Horizontal shred burst**: on approach to the event horizon, radial plunge is converted into tangential burst with trailing spaghettification particles
- **Impact-point rewind convergence**: after absorption, scattered particles gracefully converge back to the impact point via velocity-blending (not force addition)

## Running Locally

Just open `index.html` in a browser — no build step.

For local dev server (optional):

```bash
python -m http.server 8080
# open http://localhost:8080/
```

## Tech

Pure vanilla JavaScript + HTML5 Canvas 2D. No frameworks, no dependencies, no build step.

## License

MIT
