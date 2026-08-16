# Wiki Log — Rest of Europe 1866–1919

> Chronological record of wiki actions. Append-only.
> Format: `## [YYYY-MM-DD] action | subject`

## [2026-08-16] create | Source-layer foundation (prior)
- 52 primary-source pages and 53 raw OCR texts ingested across the 1866–1919 corpus (German, French, Italian, Russian, Hungarian). Sources span: Sybel & Lenz (German unification), Delord & Ollivier & Hanotaux (France), Garibaldi & Tivaroni & Oriani & Fortunato & Cadorna & Frescura & Comando Supremo (Italy), Beksics & Sosnosky & Conrad & Czernin & Redlich & Franz Ferdinand (Austria-Hungary), Kornilov & Granat & Witte & Zhevakhov & Denikin (Russia), Recouly (Great War), Sabatier & Lagardelle & Péguy (French religion/socialism).
- SCHEMA.md initialized.

## [2026-08-16] create | Entity/Event/Concept layer begun
- Goal: build the full Karpathy-style second layer (entities, events, concepts) to match the depth of the sibling Rest of Europe 1800–1865 wiki, then deploy.

## [2026-08-16] create | E/E/C layer built (157 pages over 52 sources)
- Built 62 entity, 57 event, and 38 concept pages (157 total) across the German-unification, French, Austrian-Hungarian, Italian, Russian, and Great War clusters, created via parallel subagent batches from the 52 source pages and their raw OCR texts.
- Key concept pages added: roman-question, triple-alliance, socialism-in-france (created to resolve wikilinks); event expedition-of-the-thousand-1860.
- Rebuilt index.md into Karpathy sectioned format (narrative arc first, then Entities/Events/Concepts grouped by theme). Created SCHEMA.md, log.md, _meta/style-guide.md, _meta/page-inventory.md.
- Quality audits: 0 broken wikilinks (fixed 9 line-wrapped links), 0 EEC orphans (added inbound links for 5), 52/52 sources cited (added delord t4/t6 citations), 0 YAML frontmatter errors (PyYAML-validated all 209 pages).

## [2026-08-16] lint | 0 issues found
- Full audit clean: frontmatter valid, wikilinks resolve, no orphans, all sources cited.

