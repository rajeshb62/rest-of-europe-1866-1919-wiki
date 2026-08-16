# Wiki Schema — Rest of Europe 1866–1919

## Domain

Continental European history from the Austro-Prussian War (1866) through the First World War and its immediate aftermath (to ~1920): the unification of Germany and Italy, the German Kaiserreich, the French Second Empire and the Third Republic, the Habsburg Dual Monarchy, the Eastern Question and the Balkans, Tsarist Russia's last half-century, and the road to 1914 and the Great War itself. The United Kingdom is covered in its own wiki.

## Conventions

- File names: lowercase, hyphen-separated, no spaces, with terminal years for events (e.g. `franco-prussian-war-1870-71.md`, `otto-von-bismarck.md`).
- Every page begins with YAML frontmatter.
- Use `[[wikilinks]]` between pages; every page has at least 2 outbound links.
- Narrative-first prose: entity/event/concept pages read like a history-book chapter, not bullets or excerpt-stitching. No "According to Source X" inline; a Sources table sits at the bottom.
- Source discipline (hard): no headword, claim, author, or editorial commentary beyond what the deposited sources support. Contemporary lens only — no modern framing, no retroactive value judgments. Terms not grounded in a source are not used.
- Section on citing pages is **Sources** (not "Primary Sources").
- Local-language terms appear inline with translation in the narrative.
- Provenance: every substantive claim traces to a source file; the Sources table at the bottom lists the exact `sources/*.md` pages used.
- Index pages: narrative arc first (the arc of 1866–1919), then organized nav grouped by type (Entities, Events, Concepts). Concepts favour broad umbrella categories over narrow pairwise comparisons.

## Frontmatter

```yaml
---
title: Page Title
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | event | concept | primary-source
tags: [from taxonomy]
sources:
  - source: slug-of-source-page
confidence: high | medium | low
---
```

`confidence` reflects how well-supported the claims are across sources. `low` = single source or noisy OCR.

## Tag taxonomy

- Regions/nations: germany, prussia, france, austria-hungary, hungary, italy, russia, balkans, spain, ottoman
- Politics: diplomacy, liberalism, conservatism, socialism, nationalism, parliament, monarchy, constitution, church, revolution
- War: war, military, navy, occupation, front, alliance
- Themes: unification, risorgimento, german-question, eastern-question, culturkampf, anti-clericalism, industrialization, finance, empire, wwi
- Metatype: person, state, institution, ideology, movement, event, treaty, battle, doctrine, source

Every tag must appear here.

## Page thresholds

- Create a page when an entity/event/concept appears in 2+ sources OR is central to one source.
- Don't create pages for passing mentions.
- Split pages over ~200 lines.
