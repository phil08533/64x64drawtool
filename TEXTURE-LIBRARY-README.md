# Pixel64 Texture Library Archive

This folder-level archive file, `texture-library.json`, preserves the complete named preset catalog for Pixel64 in one portable file.

- **Preset count:** 294
- **Categories:** 13
- **Fields:** category, display name, generator prompt
- **Generation:** offline procedural JavaScript; no API key or cloud service required
- **Live implementation:** `index.html`

The JSON preserves the names and prompts used by the site's texture picker. These are procedural texture recipes/prompts, not pre-rendered PNG files and not outputs from a remote generative-AI model. The generator implementation remains in `index.html`, so this archive can be used to restore or rebuild the catalog later.
