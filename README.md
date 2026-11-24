# Full-quality video files (branch `hq`)

Long videos at full quality are bigger than GitHub's 100 MB file limit, so each one is stored here in 90 MB parts
(`<slug>/<file>.partNN`) with a `manifest.json` (order, sizes, SHA-256). They are joined in the browser and uploaded
to Metricool on the next full go. This branch is kept separate from `main`.
