# Examples

Real files produced by TexWeft `0.10.0-beta.2` from the demo library (three materials: `Scan`, `Ceramic 12` with a glossiness map, and `Broken`, which is missing its metallic map on purpose).

| File | What it is |
|---|---|
| [`studio.texweft-spec`](studio.texweft-spec) | The client specification: Unity HDRP 17 mask map, TIFF 8-bit, 256 × 256, files in `Maps/<material>/<material>_Mask.tif`. |
| [`qa-report/report.html`](qa-report/report.html) | The offline report a recipient opens in any browser (download it, then open it). Source thumbnails are embedded. |
| [`qa-report/report.json`](qa-report/report.json) | The same report in machine-readable form, for pipelines and tools. |
| [`delivery-manifest/manifest.json`](delivery-manifest/manifest.json) | The receipt written next to `Ceramic 12_Mask.tif`: SHA-256 of every source and of the output, roles, and every change applied (including `Glossiness → Roughness = 1 − Glossiness`). |

Write your own spec in the app with **Delivery preflight → Edit spec…**, or start from this one.
