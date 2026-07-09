# 3cats.studio

Static one-page site for **3Cats Studio** — served via GitHub Pages at https://3cats.studio.

`index.html` is fully self-contained (all fonts + art inlined as data URIs, zero external requests).
Source of truth lives in the private game repo under `site/` (built by `tools/build-site.mjs`).
To update: rebuild there, copy `site/index.html` here, commit, push.
