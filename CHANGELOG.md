# Changelog

## 0.10.0-beta.2
- **Glossiness accepted in delivery preflight.** A material with a `_Glossiness` / `_Smoothness` map now satisfies a roughness channel: the value is complemented automatically and the report lists it as a planned fix (`source.complement`).
- **Delivery folder created for you.** Type a new folder name inside an existing one and TexWeft creates it, instead of asking for an existing folder.
- **Modern folder picker.** *Browse…* now opens the standard Windows Explorer folder dialog.
- **Large screens.** The welcome screen stays centred when the window is maximised on 4K displays.

## 0.10.0-beta.1
- Delivery preflight with client specifications (`.texweft-spec`), visual spec editor and conflict detection against named engine contracts.
- Unity HDRP 17 mask-map contract, area / bilinear filtering for continuous masks.
- Offline HTML + JSON handoff report with source previews.
- Automatic recovery of the material queue after a crash.

## 0.9.0
- Release candidate: library quality review, 8/16-bit inspector, recoverable batches, MSI installer.
