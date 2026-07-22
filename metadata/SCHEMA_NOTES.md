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

This repository is not open licensed.

## v1.0.2 integrity semantics

- `hashes/SHA256SUMS.source-tree.txt`: protected reading and cover assets, using repository-relative paths and exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.repo-layout.txt`: all non-checksum repository files, using repository-relative paths and exact staged-byte SHA-256 values; mirrors repo-all according to the existing repository design.
- `hashes/SHA256SUMS.repo-all.txt`: all non-checksum repository files, using exact staged-byte SHA-256 values.
- `hashes/SHA256SUMS.metadata-only.txt`: legal, navigation, index, and metadata files, using exact staged-byte SHA-256 values.
- Checksum manifests exclude `hashes/*` from repo-wide coverage to avoid recursive hash instability.
