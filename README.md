# dayframe-assets

Fetch-on-demand binary model artifacts for the Day Frame vision pipeline
(D32 pattern: SHA-pinned release assets, never committed to the main repo's
git history).

## Licensing

The YOLO-World ONNX exports in these releases are derived from
[Ultralytics](https://github.com/ultralytics/ultralytics) `yolov8s-worldv2`
weights and are therefore distributed under the **GNU AGPL-3.0** license
(https://www.gnu.org/licenses/agpl-3.0.html). Source model, export recipe,
and pinned package versions are documented in the Day Frame repository's
`hub/vision/MODEL_MANIFEST.md`. YOLO-World is by Tencent AI Lab
(https://github.com/AILab-CVC/YOLO-World); the Ultralytics packaging used
for this export is AGPL-3.0-or-Enterprise.

No warranty. These artifacts exist solely so a private prototype can fetch
its detector weights reproducibly.
