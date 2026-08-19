# KKS Public Files

Public file-hosting repo for Kool Kat Science student-facing materials (worksheets, handouts, unit PDFs), served via GitHub Pages.

## Structure

- `docs/` — published via GitHub Pages; this is the folder students actually browse.
- `docs/index.html` — landing page listing available materials.
- `docs/materials/<unit-folder>/` — PDFs organized by unit/program.

## Adding a new file

1. Drop the PDF into the appropriate `docs/materials/<unit>/` folder (create one if it doesn't exist yet).
2. Add a link to it in `docs/index.html`.
3. Commit — GitHub Pages rebuilds automatically within a minute or two.

## Important — this repo is PUBLIC

Do not add anything containing student names, grades, or other identifying information. Public worksheets, handouts, and answer keys (without names) only.

## Enabling GitHub Pages (one-time, manual)

Settings → Pages → Source: **Deploy from a branch** → Branch: **main**, folder: **/docs** → Save. Site will be live at `https://daveschoeff.github.io/kks-public-files/`.
