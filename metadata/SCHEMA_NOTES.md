# Schema Notes

- `BOOK_METADATA.json`: book-level identity, title set, rights pointer, and trilogy links.
- `EDITIONS_MATRIX.json`: root array of per-language edition bundles with file names, repo paths, source paths, sizes, media types, and SHA-256 values.
- `RIGHTS.json`: canonical machine-readable rights model for this repository.
- `MANIFEST.json`: repository inventory. Hash files and `MANIFEST.json` omit self-referential size/hash values where needed.
- `REPO_INDEX.json`: machine-oriented repository index.
- `metadata/ASSET_MAP.json`: cover and edition asset map.
- `metadata/EDITION_FILES.json`: edition bundle list.
- `metadata/TRILOGY_LINKS.json`: volume order and repository URLs.
- `metadata/COVER_METADATA.json`: source and repository metadata for the cover image.
- `hashes/SHA256SUMS.repo-all.txt`: all non-hash repository files; excludes `hashes/*`.
- `hashes/SHA256SUMS.repo-layout.txt`: mirrors repo-all for this assembled repository, matching the Volume II convention.
- `hashes/SHA256SUMS.source-tree.txt`: source provenance paths, not repository paths.

This repository is not open licensed.
