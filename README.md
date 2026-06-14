# json2vec docs snapshot

This repo contains a Quarto-rendered snapshot of selected `json2vec` docs copied
from `/Users/grantham/Desktop/json2vec-oss/docs`.

## Quarto build

The Quarto project lives in `_quarto.yml` and renders into `site/`.

Install or run Quarto 1.9.20+ and render:

```sh
uvx --from quarto-cli quarto render
```

Preview locally:

```sh
uvx --from quarto-cli quarto preview
```

The source pages are Quarto `.qmd` files. The `docs/data/` files are included
so examples can refer to local sample data.
