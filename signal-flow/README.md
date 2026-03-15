# GitHub Pages root files for Signal Flow

These files are intended to be published at the domain root.

Required URLs after deployment:

- `https://<your-domain>/`
- `https://<your-domain>/privacy.html`
- `https://<your-domain>/app-ads.txt`

Important:

- `app-ads.txt` must be reachable from the domain root.
- If you use GitHub Pages with a repository subpath such as
  `https://username.github.io/signalflow/`, AdMob may still look for
  `https://username.github.io/app-ads.txt`.
- The safest option is a root site such as:
  - `https://username.github.io/`
  - or a custom domain such as `https://signalflow.app/`

Files:

- `index.html`: simple landing page
- `privacy.html`: privacy policy page
- `app-ads.txt`: AdMob authorization file
