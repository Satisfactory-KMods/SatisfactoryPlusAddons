# Contributing

Add each module under `DataForge/SFPAddon<Feature>/` and gate its pack on SatisfactoryPlus. Once a pack exists, validate it with the canonical Rust `kdf` CLI from `Satisfactory-KMods/kdataforge-tools`: run `kdf lint DataForge --format github` (reads `.kdf-editor.toml`, which configures `ci/schemas` and the external `SatisfactoryPlusDataForge` pack dependency), or pass the SatisfactoryPlus core `DataForge` directory alongside `DataForge` to validate both together. Release is intentionally disabled.

`dev` is the default branch and only validates packs. `main` is protected and reserved for release builds.

Keep `Content/` empty and add no C++: the mod is packaged as a KDataForge source mod (descriptor, `Config/`, `DataForge/`). Assets or code require switching the build to full plugin packaging first.
