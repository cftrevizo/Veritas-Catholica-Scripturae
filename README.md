# Veritas Catholica Scripturae
## The Catholic 73-Book Scripture Cross-Reference Concordance — Edition 1

**Veritas Catholica Scripturae (VCS)** is an open, provenance-first research concordance that reconciles existing Bible cross-reference datasets into a Catholic 73-book framework.

Edition 1 contains **1,171,415 unique directed cross-reference relationships**. It is designed as research infrastructure: it preserves source provenance, separates source-supported relationships from interpretive review items, and makes Catholic/Deuterocanonical relationships visible without claiming that every cross-reference is a quotation or doctrinal proof.

### Edition 1 highlights
- 73-book Catholic framework
- 1,171,415 unique directed relationships
- 580,351 Level A (multi-source) relationships
- 590,391 Level B (single established-source) relationships
- 673 relationships isolated for scholar review
- 920 relationships touching the seven Deuterocanonical books
- 701 Deuterocanon ↔ New Testament relationships
- SQLite database, compressed CSV, Excel index, study guides, and visualizations

## Start here
- `METHODOLOGY.md` — how Edition 1 was reconciled and classified
- `NOTICE.md` — upstream sources, attribution, and licensing
- `data/master/master_edges.csv.gz` — full compressed master edge list
- `database/veritas_catholica_scripturae.sqlite` — queryable research database
- `data/catholic-specific/catholic_specific_edges.csv` — Catholic-specific subset
- `data/scholar-review/review_queue.csv` — non-blocking scholar-review queue
- `study-guides/` — human-readable documentation
- `visualizations/` — Edition 1 maps

## What the data means
A cross-reference can indicate quotation, allusion, shared language, parallel event, thematic similarity, editorial association, or another relationship. **Presence in VCS does not by itself prove literary dependence, canonicity, or Catholic doctrine.** Edition 1 intentionally leaves interpretive adjudication to qualified scholars and preserves provenance so those judgments can be audited.

## Why this project exists
Most large machine-readable cross-reference datasets are organized around the 66-book Protestant canon. VCS reconciles that existing work with Catholic-source material so Tobit, Judith, Wisdom, Sirach, Baruch, 1–2 Maccabees, and the Catholic biblical tradition are not invisible to computational study.

## Contributing
Corrections and scholarly review are welcome. See `CONTRIBUTING.md`. Please cite the exact verse pair, source, and reason for any proposed reclassification.

## License
Original VCS compilation, organization, metadata, and documentation are offered under **CC BY 4.0**, except where third-party components retain their own licenses or public-domain/CC0 status. See `LICENSE.md` and `NOTICE.md` before redistributing source-derived data.

## Repository
https://github.com/cftrevizo/Veritas-Catholica-Scripturae
