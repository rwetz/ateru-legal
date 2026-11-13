---
title: "Ateru Anime ID Map"
permalink: /anime-id-map
---

# Ateru's derived anime ID map — attribution copy

[Download the CSV](https://rwetz.github.io/ateru-legal/attribution/manami-map/mal-anilist-map-2026-27.csv) · [Full license text](https://rwetz.github.io/ateru-legal/attribution/manami-map/LICENSE.txt)

`mal-anilist-map-2026-27.csv` is a machine-readable copy of the 18,858 MyAnimeList-to-AniList ID pairs bundled in Ateru. It is derived from [manami-project/anime-offline-database release 2026-27](https://github.com/manami-project/anime-offline-database/releases/tag/2026-27). The upstream [license](https://github.com/manami-project/anime-offline-database/blob/2026-27/LICENSE), reproduced as `LICENSE.txt`, specifies the [Open Database License 1.0](https://opendatacommons.org/licenses/odbl/1-0/) for the database and the [Database Contents License 1.0](https://opendatacommons.org/licenses/dbcl/1-0/) for individual contents. Ateru makes this derived database available under ODbL 1.0, with the same upstream database contents license.

Ateru extracts records containing both a MyAnimeList anime URL and an AniList anime URL, retains the first mapping for each MyAnimeList ID, discards the other metadata, sorts by MyAnimeList ID, and stores the result as delta-encoded integers in `app/src/engines/malAniListMap.ts`. `tool/build-mal-map.mjs` records the upstream extraction method. This CSV decodes that exact bundled map into two integer columns. It contains no user data.

The CSV's SHA-256 is `6c72c123bdafda380d90c02a830bc250c3d81dbddeedb43ee390d7171e9f1845`.
