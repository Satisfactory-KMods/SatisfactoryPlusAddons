# Satisfactory Plus modules

Each optional pack lives in `DataForge/<PackRef>/pack.yml`. SatisfactoryPlus and the pack prerequisites must be installed. Keep matching mod versions on all multiplayer peers.

`SFPAddonWaterDam` provides the default-enabled Water Dam module. It contains a Delivery node, registration of the existing RefinedPower dam recipe, per-section construction costs and the building description. The node directly unlocks construction and waterfall-site scanning. One pack-level selection condition gates the content; its declaration remains discoverable when disabled.

Existing saves adopt newly installed default-enabled modules unless explicitly declined. A node whose recipe and scanner unlocks are already owned completes without payment or another item reward. If the module is disabled and the save is written, its unregistered recipe can be purged; enabling it again can make the node available for another normal completion and Somersloop reward. This behavior is accepted.

No third-party image files are bundled: the module references the dam texture already used by RefinedPower's descriptor. Install a SatisfactoryPlus version supporting Unreal texture object-path module icons.
