# Call of Doody: Porcelain Warfare

A single-file HTML5 Canvas tactical sanitation arcade game featuring procedural Web Audio sound effects, 4 missions, 4 tactical hydration loadouts, in-bowl power-ups, Kegel Overcharge bursts, and a persistent global leaderboard.

## Play Online

**[Play Live on GitHub Pages](https://davidhughes750.github.io/call-of-doody-porcelain-warfare/)**

## Features

- **Operative Callsign Prompt**: Enter your callsign on the home briefing screen before deploying (saved automatically across sessions).
- **Persistent Global Leaderboard & Operative Ranks**: Tracks top personal-best scores per unique operative (1 row per player with rank badge `PVT`–`GEN` and total plays badge) alongside live global mission/operative counters on both the home briefing screen and mission debrief report.
- **In-Bowl Power-Ups & Kegel Overcharge**: Pop **Urinal Cake Bombs** for a `-25%` splashback foam shockwave, pop **Hydration Bubbles** for `+20%` tank refills, and hold off fire for `2s` to unleash a `2.2x` **Kegel Overcharge** burst with FPS hit-markers and debrief medals.
- **Mobile & Touch Optimized**: Features thumb-offset touch aiming with a dedicated **HOLD TO FIRE STREAM** button, a Retina (`devicePixelRatio`) canvas, proportional portrait bowl scaling with safe-area support, and a compact single-row mobile HUD.
- **Drill Sergeant Radio Comms & Background Music**: Includes looping game soundtrack (`audio/game_music.mp3`) with automatic voice ducking and music toggle, plus 8 Gunnery Sgt. Hartman-inspired MP3 voice lines (`audio/*.mp3`) triggered on mission deploy, crust clearing, floater sinking, splashback warnings, tactical flush, victory, and court martial.

## Missions

1. **Op: Taco Tuesday** *(Suburban Bathroom)* — Moderate surface skids, baked-on crust clusters, and a rogue floater.
2. **Op: Curry Night** *(Apartment Suite)* — Dense baked-on crust formations and a regenerating Slime Streak.
3. **Op: Festival Porta-Potty** *(Hazmat Warzone)* — High stain density, Slime Streaks, and a splitting Cluster Floater inside a chemical blue basin.
4. **Op: Truck Stop Latrine** *(Interstate Bio-Boss)* — Boss stage packed with regenerating Slime Streaks and twin Cluster Floaters.

## Tactical Hydration Loadouts

- **Tap Water** — Balanced pressure, capacity, and steady aim.
- **Black Coffee** — +50% hydro-pressure for heavy crust, with high caffeine jitter.
- **Nitro Energy** — Neon tracer stream with 2.0x armor shred and fast drain rate.
- **Light Beer** — +65% bladder tank capacity with heavy drunken aim sway.

## Controls

- **Mouse / Touch Drag** — Aim stream
- **Desktop Fire** — Hold Left Mouse Button or `Space`
- **Mobile Fire** — Hold the dedicated **HOLD TO FIRE STREAM** button while aiming with your other thumb
- **`F` or Tactical Flush Button** — Trigger single-use Tactical Flush (clears loose skids & pushes floaters toward the drain, costs 5s)
- **Audio Button (`🔊`/`🔇`)** — Toggle procedural Web Audio sound effects

## Running Locally

Open `index.html` directly in any modern web browser. No build step or external assets required.
