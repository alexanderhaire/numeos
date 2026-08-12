# numeos

The public site for **Numeos**, an iPhone app — a swipeable feed of
mental-arithmetic puzzles.

- **[numeos site](https://alexanderhaire.github.io/numeos/)** — what the app is,
  with a recording of it running
- **[Privacy policy](https://alexanderhaire.github.io/numeos/privacy.html)**
- **[Support](https://alexanderhaire.github.io/numeos/support.html)**

## Why this repository exists separately

The App Store requires a privacy policy and a support page that resolve from
outside the app, and Guideline 5.1.1(i) additionally requires the policy to be
reachable from inside it. The app's own repository is private, and GitHub Pages
will not serve a private repository on a Free plan — so these few static files
live here instead. The alternative was publishing the entire source of the app
to buy hosting for three pages.

Nothing here is generated from the app repository at build time; the files are
copied across deliberately, which is what keeps the deployment runbook and the
store-listing copy — which sit beside these pages in that repository and should
not be public — out of it.

## Contents

| Path | What it is |
| --- | --- |
| `index.html` | The site itself |
| `privacy.html` | Privacy policy, linked from inside the app |
| `support.html` | Support, contact, reporting and blocking |
| `media/` | The demo recording and screenshots |

The recording in `media/` is a real capture of the app running on an iPhone
simulator, produced by `scripts/demo-video.sh` in the app repository — the app
drives itself through synthetic taps and the screen is recorded. The stills come
from `scripts/screenshots.sh` the same way. Nothing on this site is a mockup.

## Contact

<awhaire@gmail.com>
