# Taiwan Tech Night Market / 台科夜市・丸丸辦桌大作戰

(c) 2026 AEML, NTUST — Engineering Materials CT3309301, 2025 midterm review game.

## Deploy to GitHub Pages

1. Create a public repository and upload everything in this folder: `index.html`, `.nojekyll`, `assets/`.
2. Go to **Settings → Pages**. Set **Source** to *Deploy from a branch*, choose branch `main` and folder `/ (root)`.
3. After a minute the game is available at `https://<account>.github.io/<repo>/`.
4. Embed it in Blogger with `blogger-iframe-snippet.html`, replacing the address.

Notes:
- GitHub Pages is served over HTTPS, so GPS, the camera, motion sensors and full screen all work inside the iframe. The `allow=` list in the snippet is what grants them.
- On phones, the "open in a new tab" link gives the most reliable GPS and full-screen experience.
- `data-remote="1"` on the `#cg` element allows the off-campus remote mode. Set it to `"0"` to require GPS.
- Do not edit `index.html`: integrity checks disable the game if the script, question data or credit line is changed.
