# Methodology — Edition 1

## Objective
Edition 1 reconciles existing cross-reference work rather than attempting to rediscover biblical relationships independently.

## Core principles
1. **Reuse before invention.** Established datasets do the heavy lifting.
2. **Provenance first.** Supporting source families remain identifiable.
3. **Catholic scope.** The research model includes the 73-book Catholic canon.
4. **No silent theological inference.** Cross-reference presence is not automatically labeled quotation, allusion, typology, or doctrine.
5. **Scholar review is non-blocking.** Interpretive items are isolated instead of delaying source-supported publication.

## Edition 1 reconciliation
The general backbone was reconstructed from the raw OpenBible and SoulLiberty/TSK-derived files included in the NEUU source package. It was reconciled with the cross-reference files shipped in *The Catholic Bible* package. Duplicate normalized directed endpoint pairs were merged while source flags were retained.

The resulting master contains **1,171,415 unique directed relationships**.

## Verification model
- **Level A:** two or more independent source families support the normalized relationship.
- **Level B:** one established source family supports it with provenance.
- **Review:** authored/interpretive material reserved for scholarly adjudication.
- **Conflict:** unresolved normalization/source disagreement; not part of verified-only publication views.

Edition 1 reports 580,351 Level A, 590,391 Level B, and 673 review relationships.

## Catholic-specific layer
The seven Deuterocanonical books are Tobit, Judith, Wisdom, Sirach, Baruch, 1 Maccabees, and 2 Maccabees. Edition 1 contains 920 relationships touching these books, including 701 relationships between the Deuterocanon and New Testament.

Catholic Esther and Daniel require special versification care. Edition 1's research architecture preserves source notation and avoids silently forcing incompatible numbering systems.

## Known source discrepancy
The documentation for *The Catholic Bible* describes 207,636 cross-references, while the 73 shipped cross-reference JSON files inspected for Edition 1 contained 213,267 records (210,232 OpenBible-derived, 2,362 Douay-Rheims-derived, and 673 NA27-authored records). Edition 1 records the shipped data rather than silently substituting the README count.

## Interpretation boundary
Edition 1 is a concordance, not a declaration that every edge is a direct quotation. Future scholarly review can approve, reject, or classify review items, after which publication outputs can be regenerated without rebuilding the source-supported foundation.
