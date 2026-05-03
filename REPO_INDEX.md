# Repository Index

This repository contains the public reading package for Volume III of Ivan Kotov's Qubit of Hope trilogy.

## Top-Level Files

- `README.md`: human entry and direct downloads table.
- `DOWNLOADS.md`: simple download table with rights warning.
- `RELEASE_STATUS.md`: assembly and release status.
- `MACHINE_ENTRY.md`: compact machine entry.
- `REPO_INDEX.md`: this human-readable map.
- `REPO_INDEX.json`: machine-readable repository map.
- `BOOK_METADATA.json`: book-level metadata.
- `EDITIONS_MATRIX.json`: language and format matrix.
- `MANIFEST.json`: repository file inventory.
- `RIGHTS.json`: machine-readable rights summary.
- `LICENSE.txt`: human-readable rights terms.
- `NOTICE.txt`: reader and mirror notice.
- `CITATION.cff`: citation metadata.
- `llms.txt`: concise machine index.
- `llms-full.txt`: fuller machine index without book text.
- `.gitignore`: parity with Volumes I and II; ignores OS clutter only.

## Folders

- `covers/`: cover image, preserving the original source file name.
- `editions/`: reader files by language and format.
- `hashes/`: SHA-256 manifests.
- `metadata/`: supporting machine metadata.

## Editions

| language | name | Markdown | PDF | EPUB | FB2 |
|---|---|---|---|---|---|
| `ru` | Russian | [md](editions/ru/md/Kubit_Nadezhdy_Tom_III_ru.md) | [pdf](editions/ru/pdf/Kubit_Nadezhdy_Tom_III_ru.pdf) | [epub](editions/ru/epub/Kubit_Nadezhdy_Tom_III_ru.epub) | [fb2](editions/ru/fb2/Kubit_Nadezhdy_Tom_III_ru.fb2) |
| `en` | English | [md](editions/en/md/Qubit_of_Hope_Volume_III_en.md) | [pdf](editions/en/pdf/Qubit_of_Hope_Volume_III_en.pdf) | [epub](editions/en/epub/Qubit_of_Hope_Volume_III_en.epub) | [fb2](editions/en/fb2/Qubit_of_Hope_Volume_III_en.fb2) |
| `fr` | French | [md](editions/fr/md/Qubit_de_l_espoir_Tome_III_fr.md) | [pdf](editions/fr/pdf/Qubit_de_l_espoir_Tome_III_fr.pdf) | [epub](editions/fr/epub/Qubit_de_l_espoir_Tome_III_fr.epub) | [fb2](editions/fr/fb2/Qubit_de_l_espoir_Tome_III_fr.fb2) |
| `es` | Spanish | [md](editions/es/md/El_cubit_de_la_esperanza_Tomo_III_es.md) | [pdf](editions/es/pdf/El_cubit_de_la_esperanza_Tomo_III_es.pdf) | [epub](editions/es/epub/El_cubit_de_la_esperanza_Tomo_III_es.epub) | [fb2](editions/es/fb2/El_cubit_de_la_esperanza_Tomo_III_es.fb2) |
| `de` | German | [md](editions/de/md/Kubit_der_Hoffnung_Band_III_de.md) | [pdf](editions/de/pdf/Kubit_der_Hoffnung_Band_III_de.pdf) | [epub](editions/de/epub/Kubit_der_Hoffnung_Band_III_de.epub) | [fb2](editions/de/fb2/Kubit_der_Hoffnung_Band_III_de.fb2) |
| `nl` | Dutch | [md](editions/nl/md/De_qubit_van_hoop_Deel_III_nl.md) | [pdf](editions/nl/pdf/De_qubit_van_hoop_Deel_III_nl.pdf) | [epub](editions/nl/epub/De_qubit_van_hoop_Deel_III_nl.epub) | [fb2](editions/nl/fb2/De_qubit_van_hoop_Deel_III_nl.fb2) |
| `zh-CN` | Simplified Chinese | [md](editions/zh-CN/md/Kubit_Nadezhdy_Tom_III_zh_CN.md) | [pdf](editions/zh-CN/pdf/Kubit_Nadezhdy_Tom_III_zh_CN.pdf) | [epub](editions/zh-CN/epub/Kubit_Nadezhdy_Tom_III_zh_CN.epub) | [fb2](editions/zh-CN/fb2/Kubit_Nadezhdy_Tom_III_zh_CN.fb2) |

## Trilogy Bridge

- Volume I: https://github.com/Kot141078/qubit-of-hope-volume-i
- Volume II: https://github.com/Kot141078/qubit-of-hope-volume-ii
- Volume III: https://github.com/Kot141078/qubit-of-hope-volume-iii

## Integrity Manifests

- `hashes/SHA256SUMS.repo-all.txt`: all non-hash repository files, excluding `hashes/*` to avoid recursive hash instability.
- `hashes/SHA256SUMS.repo-layout.txt`: mirrors `repo-all` in this repository, matching the Volume II convention where repo-layout and repo-all have the same content set.
- `hashes/SHA256SUMS.metadata-only.txt`: root metadata/readme surfaces and `metadata/*` files.
- `hashes/SHA256SUMS.source-tree.txt`: source provenance hashes using original local source paths, not repository paths.

## Rights

All rights reserved. This repository is public for reading and personal local download only. It is not an open-license reuse surface.
