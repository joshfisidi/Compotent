# Orbital Glass CTA

A zero-JS, zero-dependency, single-file HTML component demo focused on high-fidelity visual UI craft.

## Design stack used
- Layered radial-gradient orb for volumetric depth
- Dual pseudo-elements (`::before` + `::after`) for highlight + caustic shimmer
- Dual animation systems (breath + drift)
- 3-tier glow cascade (core / mid / ambient)
- Counter-rotating orbital rings with particle node highlights
- Glass CTA button with backdrop blur + saturation
- Inset top-shine and hover shimmer sweep
- Springy hover timing (`cubic-bezier(0.34,1.56,0.64,1)`)
- Tactile active press response
- Micro-orb in button with independent pulse cycle

## Files
- `index.html` — full component (self-contained)
- `preview.png` — static screenshot
- `loop.gif` — short looping animation capture

## Run locally
```bash
cd orbital-glass-cta
python3 -m http.server 4312
# open http://localhost:4312/index.html
```
