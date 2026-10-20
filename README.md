# ButtonPath builds

Each released build has its own directory and permanent game link. Keep released
files unchanged; publish later builds in a new directory.

| Version | Directory | Status |
| --- | --- | --- |
| Alpha check | [`alpha_check_build/`](alpha_check_build/) | Archived copy of the original published build, byte-for-byte from commit `440c10c` |
| Alpha | [`alpha_build/`](alpha_build/) | Reserved; waiting for the team's remaining changes, with no game build published yet |

## Play the Alpha check build

- Version link: https://yuanqu-peter.github.io/buttonpath_build/alpha_check_build/
- Original link: https://yuanqu-peter.github.io/buttonpath_build/

The original root `index.html`, `Build/`, `TemplateData/`, and `.nojekyll` remain
unchanged so previously shared links continue to serve the same Alpha check game.
The archived version contains the same files with relative asset paths intact.

## Publish Alpha when the team is ready

Build the agreed source revision from
[Team200](https://github.com/Firemanwolf/Team200), then put the complete Web output
inside `alpha_build/`. Its `index.html` and all accompanying asset folders must
stay together. Do not replace the root files or anything in `alpha_check_build/`.

The planned game URL is
`https://yuanqu-peter.github.io/buttonpath_build/alpha_build/`.
It is not a playable release yet. After publishing, record the source commit
and release date in `alpha_build/README.md`, and preserve that release for future
playtest comparisons.
