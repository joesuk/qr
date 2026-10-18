# qr

Redirect target for the printed QR code that points to <https://joesuk.github.io/qr/>.

This repo is published with GitHub Pages as a project site, so it is served at
`joesuk.github.io/qr/` independently of the main website repo.

## Changing the destination

Edit the Google Drive URL in `index.html` (it appears three times: the
`<meta http-equiv="refresh">` tag, the `<link rel="canonical">` tag, and the
`<a>` link), commit, and push. GitHub Pages redeploys within a minute or so.

Tip: to avoid editing at all, keep a single Drive file and upload new weekly
versions via *Manage versions* in Drive. The file ID, and therefore this
redirect, then never changes.

## One-time GitHub setup

1. Create a **public** repo named `qr` under your account.
2. Push this repo to it.
3. In the repo's *Settings → Pages*, set **Source** to *Deploy from a branch*,
   branch `main`, folder `/ (root)`.

`qr.png` is the QR code image encoding `https://joesuk.github.io/qr`.
