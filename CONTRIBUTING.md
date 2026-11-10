# Contributing

Add each module under `DataForge/SFPAddon<Feature>/` and gate its pack on SatisfactoryPlus. Once a pack exists, run `uv run --locked kdataforge-linter lint DataForge --format github` before submitting changes. Release is intentionally disabled.

`dev` is the default branch and only validates packs. `main` is protected and reserved for release builds.

Keep `Content/` empty and add no C++: the mod is packaged as a KDataForge source mod (descriptor, `Config/`, `DataForge/`). Assets or code require switching the build to full plugin packaging first.
