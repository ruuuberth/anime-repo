# Ruuberth Aniyomi Extensions

Published extension repository for **Aniyomi / Anikku / Animiru**.

- Source code: https://github.com/ruuuberth/anime-extensions
- Add this repository in the app with:
  `https://raw.githubusercontent.com/ruuuberth/anime-repo/repo/index.min.json`

| File | Purpose |
|---|---|
| `repo.json` | Repository metadata and signing-key fingerprint (`index_v2` points to the protobuf index) |
| `index.min.json` | Legacy JSON index (one entry per extension) |
| `index.json` | Protobuf index in JSON form |
| `index.pb` | Protobuf index (gzipped) |
| `apk/` | Extension APKs |
| `icon/` | Extension icons |

The `repo` branch is written by the `publish` job of the
[anime-extensions](https://github.com/ruuuberth/anime-extensions) workflow.
