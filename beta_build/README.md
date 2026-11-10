# Beta build

[Play ButtonPath](https://yuanqu-peter.github.io/buttonpath_build/beta_build/). Choose any of the ten levels directly from the title-screen grid.

Released November 10, 2026, using Unity 6000.3.22f1 and the ButtonPathTouch template from [Team200 commit `57a6a13`](https://github.com/Firemanwolf/Team200/commit/57a6a13b9f3ddf7b539acf8c6655501e6c0bb19e).

Includes The Crossing Hall's two routes, Level 10, completion stars, and updated menus and tutorials. The [build manifest](build-manifest.json) records the size and SHA-256 checksum of every game file.

Validation: all 29 simulation checks passed. All ten authored levels were captured successfully with no missing scene or prefab scripts. Level 9's upper, lower relay, and carried-speed solutions passed against the authored geometry; renamed button IDs were resolved by position in the validation snapshot. The Unity WebGL build completed successfully.

Browser check: the ten-level menu, Level 9, and Level 10 loaded successfully in desktop Chrome with no console errors.
