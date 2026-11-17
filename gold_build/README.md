# Gold build

[Play ButtonPath](https://yuanqu-peter.github.io/buttonpath_build/gold_build/). Choose any of the ten levels directly from the title-screen grid.

Released November 17, 2026, using Unity 6000.3.22f1 and the ButtonPathTouch template from [Team200 commit `9a11d0b`](https://github.com/Firemanwolf/Team200/commit/9a11d0b34c4acb1f38b2a2f24727ea15da933c44).

Includes the ten-level campaign and completion stars from Beta, plus cyan moving-platform ghost previews in Levels 7, 8 and 10, a separate current-run timer, direction-neutral lightning-bolt Speed Up and Dash icons, revised Level 1 star-rating guidance, and the Reverse combo explanation. The [build manifest](build-manifest.json) records the size and SHA-256 checksum of every game file.

Validation: all 29 existing simulation checks passed, and the Unity WebGL build completed successfully from the clean source revision. Source files and project settings were unchanged after building.

Browser check: the ten-level menu and Levels 7, 8 and 10 loaded in desktop Chrome. Moving-platform placement displayed cyan previews in those levels; the run timer, lightning icons and Reverse guide rendered. No browser console errors were observed during these checks. Full campaign completion and physical phone testing were not repeated for this release.

The build uses uncompressed WebGL assets and no WebGL threads, matching the previous GitHub Pages releases. Earlier version directories and the original root game remain unchanged.
