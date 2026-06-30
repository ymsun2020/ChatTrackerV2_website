# ChatTracker Project Website

This repository contains a static project page for ChatTracker. It highlights:

- open-source code
- raw experiment results
- manual review results
- the NeurIPS 2024 conference version citation and links
- the IEEE TPAMI 2026 journal version citation and links

## Structure

- `index.html` is the website entry point.
- `assets/css/styles.css` contains the visual system and responsive layout.
- `assets/js/main.js` controls citation tabs and BibTeX copying.
- `assets/images/` contains project figures used by the page.
- `data/resources.json` mirrors the public resource and paper links for downstream tools.
- `resources/raw-results/` and `resources/manual-review/` are placeholders for released artifacts.

## Local Preview

Run a static server from the repository root:

```sh
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Link Targets

The source code URL is set to the expected public release location. Raw results are currently linked through Baidu Netdisk:

- `https://github.com/10225102484/Chattracker`
- `https://pan.baidu.com/s/1e-cIfJJyFKq_UW28-a2efA?pwd=ae5c`
- extraction code: `ae5c`

If the final repository or release tag differs, update those URLs in `index.html` and `data/resources.json`.
