# dayframe-assets

Fetch-on-demand binary model artifacts for the [Day Frame](https://github.com/aydo-89/dayframe)
vision pipeline.

Per Day Frame's own storage convention (decision D32, the same pattern `hub/vision/detect.py`'s
`ensure_model()` uses for its base ONNX detector): large binaries are never committed to the
main repo's git history. Instead they live here, as SHA-256-pinned GitHub Release assets, and
the main repo's code fetches + verifies them on demand.

See each release's notes for exact provenance (source checkpoint, export command, pinned
package versions, and the resulting artifact's checksum).
