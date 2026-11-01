# All-Range

A free-flight 3D arcade dogfighter that runs in your browser. Fly anywhere inside a large circular combat zone, clear the enemy carrier's fighters out of the sky, and see how many hits you can rack up before you're shot down. One life, so fly carefully: crashing into terrain tears most of your shield away.

**Play:** https://dhfm91.github.io/all-range/

## Maps

A different map is picked every day at midnight (Eastern), never the same one two days in a row:

- **Green Valley**: rolling hills and forest around the base.
- **Broken Sea**: an island base in open water, ringed by sea stacks. The sea surface is as hard as the ground.
- **Spire Canyon**: red rock canyons and dozens of tall stone spires to thread between.

To try a specific map, add `?map=valley`, `?map=ocean` or `?map=spires` to the address.

## Controls

### Mouse + keyboard (recommended)

Click **START** and the game captures your mouse for aiming (press Esc to release it).

| Input | Action |
| --- | --- |
| Mouse | Aim. The nose follows the cursor |
| Left click | Fire. Hold to charge, lock on, release |
| Right click | Shield (bounces enemy fire back) |
| Wheel up / down | Loop (get behind a pursuer) / U-turn |
| W / S | Boost / Brake |
| A / D | Bank for tight turns |
| Space or middle click | Bomb (press again to detonate) |
| [ / ] | Mouse sensitivity down / up |
| T | Invert pitch |

### Keyboard only

| Key | Action |
| --- | --- |
| WASD / Arrows | Steer |
| Space / J | Fire. Hold to charge, lock on, release |
| B | Bomb (press again to detonate) |
| C | Shield |
| Shift / Z | Boost / Brake |
| Q / E | Bank for tight turns |
| R / F | Loop / U-turn |

**Any time:** V camera, M mute, P or Esc pause.

Gamepads work too: left stick steers, A fires, X bombs, RT/LT boost and brake, LB/RB bank, left stick click raises the shield, Y loops, B U-turns.

## On a phone or tablet

Touch controls appear automatically. Drag anywhere on the left side to steer (push all the way sideways for a tight turn). The right thumb gets FIRE (hold to charge a lock-on shot), SHIELD, BOOST, BRAKE, BOMB, LOOP and U-TURN. Landscape works best.

## Running it locally

Download `index.html` and `three.min.js` into the same folder and open `index.html` in a browser. Everything runs offline except the global scoreboard.

The 3D engine is [Three.js](https://threejs.org) r128, included as `three.min.js` under its MIT license.
