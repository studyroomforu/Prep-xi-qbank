# Prep XI Q Bank — GitHub Pages (Fast / Lazy Loading)

Upload `index.html` and the entire `data/` folder together. Keep `data/` next to `index.html`.

The site loads only a small metadata file at startup. Question data is split into 6 gzip groups and is loaded on demand when a test or custom-practice selection needs it. This reduces startup time and iPad/Safari memory usage.
