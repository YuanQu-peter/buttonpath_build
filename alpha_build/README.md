# Alpha build

Play: https://yuanqu-peter.github.io/buttonpath_build/alpha_build/

- Release date: 2026-10-20 (America/Los_Angeles).
- Source: [Team200 main, `10145349b20c3d6294fcf418e7aacf2e1416ec68`](https://github.com/Firemanwolf/Team200/commit/10145349b20c3d6294fcf418e7aacf2e1416ec68).
- Editor: Unity 6000.3.22f1.
- Build: Button Path → Build Web, using the ButtonPathTouch template.
- Integrity: [build-manifest.json](build-manifest.json) records SHA-256 checksums and sizes for all six output files.

This version includes the tutorial, mobile controls, circular toolbar,
automatic return to the start after a fall with placements retained, the level
timer spanning retries, and the team's Google Forms completion analytics.

The source passed all 19 simulation/input check groups and the authored
campaign/scene/prefab validation. WebGL built successfully with zero errors.
The only build warning says the development Pipeline is disabled in Player
builds because no runtime configuration was supplied.

The local browser playtest covered selection, placement, the persistent Remove
toggle, replacing a command, starting a route, completing Level 1 and dismissing
the completion popup while retaining its layout and final time.

Known issue: the local WebGL playtest logged
`Google Forms upload failed: Unknown Error` after completion. Gameplay and the
completion dialog still worked. Recording in the production form has not been
confirmed; this release preserves the latest main implementation unchanged.
Physical iOS/Android testing also remains outstanding.

Keep this release unchanged. Publish subsequent builds in a new directory.
The previous Alpha check remains in `../alpha_check_build/` and at the original
site root.
