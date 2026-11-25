# Gustwing 2.0

An original one-button flyer: a scarfed wind-sprite threads sandstone spires
through a sky that turns from day to dusk to night to dawn as you score.
It is one HTML file. There are no assets, and the sound is synthesised.
Open `index.html` in a browser to play.

## What we studied (the genre's core loop)

| Mechanic | Why it works | Gustwing value |
|---|---|---|
| One input: tap = upward impulse, constant gravity | Zero learning curve, all skill is timing | gravity 1500 px/s², flap −440 px/s |
| Body tilts with vertical speed | Reads momentum at a glance | rot = vy / 560, clamped |
| Endless paired obstacles with a gap | Every gate is a tiny pass/fail test | spires every 214 px |
| One point per gate, instant death | Short runs, "one more try" loop | ground kills, ceiling clamps |
| Medals + best score | A long-term goal for a short game | bronze 10, silver 20, gold 30, platinum 50 |

## What 2.0 adds

- **Difficulty curve**: the gap shrinks from 170 to 128 px and speed rises from 150 to 225 px/s over the first 45 points.
- **Moving gates** from score 8. The gap drifts up and down, marked with arrows.
- **Perfect passes**: fly through the centre of a gate for +1 bonus. Perfects in a row build a streak.
- **Gems**: collect them and spend them on skins (Teal, Ember 40, Violet 120, Gilded 300).
- **Power-ups**: Shield (absorbs one hit or a ground touch), Slow time (5 s), and Gem magnet (8 s).
- **Day-night cycle** with parallax ridges, clouds, stars and a sun or moon.
- **Feel**: particles, screen shake, floating callouts, and synthesised sound effects.
- **Quality of life**: pause (P/Esc, auto-pauses on blur), mute (M), and local best score.

Controls: Space / ↑ / W / click / tap to flap.
