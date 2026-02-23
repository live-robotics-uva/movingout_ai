# GitHub Pages Bundle

This folder is self-contained and can be deployed directly to GitHub Pages.

## Required files

- `index.html`
- `segment_cluster_data.json`
- `map.png`

The web page only reads these files from the same folder.

## Deploy (GitHub Pages)

1. Create a repo (or use an existing one).
2. Upload all files in this folder to the repo root (or to a docs folder).
3. In GitHub repo settings:
   - Open **Pages**
   - Set Source to the branch and folder containing these files
4. Open the published URL.

## Notes

- Coordinate range is fixed to `x,y in [-1.2, 1.2]`.
- Background map is loaded from `map.png`.
- Scatter points are segment start points, colored by cluster.
- Overlay panel supports multi-cluster checkbox filtering.
