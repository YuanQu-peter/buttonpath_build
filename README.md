# ButtonPath builds

Each released build has its own directory and permanent game link. Keep released
files unchanged; publish later builds in a new directory.

| Version | Directory | Status |
| --- | --- | --- |
| Alpha check | [`alpha_check_build/`](alpha_check_build/) | Archived copy of the original published build, byte-for-byte from commit `440c10c` |
| Alpha | [`alpha_build/`](alpha_build/) | 2026-10-20 release from Team200 `1014534` |

## Play the Alpha build

https://yuanqu-peter.github.io/buttonpath_build/alpha_build/

Built with Unity 6000.3.22f1 from
[`1014534`](https://github.com/Firemanwolf/Team200/commit/10145349b20c3d6294fcf418e7aacf2e1416ec68).
See the [release record](alpha_build/README.md) and
[file checksums](alpha_build/build-manifest.json).

## Play the Alpha check build

- Version link: https://yuanqu-peter.github.io/buttonpath_build/alpha_check_build/
- Original link: https://yuanqu-peter.github.io/buttonpath_build/

The original root `index.html`, `Build/`, `TemplateData/`, and `.nojekyll` remain
unchanged so previously shared links continue to serve the same Alpha check game.
The archived version contains the same files with relative asset paths intact.

## Publish later versions

Build an agreed source revision from [Team200](https://github.com/Firemanwolf/Team200)
and put its complete Web output in a new version directory. Keep `index.html`
and its accompanying asset folders together. Record the source commit, release
date and file checksums. Preserve the root files, `alpha_check_build/`, and this
released `alpha_build/` for future playtest comparisons.
