# HarmsVis (MRS Edition)

Self-contained HTML app to visualize **harms risk-of-bias**: traffic-light tables and summary bars. Paste your Excel/CSV/TSV and export high-resolution **PNG/TIFF**.

- **Live demo (GitHub Pages)**: https://&lt;your-github-username&gt;.github.io/HarmsVis-MRS/
- **Citable archive (DOI)**: https://doi.org/10.xxxx/zenodo.xxxxxxx
- **Version**: v1.0.0
- **Author**: Mohamad Radwan Sirri (MRS)

## Quick start
1. Open `index.html` locally (double-click) or via GitHub Pages link above.
2. Paste a table from Excel (Option A) or paste CSV/TSV (Option B) and click **Load**.
3. Click **Render Traffic / Render Summary**.
4. Export images via **Download PNG/TIFF** (set **Export width** for DPI-like quality).

## Data format
First column must be **Study**, subsequent columns are **Q1..Qn**. Cell values can be any synonyms of:
- **Yes/Low** → green circle
- **Unsure/Moderate** → yellow circle
- **No/High** → red circle

You can customize synonyms in the **Synonyms** panel.

## Features (v1.0.0)
- Traffic-light table + Summary bars with consistent palette (Green/Yellow/Red).
- Legend (Yes / Unsure / No) with optional text.
- Global/per-row **% ticks** (0–100 by 10), optional segment % labels.
- Auto-fit circles and study-name font sizes; numeric and slider controls for dimensions/spacing.
- **Dynamic question management**: add/remove Q, drag-and-drop reordering, renumber Q→Q1..Qn.
- **Q-marker parser**: paste a block like `Q1: ...`, `Q2 - ...` to auto-assign question texts.
- Traffic footer questions (optional) included in exports.
- High-resolution **PNG/TIFF** export (RGB, 300 DPI-equivalent sizing).

## Sample data
See `sample_data/harmsvis_sample.xlsx` and `sample_data/harmsvis_sample.csv`.

## How to publish (recommended)
- **GitHub Pages**: host `index.html` for a stable, free live link.
- **Zenodo**: connect the GitHub repo and mint a **DOI** per release.
- Update the README with your real links and DOI, then cite as below.

## How to cite
### Vancouver
Sirri MR. HarmsVis (MRS Edition) [software]. Version 1.0.0. Zenodo; 2025. Available from: https://doi.org/10.5281/zenodo.17065698.

### APA
Sirri, M. R. (2025). *HarmsVis (MRS Edition)* (Version 1.0.0) [Software]. Zenodo. https://doi.org/10.5281/zenodo.17065698.

### BibTeX
See `citation.bib` or use the DOI directly once minted.

## License
MIT © 2025 Mohamad Radwan Sirri
https://github.com/sirirradwan-cyber/HarmsVis-MRS/raw/main/harmsvis.enw
https://github.com/sirirradwan-cyber/HarmsVis-MRS/raw/main/harmsvis.ris
## Cite / Download for EndNote
- **EndNote (.ENW):** [Download](https://github.com/sirirradwan-cyber/HarmsVis-MRS/raw/main/harmsvis.enw)
- **RIS (.RIS):** [Download](https://github.com/sirirradwan-cyber/HarmsVis-MRS/raw/main/harmsvis.ris)
