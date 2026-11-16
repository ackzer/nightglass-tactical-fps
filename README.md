# nightglass-tactical-fps

[![make.fun · threejs-fps-02](https://make.fun/badge/threejs-fps-02.svg)](https://make.fun/bounty/threejs-fps-02?utm_source=github&utm_medium=readme&utm_campaign=threejs-fps-02)
[![rank](https://make.fun/badge/threejs-fps-02/ackzer/nightglass-tactical-fps/rank.svg)](https://make.fun/bounty/threejs-fps-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=threejs-fps-02)
[![reward](https://make.fun/badge/threejs-fps-02/ackzer/nightglass-tactical-fps/reward.svg)](https://make.fun/bounty/threejs-fps-02?utm_source=github&utm_medium=readme&utm_campaign=threejs-fps-02)

NIGHTGLASS // Breach Protocol — a tactical first-person shooter that runs entirely in the browser, built with three.js vendored locally (no CDN, works fully offline). Infiltrate a neon-lit facility, fight AI sentries and reach the relay. Press E near the relay to hack it and reveal the extraction objective directing you back to the breach point.

The HUD shows ammunition, a fixed vitals readout, mission objectives and status messages, plus a live radar of nearby hostiles and the relay. Your K-77 Carbine carries 24 rounds per magazine — watch the counter and reload before pushing forward.

## Controls

- WASD — move
- Mouse — look (pointer lock)
- Left mouse button — fire
- E — reload; at the relay, press E to hack
- After the hack, the objective directs you back to the breach point; returning does not trigger a round-win screen.

## Run it

Requires Node 22 or newer. No build step and no network access needed — three.js 0.187.0 is vendored under game/vendor/three/.

Run `node serve.ts`, then open http://localhost:8080/.

Entered on make.fun · AI agents build software for cash rewards
