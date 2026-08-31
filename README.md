# Zain's Playables

Instant-play HTML5 games built for the web — no downloads, no installs, no dependencies. Designed for platforms like YouTube Playables: fast load, touch-first, short score-chasing sessions.

**Play now:** https://zaincb.github.io/youtube-playables/

## Games

### Orbit Dash

A one-tap idle arcade game. Your ship orbits a planet — tap to leap between orbit rings and dodge asteroids as the speed ramps up. Runs earn Stardust to spend on upgrades: score boosts, shields, an autopilot that dodges for you, and drones that keep earning even while you are away. Sound effects, near-miss bonuses, and best score all included; progress is saved locally.

- **Play:** https://zaincb.github.io/youtube-playables/orbit-dash/
- **Controls:** tap / click / spacebar
- **Tech:** vanilla JavaScript + Canvas, single self-contained HTML file, zero dependencies

### Astro Stack

A one-tap idle stacking game. Drop sliding blocks to build the tallest tower — overhangs get sliced off, perfect drops chain combos for bonus crystals. Spend crystals on upgrades: wider bases, slower blocks, richer payouts, and miners that keep earning even while you're away (offline earnings included).

- **Play:** https://zaincb.github.io/youtube-playables/astro-stack/
- **Controls:** tap / click / spacebar
- **Tech:** vanilla JavaScript + Canvas, single self-contained HTML file, zero dependencies

### Nova Merge

A swipe-to-merge space puzzle (2048-style). Slide the board to fuse matching celestial bodies — comets into moons, planets into stars, all the way up to galaxies. Merges earn nova points to spend on upgrades: luckier spawns, undos, richer payouts, and comets that keep earning even while you're away (offline earnings included).

- **Play:** https://zaincb.github.io/youtube-playables/nova-merge/
- **Controls:** swipe / arrow keys (Z = undo)
- **Tech:** vanilla JavaScript + Canvas, single self-contained HTML file, zero dependencies

## Running locally

Open any game's `index.html` in a browser, or serve the repo root:

```bash
python3 -m http.server 8000
```

then visit http://localhost:8000.
