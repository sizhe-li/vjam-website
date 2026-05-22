# VJAM — Turning Video Models into Generalist Robot Policies

Project page for **VJAM**: a closed-loop video-to-action policy that pairs an action-free
video world model with a Jacobian inverse dynamics model.

## Live site

Once GitHub Pages is enabled (Settings → Pages → Branch: `main`), the page is served at
<https://sizhe-li.github.io/vjam-website/>.

## Local preview

```bash
cd /path/to/vjam-website
python3 -m http.server 8770
# open http://localhost:8770/
```

## Layout

```
index.html              # single-page project site
static/
  css/                  # Bulma + project styles (vjam.css)
  js/                   # Bulma carousel/slider helpers + script.js
  figures/              # paper figures (png)
  videos/               # all result videos
    results/            # raw source videos (h264 + mpeg4)
    results_h264/       # browser-decodable h264 re-encodes of mpeg4 sources
```

## Acknowledgments

Page template adapted from
[Nerfies](https://github.com/nerfies/nerfies.github.io) (CC BY-SA 4.0).
