# linkedin-extension-config

Public remote selector config for **LinkedIn Message Manager** and **LinkedIn Job Assistant**.

When LinkedIn changes its UI, update `selector-config.json` here and bump `version`. Installed extensions fetch this file daily (and after failed DOM lookups).

Extension source code is **not** in this repo.

## Hotfix workflow

1. Edit `selector-config.json` — bump `"version"`
2. Commit and push to `main`
3. Users get the update within 24 hours (or sooner on the next failed read)

## URL used by extensions

```
https://raw.githubusercontent.com/abaddion/linkedin-extension-config/main/selector-config.json
```
